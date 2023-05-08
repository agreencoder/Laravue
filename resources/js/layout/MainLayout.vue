<template>
  <Link href="/">Home</Link>
  <Link href="/show">Show</Link>
  <slot />
</template>

<script setup>
import {Link} from '@inertiajs/inertia-vue3'
</script>

