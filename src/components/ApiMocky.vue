<script>

export default {
       
    data() {
        return {
            apiData: {}
        }
    },
    
    async mounted() {

        //Async-Await Based Way
        const response = await fetch("https://run.mocky.io/v3/9fd4932a-dffb-4a31-95b6-705bb45e0d5e")
        this.apiData = await response.json()
    
    }

}

</script>

<template>
    <h1>Some data from the api is {{ apiData.drink.brand }} in {{ apiData }}!</h1>
</template>