<script>
    export default {
        name: "SignupForm",
        data(){
            return {
                name: '',
                supervisor: '',
                email: ''
            }
        },
        methods: {
            onSubmit(e){
                e.preventDefault()
                alert(
                    'name: ' + this.name + "\n" + 'supervisor: ' + this.supervisor + "\n" + 'email: ' + this.email
                )
                this.name = ''
                this.supervisor = ''
                this.email = ''
            }
        }
    }
</script>

<template>
    <form @submit="onSubmit" class="lg:w-[20rem] flex flex-col gap-y-8">
        <div class="border-b border-slate-500 flex flex-row px-2 justify-between">
            <input 
                class="select-none focus:outline-0 w-full"
                type="text"
                name="name"
                placeholder="YOUR NAME"
                required
                v-model="name"
            ><i class="fa-sharp fa-solid fa-user text-slate-500 pt-1"></i>
        </div>
        <div class="border-b border-slate-500 flex flex-row px-2 justify-between">
            <input 
                class="select-none focus:outline-0 w-full"
                type="text"
                name="supervisor"
                placeholder="SUPERVISOR'S NAME"
                required
                v-model="supervisor"
            />
            <i class="fa-solid fa-briefcase text-slate-500 pt-1"></i>
        </div>
        <div class="border-b border-slate-500 flex flex-row px-2 justify-between"> 
            <input 
                class="select-none focus:outline-0 w-full"
                type="email"
                name="email"
                placeholder="YOUR EMAIL"
                required
                v-model="email"
            />
            <i class="fa-solid fa-envelope text-slate-500 pt-1"></i>
        </div>
        <div class="flex justify-end pt-6 pb-4">
            <button type="submit" class="border border-transparent bg-red-400 text-white font-semibold p-1 hover:bg-white hover:text-red-400 duration-300 hover:border-red-400">REQUEST ACCESS</button>
        </div>
    </form>
</template>