<script>
    export default {
        name: "SignupForm",

    }
</script>

<template>
    <form class="w-full">
        <div class="border-b border-slate-500 flex flex-row px-2 justify-between">
            <input 
                class="select-none focus:outline-0 w-full"
                type="text"
                name="name"
                placeholder="YOUR NAME"
                
            ><i class="fa-sharp fa-solid fa-user text-slate-500 pt-1"></i>
        </div>
        <div class="border-b border-slate-500 flex flex-row px-2 justify-between">
            <input 
                class="select-none focus:outline-0 w-full"
                type="text"
                name="supervisor"
                placeholder="SUPERVISOR'S NAME"
            />
            <i class="fa-solid fa-briefcase text-slate-500 pt-1"></i>
        </div>
        <div class="border-b border-slate-500 flex flex-row px-2 justify-between"> 
            <input 
                class="select-none focus:outline-0 w-full"
                type="email"
                name="email"
                placeholder="YOUR EMAIL"
            />
            <i class="fa-solid fa-envelope text-slate-500 pt-1"></i>
        </div>
        <button type="submit" class="border border-transparent bg-red-400 text-white font-semibold p-1 hover:bg-white hover:text-red-400 duration-300 hover:border-red-400">REQUEST ACCESS</button>
    </form>
</template>