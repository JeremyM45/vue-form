<script>
import SignupForm from './SignupForm.vue';
    export default {
        name: "Signup",
        components: {
            SignupForm,
        }
    }
</script>

<template>
    <div class="bg-white w-screen md:w-fit">
        <div class="flex flex-col p-14">
            <h1 class="text-red-400 text-3xl font-bold pb-10">REQUEST ACCESS</h1>
            <SignupForm />
        </div>
    </div> 
</template>
