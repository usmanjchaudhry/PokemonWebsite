<template>
    <div>
        <h3> My Profile </h3>
       <app-status />

    </div>
</template>

<script>
import Status from '../components/Status.vue'

    export default {
        components: {
           'app-status': Status
        }
    }
    </script>

    <style scoped>

    </style>