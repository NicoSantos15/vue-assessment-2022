<template>
  <div class="challenge">
    <h1>Bug Challenge 2</h1>
    <component-1 />
  </div>
</template>

<script>
import Component1 from '@/components/Component1'

export default {
  name: 'Challenge2',
  components: {
    Component1
  },
  data() {
    return {
      msg: 'Congrats you have discovered the issue',
    }
  }
}
</script>
