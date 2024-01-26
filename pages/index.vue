<!-- <template>
    <div class="bg-gray-700 h-screen">
        <div class=" mx-auto max-w-lg h-screen bg-blue-950">
            <img src="https://sjhygr-5198-ppp.s3.sa-east-1.amazonaws.com/siteadmin/upload/img/1709107893685719042.png" />
            <img src="https://sjhygr-5198-ppp.s3.sa-east-1.amazonaws.com/siteadmin/upload/img/1708812659034382338.png" />
            <img src="https://sjhygr-5198-ppp.s3.sa-east-1.amazonaws.com/siteadmin/upload/img/1708812725187829762.png" />
        </div>
    </div>
</template> -->

<!-- <template>
    <div class="bg-gray-600 h-screen flex flex-col">
        <div class="max-w-lg mx-auto">
            <img src="https://sjhygr-5198-ppp.s3.sa-east-1.amazonaws.com/siteadmin/upload/img/1709107893685719042.png"
                class="bg-blue-950 " />
        </div>
        <div class="flex-1 overflow-y-auto max-w-lg mx-auto scrollbar-style">
            <div class="pt-4 bg-blue-950"></div>
            <img src="https://sjhygr-5198-ppp.s3.sa-east-1.amazonaws.com/siteadmin/upload/img/1708812659034382338.png" />
            <img src="https://sjhygr-5198-ppp.s3.sa-east-1.amazonaws.com/siteadmin/upload/img/1708812725187829762.png" />
            <img src="https://sjhygr-5198-ppp.s3.sa-east-1.amazonaws.com/siteadmin/upload/img/1708812862310969346.png" />

            <div class="fixed top-0 left-0 bg-white p-4 shadow-md">
           
                <p>This is a fixed div.</p>
            </div>
        </div>
    </div>
</template> -->

<script setup>
import { onMounted } from 'vue'
import {
    initAccordions,
    initCarousels,
    initCollapses,
    initDials,
    initDismisses,
    initDrawers,
    initDropdowns,
    initModals,
    initPopovers,
    initTabs,
    initTooltips
} from 'flowbite'

// initialize components based on data attribute selectors
onMounted(() => {
    initAccordions();
    initCarousels();
    initCollapses();
    initDials();
    initDismisses();
    initDrawers();
    initDropdowns();
    initModals();
    initPopovers();
    initTabs();
    initTooltips();
})
</script>
<template>
    <div class="bg-gray-600 h-screen flex flex-col">
        <div class="max-w-lg mx-auto relative">
            <img src="https://sjhygr-5198-ppp.s3.sa-east-1.amazonaws.com/siteadmin/upload/img/1709107893685719042.png"
                class="bg-blue-950" />



        </div>
        <div class="flex-1 overflow-y-auto max-w-lg mx-auto scrollbar-style">
            <div class="pt-4 bg-blue-950"></div>
            <!-- Your scrollable content here -->
            <img src="https://sjhygr-5198-ppp.s3.sa-east-1.amazonaws.com/siteadmin/upload/img/1708812659034382338.png" />
            <img src="https://sjhygr-5198-ppp.s3.sa-east-1.amazonaws.com/siteadmin/upload/img/1708812725187829762.png" />
            <img src="https://sjhygr-5198-ppp.s3.sa-east-1.amazonaws.com/siteadmin/upload/img/1708812862310969346.png" />

            <div class="fixed bottom-0 bg-black py-6 px-8 shadow-md space-x-6" style="background-color: rgba(0, 0, 0, 0.712);">
                <button
                    class="relative inline-flex items-center justify-center  p-0.5 mb-2 me-2 overflow-hidden text-sm font-medium text-gray-900 rounded-xl group bg-gradient-to-br from-cyan-500 to-blue-500 group-hover:from-cyan-500 group-hover:to-blue-500 hover:text-white dark:text-white focus:ring-4 focus:outline-none focus:ring-cyan-200 dark:focus:ring-cyan-800">
                    <span
                        class="relative px-12 py-3 transition-all ease-in duration-75 bg-blue-600 dark:bg-gray-900 rounded-md group-hover:bg-opacity-0 text-neutral-50 font-semibold text-lg">
                        Jogue Agora
                    </span>
                </button>

                <button
                    class="relative inline-flex items-center justify-center p-0.5 mb-2 me-2 overflow-hidden text-sm font-medium text-gray-900 rounded-xl group bg-gradient-to-br from-red-200 via-red-300 to-yellow-200 group-hover:from-red-200 group-hover:via-red-300 group-hover:to-yellow-200 dark:text-white dark:hover:text-gray-900 focus:ring-4 focus:outline-none focus:ring-red-100 dark:focus:ring-red-400">
                    <span
                        class="relative px-12 py-3 transition-all ease-in duration-75 bg-yellow-400 dark:bg-gray-900 rounded-md group-hover:bg-opacity-0 text-neutral-50 font-semibold text-lg">
                        Red to Yellow
                    </span>
                </button>   
            </div>


        </div>
    </div>
</template>

<style>
.scrollbar-style::-webkit-scrollbar {
    width: 6px;
    /* Adjust the width of the scrollbar */
}

.scrollbar-style::-webkit-scrollbar-thumb {
    background-color: #1a365d;
    /* Match the color of bg-blue-950 */
    border-radius: 3px;
    /* Rounded corners for the thumb */
}

.scrollbar-style::-webkit-scrollbar-track {
    background-color: #2d3748;
    /* Color of the track */
}
</style>


