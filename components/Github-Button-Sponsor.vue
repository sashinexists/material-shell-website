<template>
  <div>
    <v-btn
      rounded
      depressed
      link
      color="primary"
      href="https://github.com/sponsors/PapyElGringo"
      class="overflow-hidden px-2 px-md-4"
    >
      <v-icon class="ml-md-n1 mr-md-2">mdi-heart</v-icon>
      <span class="hidden-sm-and-down">Sponsor</span>
    </v-btn>
  </div>
</template>
<script lang="ts">
export default {
  props: ['stars'],
}
</script>
<style lang="scss" scoped>
.v-btn {
  min-width: 48px !important;
}
</style>
