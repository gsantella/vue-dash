<script>

export default {
       
    data() {
        return {
            apiData: {}
        }
    },
    
    async mounted() {

        //Async-Await Based Way
        const response = await fetch("https://quiet-moon-f08e.shsbt.workers.dev")
        this.apiData = await response.json()
    
    }

}

</script>

<template>
    <h1>Some data from the api is {{ apiData }} in {{ apiData }}!</h1>
</template>