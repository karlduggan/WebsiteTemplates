<template>
    <div class="py-[44px] flex inline relative">
        <div class="left-0">
            <h1 class="absolute left-0 text-3xl">Name</h1>
        </div>
        <div>
            <ul class="flex inline gap-6 text-xl font-bold absolute right-0 ">
                <li>Home</li>
                <li>About</li>
                <li>Contact</li>
                <li>Elements</li>
                <li><LightDarkModeComponent/></li>
                <li>
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-search"><circle cx="11" cy="11" r="8"></circle><line x1="21" y1="21" x2="16.65" y2="16.65"></line></svg>
                </li>
            </ul>
        </div>
    </div>
</template>

<script>
import LightDarkModeComponent from './LightDarkModeComponent.vue';
export default {
    components: {
        LightDarkModeComponent
    }
}
</script>


