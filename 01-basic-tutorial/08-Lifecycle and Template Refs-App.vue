<script>
export default {
  mounted() {
    this.$refs.refNameForParagraph.textContent =  "Caglar Kaya";
  }
}
</script>

<template>
  <p ref="refNameForParagraph">hello</p>
</template>