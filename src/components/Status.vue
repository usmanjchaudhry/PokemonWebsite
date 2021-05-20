<template>
    <div>
        <button @click="status=!status"> change status </button>{{status}}

        <p> This is coming from Status.vue Component </p>
    </div>


</template>

<script>
export default {
    data: () => {
    return {
        status:false
    }
    
}

}
</script>
