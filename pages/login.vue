<template>
  <LoginTemplate />
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  layout: 'ibook',
  middleware: 'user'
})
</script>

<style lang="scss" scoped></style>
