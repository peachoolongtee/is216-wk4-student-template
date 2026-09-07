<script setup>
    import { ref } from 'vue'

    // Add code here
    const obj = {
        src: '../../public/assets/me.png',
        width: 200,
        height: 200,

    }
    import me from '../../public/assets/me.png'
    const width = ref(200)
    const height = ref(200)

</script>

<template>

    <!-- Add code here -->
    <img v-bind='obj'>
    <img v-bind:src='me' v-bind:width v-bind:height>
</template>
