<template>
  <component
    :is="tag"
    :class="[
      buttonVariants({ variant, size }),
      className
    ]"
    :disabled="disabled"
    v-bind="$attrs"
  >
    <slot />
  </component>
</template>

<script setup>
import { computed } from 'vue';
import { buttonVariants } from '.';

defineProps({
  variant: {
    type: String,
    default: 'default',
  },
  size: {
    type: String,
    default: 'default',
  },
  disabled: {
    type: Boolean,
    default: false,
  },
  tag: {
    type: String,
    default: 'button',
  },
  className: {
    type: String,
    default: '',
  },
});
</script>