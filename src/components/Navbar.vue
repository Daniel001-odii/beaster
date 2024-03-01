<template>
    <div>
        <div class="flex flex-col md:flex-row gap-5 justify-between p-5 bg-slate-100 md:items-center">
            <div class="flex flex-row w-full md:w-fit justify-between items-center">
                <span class="flex flex-row items-center">
                    <img src="../assets/images/logo.png" class=" h-10">
                    <span class="font-bold  text-xl">Beaster</span>
                </span>
                <button @click="nav_visible = !nav_visible" class=" md:hidden text-2xl">
                    <i class="bi bi-list-nested"></i>
                </button>
            </div>
            <div :class="nav_visible ? 'flex':'hidden'" class="transition ease-in delay-1000 duration-1000 md:flex flex-col md:flex-row gap-8 font-bold text-slate-700 ">
                <RouterLink to="#">About</RouterLink>
                <RouterLink to="#">Marketplaces</RouterLink>
                <RouterLink to="#">Catalog Management</RouterLink>
                <RouterLink to="#">Product Content</RouterLink>
                <RouterLink to="#">Contact</RouterLink>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Navbar",
        data(){
            return{
                nav_visible: false,
            }
        }
    }
</script>

<style scoped>

</style>