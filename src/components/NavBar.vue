<template>
<header class="m-auto pt-8 items-center justify-center space-between gap-200 flex w-full">
    <div>
        <img src="../assets/Logo.png" alt="Logo" class=" w-1/5">
    </div>
    <nav class="flex gap-8 items-center">
        <ul className="flex gap-8">
            <li><a href="/" className="font-['DM-Sans'] font-medium text-[16px] leading-5 text-center text-white no-underline hover:text-[#328bcb]">Home</a></li>
            <li>
                <a href="#" className="font-['DM-Sans'] font-medium text-[16px] leading-5 text-center text-white no-underline hover:text-[#328bcb]">
                    Landings
                    <select name="landings" id="landings" className="bg-none border-none text-white hover:text-[#3c81b3]">
                    </select>
                </a>
            </li>
            <li><a href="#" className="font-['DM-Sans'] font-medium text-[16px] leading-5 text-center text-white no-underline hover:text-[#328bcb]">Pages</a></li>
            <li><a href="#" className="font-['DM-Sans'] font-medium text-[16px] leading-5 text-center text-white no-underline hover:text-[#328bcb]">Docs</a></li>
            <li><a href="#" className="font-['DM-Sans'] font-medium text-[16px] leading-5 text-center text-white no-underline hover:text-[#328bcb]">Help</a></li>
        </ul>
        <Button className="bg-linear-to-r from-[#005490] to-[#328bcb] text-white border-none px-6 py-2 cursor-pointer hover:text-[#328bcb]">Login</Button>
    </nav>
</header>
</template>

<script setup>
   import { ref } from 'vue';
</script>

<style scoped>
    nav Button:hover {
        background: white;
    }
</style>