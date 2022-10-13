<template>
    <div v-if="string.length > 0">
        <p>Congrats you have discovered the issue</p>
        <p>Don't forget to commit this solution</p>
    </div>
</template>

<script>
    export default {
        name: 'Component1',
        data() {
            return {
                string: " "
            }
        }
    }
</script>