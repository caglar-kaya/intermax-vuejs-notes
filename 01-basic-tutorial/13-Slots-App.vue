<script>
import ChildCompSlots from './ChildCompSlots.vue'

export default {
  components: {
    ChildCompSlots
  },
  data() {
    return {
      msg: 'from parent'
    }
  }
}
</script>

<template>
  <ChildComp>Message: {{ msg }}</ChildComp>
</template>