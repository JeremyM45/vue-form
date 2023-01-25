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
    <div class="h-full min-h-screen w-screen min-w-full bg-[url('/img/1014.jpg')] flex justify-center items-center flex-col md:flex-row">
        <div class="md:absolute md:mr-[30rem] lg:mr-[25rem]">
            <Signup />
        </div>
        <Login />
    </div>
</template>