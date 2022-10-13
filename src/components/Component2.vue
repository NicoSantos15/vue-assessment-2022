<template>
    <div>
        <p>{{ msg[0] }}</p>
        <p>{{ msg[1] }}</p>
    </div>
</template>

<script>
export default {
    name: 'Component2',
    props: {
        msg: {
            require: true,
            type: Array
        }
    }
}
</script>