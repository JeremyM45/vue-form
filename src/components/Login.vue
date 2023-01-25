<script>
    export default{
        name: "Login",

    }
</script>
<template>
    <div class="bg-slate-900/80 w-screen lg:w-[60rem] py-[8rem] items-center justify-center md:justify-end flex flex-row gap-x-80">
        <div class="text-slate-300 flex flex-col px-12 max-w-[55ch]">
            <h3 class="text-3xl pb-4">Already have an account?</h3>
            <p class="text-xl pb-2">Click the button below to be taken to the login screen.</p>
            <div class="flex justify-center">
                <button class="border border-slate-300 p-1 px-4 text-sm hover:bg-white hover:text-black duration-300">LOG IN</button>
            </div>
        </div>
    </div>
</template>