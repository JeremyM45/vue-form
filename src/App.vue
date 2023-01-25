<script>
    import Login from './components/Login.vue';
    import Signup from './components/Signup.vue'

    export default {
        name: "App",
        components: {
            Login,
            Signup
        }
    }
</script>

<template>
    <div class="h-screen bg-blue-500 flex justify-center items-center">
        <div class="absolute left-96">
            <Signup />
        </div>
        <Login />
    </div>
</template>