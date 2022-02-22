<script>

export default {
       
    data() {
        return {
            apiData: {}
        }
    },
    
    async mounted() {

        //Async-Await Based Way
        const response = await fetch("https://backendapisample.gsantella.repl.co/api")
        this.apiData = await response.json()
    
    }

}

</script>

<template>
    <h1>Some data from the api is {{ apiData }} in {{ apiData }}!</h1>
</template>