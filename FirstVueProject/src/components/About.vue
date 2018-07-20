<template>
   <div id="about">
       <h1>Hello {{ their_name }}, This is an About Page</h1>
       <p>This is the about page. You can easily understand what you are seeing at this page.</p>
   </div> 
</template>

<script>
export default {
    name: 'About',
    data() {
        return {
            their_name: this.$route.params.name
        }
    }
}
</script>

<style>

</style>

