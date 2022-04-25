<script>
import ChildCompProps from './ChildCompProps.vue'

export default {
  components: {
    ChildCompProps
  },
  data() {
    return {
      greeting: 'Hello from parent'
    }
  }
}
</script>

<template>
  <ChildCompProps :msg="greeting"/>
</template>