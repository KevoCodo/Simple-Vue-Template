<template>
    <div>
        <h1>{{title}}</h1>
        <h1>Welcome {{msg}}</h1>
        <button v-on:click='greeting'>Click Here</button>
    </div>
</template>

<script>
export default {
    name: 'Navbar',
    data(){
        return{
           title: 'Welcome to Vue Js Practice' 
        }
    },
    props:{
      
    },
    methods:{
        greeting(){
            alert('clicked');
        }
    }
    }
</script>

<style scoped>

</style>


<!--What is code splitting
    Transpulation
    Salesforce
    BlueOcean
    Legacy
    Evestment - Networking opportunity
    Micro frontends
    Monolithic Frontends
    hash - allows for files to be cached for re-render
    webpack-manifest-plugin
    devtools network filters - alerts
    helps reduce already loaded files
-->