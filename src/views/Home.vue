<template>
    <div class="home">
        <h1>Welcome to Home</h1>
        <p>This is the Home page of your application.</p>
    </div>
</template>

<script>
export default {
    name: "Home",
    data() {
        return {
            message: "Hello from Home!"
        };
    },
    methods: {
        greet() {
            console.log(this.message);
        }
    }
};
</script>

<style scoped>

</style>