<template>
  <div class="challenge">
    <h1>Bug Challenge 1</h1>
    <p>{{ this.msg }}</p>
    <p>{{ this.msg2 }}</p>
  </div>
</template>

<script>
export default {
  name: 'Challenge1',
  data() {
    return {
      msg: 'Congrats you have discovered the issue',
      msg2: 'Don\'t forget to commit this solution'
    }
  }
}
</script>
