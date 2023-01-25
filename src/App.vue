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
    <div class="h-screen w-screen bg-[url('/img/1014.jpg')] flex justify-center items-center">
        <div class="absolute mr-[25rem]">
            <Signup />
        </div>
        <Login />
    </div>
</template>