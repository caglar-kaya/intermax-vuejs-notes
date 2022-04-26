<script>
import ChildCompEmits from './ChildCompEmits.vue'

export default {
  components: {
    ChildCompEmits
  },
  data() {
    return {
      childMsg: 'No child msg yet'
    }
  }
}
</script>

<template>
  <ChildCompEmits @response="(msg) => childMsg = msg" />
  <p>{{ childMsg }}</p>
</template>