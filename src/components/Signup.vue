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
    <div class="bg-white w-[30rem] h-[40rem]">
        <div class="flex flex-col p-20">
            <h1 class="text-red-400 text-3xl font-bold">REQUEST ACCESS</h1>
            <SignupForm />
        </div>
    </div> 
</template>
