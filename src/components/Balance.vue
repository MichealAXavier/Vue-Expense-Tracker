<template>
    <h4>Your Balance</h4>
    <h1 id="balance">Rs{{ total }}</h1>
</template>


<script setup>
//setup() function is used inside a Vue component to initialize the component's state, 
//define reactive properties, set up event listeners, 
//and perform other initialization tasks.
const props = defineProps({
    total: {
        type: Number,
        required: true,
    },
});
</script>