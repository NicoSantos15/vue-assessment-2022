<template>
  <div class="challenge">
    <h1>Bug Challenge 3</h1>
    <component-2 :msg='msg' />
    <!-- This could be implemented as a global 
    <div class="flower">
      <img src="https://images.unsplash.com/photo-1613539246066-78db6ec4ff0f?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1000&q=80" 
      alt="Flower1">
    </div>
    -->
  </div>
</template>

<script>
import Component2 from '@/components/Component2'

export default {
  name: 'Challenge2',
  components: {
    Component2
  },
  data() {
    return {
      msg: [
        'Congrats you have discovered the issue',
        'Don\'t forget to commit this solution'
      ]
    }
  }
}
</script>
