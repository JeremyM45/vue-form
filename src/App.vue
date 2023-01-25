<script>
    import Login from './components/Login.vue';

    export default {
        name: "App",
        components: {
            Login,
        }
    }
</script>

<template>
    <div class="h-screen bg-blue-500 flex justify-center items-center">
        <Login />
    </div>
</template>