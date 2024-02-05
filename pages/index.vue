<script setup>
import { ref, onMounted, watch } from 'vue'
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

const isModalOpen = ref(false);

const gnumb = ref(500);
const generateRandomNumber = () => {
    setTimeout(() => {
        const randomNumber = Math.floor(Math.random() * (560 - 130 + 1) + 130);
        gnumb.value = randomNumber
    }, 10000);
};

const Jogue_Agora = () => {
    console.log('Jogue_Agora', isModalOpen.value);
    isModalOpen.value = !isModalOpen.value;
    const modal = document.getElementById('small-modal');
    modal.classList.toggle('hidden');
}
const Jogue_Agora1 = () => {
    console.log('Jogue_Agora1');
    window.open('https://www.iwc7777.com', '_blank');
}
const Jogue_Agora2 = () => {
    console.log('Jogue_Agora2');
    window.open('https://www.iwc777.me', '_blank');
}
const Jogue_Agora3 = () => {
    console.log('Jogue_Agora3');
    window.open('https://iwc777.co', '_blank');
}
const Jogue_Agora4 = () => {
    console.log('Jogue_Agora4');
    window.open('https://iwc777.me', '_blank');
}
const Jogue_Agora5 = () => {
    console.log('Jogue_Agora5');
    window.open('https://iwc777.com', '_blank');
}
const Jogue_Agora6 = () => {
    console.log('Jogue_Agora6');
    window.open('https://www.iwc7777.com', '_blank');
}
// const Suporte = () => {
//     console.log('Suporte');
// }
const Baixe_Agora = () => {
    console.log('Baixe_Agora');
}
const Atualizar = () => {
    const randomNumber = Math.floor(Math.random() * (560 - 130 + 1) + 130);
    gnumb.value =randomNumber
}

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
    generateRandomNumber();
})
watch(gnumb, () => {
    generateRandomNumber();
});
</script>

<template>
    <div class="bg-gray-600 h-screen flex flex-col" :class="{ 'overflow-y-hidden': isModalOpen }">
        <div class="max-w-lg mx-auto relative">
            <img src="https://sjhygr-5198-ppp.s3.sa-east-1.amazonaws.com/siteadmin/upload/img/1709107893685719042.png"
                class="bg-blue-950" />
        </div>
        <div
            :class="{ 'flex-1 overflow-y-auto max-w-lg mx-auto scrollbar-style relative': !isModalOpen, 'flex-1 overflow-y-auto max-w-lg mx-auto scrollbar-style relative ': isModalOpen }">
            <div class="pt-4 bg-blue-950"></div>
            <div :class="{ 'opacity-60': isModalOpen, 'z-40': isModalOpen }">
                <div class="fixed top-1/5 mt-2 ml-8 pt-12 pl-96  flex items-center justify-center">
                    <div class="p-3 border-2 border-blue-700 rounded-3xl"
                        style="background-color: rgba(255, 255, 255, 0.60);">
                       <a href="https://psowoexvd.dqo7x1brkiq.com/chatwindow.aspx?siteId=65001438&planId=3976e3fe-7177-48c5-869b-350b65d28289"> <button >
                            <div class="pl-1.5">
                                <svg xmlns="http://www.w3.org/2000/svg" width="2em" height="2em" viewBox="0 0 256 256">
                                    <path fill="blue"
                                        d="M232 136v56a24 24 0 0 1-24 24h-16a24 24 0 0 1-24-24v-40a24 24 0 0 1 24-24h23.65a87.71 87.71 0 0 0-87-80H128a88 88 0 0 0-87.64 80H64a24 24 0 0 1 24 24v40a24 24 0 0 1-24 24H48a24 24 0 0 1-24-24v-56a104.11 104.11 0 0 1 177.89-73.34A103.41 103.41 0 0 1 232 136" />
                                </svg>
                            </div>
                            <p class="font-medium text-blue-700 text-sm">Suporte</p>
                        </button></a>
                    </div>
                </div>
                <img
                    src="https://sjhygr-5198-ppp.s3.sa-east-1.amazonaws.com/siteadmin/upload/img/1708812659034382338.png" />
                <img
                    src="https://sjhygr-5198-ppp.s3.sa-east-1.amazonaws.com/siteadmin/upload/img/1708812725187829762.png" />
                <img
                    src="https://sjhygr-5198-ppp.s3.sa-east-1.amazonaws.com/siteadmin/upload/img/1708812862310969346.png" />
                <div class="fixed bottom-0 bg-black py-6 px-6 shadow-md flex space-x-8 sm:space-x-11 md:space-x-11 lg:space-x-11"
                    style="background-color: rgba(0, 0, 0, 0.700);">
                    <button @click="Jogue_Agora" :disabled="isModalOpen"
                        class="flex-grow relative inline-flex items-center justify-center p-0.5 overflow-hidden text-sm font-medium text-gray-900 rounded-lg">
                        <span
                            class="relative px-12 py-3 transition-all ease-in duration-75 bg-blue-600 dark:bg-gray-900 rounded-md text-neutral-50 font-normal text-xl">
                            Jogue Agora
                        </span>
                    </button>
                    <button @click="Baixe_Agora" :disabled="isModalOpen"
                        class="flex-grow relative inline-flex items-center justify-center p-0.5 overflow-hidden text-sm font-medium text-gray-900 rounded-xl group">
                        <span
                            class="relative px-12 py-3 transition-all ease-in duration-75 bg-yellow-400 dark:bg-gray-900 rounded-md text-neutral-50 font-normal text-xl">
                            Baixe Agora
                        </span>
                    </button>
                </div>
            </div>
        </div>
        <div class="fixed top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 z-50">
            <div id="small-modal" tabindex="-1"
                class=" z-50 hidden  overflow-x-hidden overflow-y-auto md:inset-0 h-[calc(100%-1rem)] max-h-full ">
                <div class=" mt-20 pb-2 flex justify-end">
                    <button @click="Atualizar">
                        <div class="px-6 py-1.5 text-white font-medium text-lg bg-blue-600 rounded-xl">
                            Atualizar
                        </div>
                    </button>
                </div>
                <div>
                    <div class="relative bg-white rounded-xl shadow dark:bg-gray-700 border border-white px-2.5 py-6"
                        style="background-color: rgba(0, 0, 0, 0.450);">
                        <div class=" flex items-center pb-1">
                            <div class="pl-5 pr-3">
                                <div v-if="gnumb + 50 <= 199" class="px-1 py-1">
                                    <svg xmlns="http://www.w3.org/2000/svg" width="3em" height="3em" viewBox="0 0 24 24">
                                        <path fill="red"
                                            d="M6.5 20q-.625 0-1.062-.437T5 18.5v-3q0-.625.438-1.062T6.5 14q.625 0 1.063.438T8 15.5v3q0 .625-.437 1.063T6.5 20" />
                                    </svg>
                                </div>
                                <div v-if="gnumb + 50 >= 200 && gnumb + 50 <= 399" class="px-1 py-1">
                                    <svg xmlns="http://www.w3.org/2000/svg" width="3em" height="3em" viewBox="0 0 24 24">
                                        <path fill="yellow"
                                            d="M6.5 20q-.625 0-1.062-.437T5 18.5v-3q0-.625.438-1.062T6.5 14q.625 0 1.063.438T8 15.5v3q0 .625-.437 1.063T6.5 20m6 0q-.625 0-1.062-.437T11 18.5v-8q0-.625.438-1.062T12.5 9q.625 0 1.063.438T14 10.5v8q0 .625-.437 1.063T12.5 20" />
                                    </svg>
                                </div>
                                <div v-if="gnumb + 50 >= 400">
                                    <svg class="custom-svg" xmlns="http://www.w3.org/2000/svg" width="3.5em" height="3.5em"
                                        viewBox="0 0 21 21">
                                        <path class="fill-green" fill-rule="evenodd" stroke="stroke-lightgreen"
                                            stroke-linecap="round" stroke-linejoin="round"
                                            d="M5.5 16.5v-3a1 1 0 1 1 2 0v3a1 1 0 0 1-2 0m4 0v-6a1 1 0 1 1 2 0v6a1 1 0 0 1-2 0m4 0v-9a1 1 0 1 1 2 0v9a1 1 0 0 1-2 0" />
                                    </svg>
                                </div>
                            </div>
                            <div class="font-normal text-white text-xl pr-3">Online1 </div>
                            <div :class="{
                                'px-1 py-1': gnumb + 50 <= 199,
                                'text-red-400': gnumb + 50 <= 199,
                                'text-yellow-200': gnumb + 50 >= 200 && gnumb + 50 <= 399,
                                'custom-text-color': gnumb + 50 >= 400
                            }" class="font-normal text-xl pr-2">{{ gnumb + 50 }}MS</div>
                            <div class="px-4">
                                <button @click="Jogue_Agora1">
                                    <div class="px-6 py-1.5 text-white font-medium text-lg bg-blue-600 rounded-xl">
                                        Jogue Agora
                                    </div>
                                </button>
                            </div>
                        </div>
                        <div class=" flex items-center pb-1">
                            <div class="pl-5 pr-3">
                                <div v-if="gnumb - 20 <= 199" class="px-1 py-1">
                                    <svg xmlns="http://www.w3.org/2000/svg" width="3em" height="3em" viewBox="0 0 24 24">
                                        <path fill="red"
                                            d="M6.5 20q-.625 0-1.062-.437T5 18.5v-3q0-.625.438-1.062T6.5 14q.625 0 1.063.438T8 15.5v3q0 .625-.437 1.063T6.5 20" />
                                    </svg>
                                </div>
                                <div v-if="gnumb - 20 >= 200 && gnumb - 20 <= 399" class="px-1 py-1">
                                    <svg xmlns="http://www.w3.org/2000/svg" width="3em" height="3em" viewBox="0 0 24 24">
                                        <path fill="yellow"
                                            d="M6.5 20q-.625 0-1.062-.437T5 18.5v-3q0-.625.438-1.062T6.5 14q.625 0 1.063.438T8 15.5v3q0 .625-.437 1.063T6.5 20m6 0q-.625 0-1.062-.437T11 18.5v-8q0-.625.438-1.062T12.5 9q.625 0 1.063.438T14 10.5v8q0 .625-.437 1.063T12.5 20" />
                                    </svg>
                                </div>
                                <div v-if="gnumb - 20 >= 400">
                                    <svg class="custom-svg" xmlns="http://www.w3.org/2000/svg" width="3.5em" height="3.5em"
                                        viewBox="0 0 21 21">
                                        <path class="fill-green" fill-rule="evenodd" stroke="stroke-lightgreen"
                                            stroke-linecap="round" stroke-linejoin="round"
                                            d="M5.5 16.5v-3a1 1 0 1 1 2 0v3a1 1 0 0 1-2 0m4 0v-6a1 1 0 1 1 2 0v6a1 1 0 0 1-2 0m4 0v-9a1 1 0 1 1 2 0v9a1 1 0 0 1-2 0" />
                                    </svg>
                                </div>
                            </div>
                            <div class="font-normal text-white text-xl pr-3">Online2</div>
                            <div :class="{
                                'px-1 py-1': gnumb - 20 <= 199,
                                'text-red-400': gnumb - 20 <= 199,
                                'text-yellow-200': gnumb - 20 >= 200 && gnumb - 20 <= 399,
                                'custom-text-color': gnumb - 20 >= 400
                            }" class="font-normal text-xl pr-2">{{ gnumb - 20 }}MS</div>
                            <div class="px-4">
                                <button @click="Jogue_Agora2">
                                    <div class="px-6 py-1.5 text-white font-medium text-lg bg-blue-600 rounded-xl">
                                        Jogue Agora
                                    </div>
                                </button>
                            </div>
                        </div>
                        <div class=" flex items-center pb-1">
                            <div class="pl-5 pr-3">
                                <div v-if="gnumb + 40 <= 199" class="px-1 py-1">
                                    <svg xmlns="http://www.w3.org/2000/svg" width="3em" height="3em" viewBox="0 0 24 24">
                                        <path fill="red"
                                            d="M6.5 20q-.625 0-1.062-.437T5 18.5v-3q0-.625.438-1.062T6.5 14q.625 0 1.063.438T8 15.5v3q0 .625-.437 1.063T6.5 20" />
                                    </svg>
                                </div>
                                <div v-if="gnumb + 40 >= 200 && gnumb + 40 <= 399" class="px-1 py-1">
                                    <svg xmlns="http://www.w3.org/2000/svg" width="3em" height="3em" viewBox="0 0 24 24">
                                        <path fill="yellow"
                                            d="M6.5 20q-.625 0-1.062-.437T5 18.5v-3q0-.625.438-1.062T6.5 14q.625 0 1.063.438T8 15.5v3q0 .625-.437 1.063T6.5 20m6 0q-.625 0-1.062-.437T11 18.5v-8q0-.625.438-1.062T12.5 9q.625 0 1.063.438T14 10.5v8q0 .625-.437 1.063T12.5 20" />
                                    </svg>
                                </div>
                                <div v-if="gnumb + 40 >= 400">
                                    <svg class="custom-svg" xmlns="http://www.w3.org/2000/svg" width="3.5em" height="3.5em"
                                        viewBox="0 0 21 21">
                                        <path class="fill-green" fill-rule="evenodd" stroke="stroke-lightgreen"
                                            stroke-linecap="round" stroke-linejoin="round"
                                            d="M5.5 16.5v-3a1 1 0 1 1 2 0v3a1 1 0 0 1-2 0m4 0v-6a1 1 0 1 1 2 0v6a1 1 0 0 1-2 0m4 0v-9a1 1 0 1 1 2 0v9a1 1 0 0 1-2 0" />
                                    </svg>
                                </div>
                            </div>
                            <div class="font-normal text-white text-xl pr-3">Online3</div>
                            <div :class="{
                                'px-1 py-1': gnumb + 40 <= 199,
                                'text-red-400': gnumb + 40 <= 199,
                                'text-yellow-200': gnumb + 40 >= 200 && gnumb + 40 <= 399,
                                'custom-text-color': gnumb + 40 >= 400
                            }" class="font-normal text-xl pr-2">{{ gnumb + 40 }}MS</div>
                            <div class="px-4">
                                <button @click="Jogue_Agora3">
                                    <div class="px-6 py-1.5 text-white font-medium text-lg bg-blue-600 rounded-xl">
                                        Jogue Agora
                                    </div>
                                </button>
                            </div>
                        </div>
                        <div class=" flex items-center pb-1">
                            <div class="pl-5 pr-3">
                                <div v-if="gnumb - 30 <= 199" class="px-1 py-1">
                                    <svg xmlns="http://www.w3.org/2000/svg" width="3em" height="3em" viewBox="0 0 24 24">
                                        <path fill="red"
                                            d="M6.5 20q-.625 0-1.062-.437T5 18.5v-3q0-.625.438-1.062T6.5 14q.625 0 1.063.438T8 15.5v3q0 .625-.437 1.063T6.5 20" />
                                    </svg>
                                </div>
                                <div v-if="gnumb - 30 >= 200 && gnumb - 30 <= 399" class="px-1 py-1">
                                    <svg xmlns="http://www.w3.org/2000/svg" width="3em" height="3em" viewBox="0 0 24 24">
                                        <path fill="yellow"
                                            d="M6.5 20q-.625 0-1.062-.437T5 18.5v-3q0-.625.438-1.062T6.5 14q.625 0 1.063.438T8 15.5v3q0 .625-.437 1.063T6.5 20m6 0q-.625 0-1.062-.437T11 18.5v-8q0-.625.438-1.062T12.5 9q.625 0 1.063.438T14 10.5v8q0 .625-.437 1.063T12.5 20" />
                                    </svg>
                                </div>
                                <div v-if="gnumb - 30 >= 400">
                                    <svg class="custom-svg" xmlns="http://www.w3.org/2000/svg" width="3.5em" height="3.5em"
                                        viewBox="0 0 21 21">
                                        <path class="fill-green" fill-rule="evenodd" stroke="stroke-lightgreen"
                                            stroke-linecap="round" stroke-linejoin="round"
                                            d="M5.5 16.5v-3a1 1 0 1 1 2 0v3a1 1 0 0 1-2 0m4 0v-6a1 1 0 1 1 2 0v6a1 1 0 0 1-2 0m4 0v-9a1 1 0 1 1 2 0v9a1 1 0 0 1-2 0" />
                                    </svg>
                                </div>
                            </div>
                            <div class="font-normal text-white text-xl pr-3">Online4</div>
                            <div :class="{
                                'px-1 py-1': gnumb - 30 <= 199,
                                'text-red-400': gnumb - 30 <= 199,
                                'text-yellow-200': gnumb - 30 >= 200 && gnumb - 30 <= 399,
                                'custom-text-color': gnumb - 30 >= 400
                            }" class="font-normal text-xl pr-2">{{ gnumb - 30 }}MS</div>
                            <div class="px-4">
                                <button @click="Jogue_Agora4">
                                    <div class="px-6 py-1.5 text-white font-medium text-lg bg-blue-600 rounded-xl">
                                        Jogue Agora
                                    </div>
                                </button>
                            </div>
                        </div>
                        <div class=" flex items-center pb-1">
                            <div class="pl-5 pr-3">
                                <div v-if="gnumb + 100 <= 199" class="px-1 py-1">
                                    <svg xmlns="http://www.w3.org/2000/svg" width="3em" height="3em" viewBox="0 0 24 24">
                                        <path fill="red"
                                            d="M6.5 20q-.625 0-1.062-.437T5 18.5v-3q0-.625.438-1.062T6.5 14q.625 0 1.063.438T8 15.5v3q0 .625-.437 1.063T6.5 20" />
                                    </svg>
                                </div>
                                <div v-if="gnumb + 100 >= 200 && gnumb + 100 <= 399" class="px-1 py-1">
                                    <svg xmlns="http://www.w3.org/2000/svg" width="3em" height="3em" viewBox="0 0 24 24">
                                        <path fill="yellow"
                                            d="M6.5 20q-.625 0-1.062-.437T5 18.5v-3q0-.625.438-1.062T6.5 14q.625 0 1.063.438T8 15.5v3q0 .625-.437 1.063T6.5 20m6 0q-.625 0-1.062-.437T11 18.5v-8q0-.625.438-1.062T12.5 9q.625 0 1.063.438T14 10.5v8q0 .625-.437 1.063T12.5 20" />
                                    </svg>
                                </div>
                                <div v-if="gnumb + 100 >= 400">
                                    <svg class="custom-svg" xmlns="http://www.w3.org/2000/svg" width="3.5em" height="3.5em"
                                        viewBox="0 0 21 21">
                                        <path class="fill-green" fill-rule="evenodd" stroke="stroke-lightgreen"
                                            stroke-linecap="round" stroke-linejoin="round"
                                            d="M5.5 16.5v-3a1 1 0 1 1 2 0v3a1 1 0 0 1-2 0m4 0v-6a1 1 0 1 1 2 0v6a1 1 0 0 1-2 0m4 0v-9a1 1 0 1 1 2 0v9a1 1 0 0 1-2 0" />
                                    </svg>
                                </div>
                            </div>
                            <div class="font-normal text-white text-xl pr-3">Online5</div>
                            <div :class="{
                                'px-1 py-1': gnumb + 100 <= 199,
                                'text-red-400': gnumb + 100 <= 199,
                                'text-yellow-200': gnumb + 100 >= 200 && gnumb + 100 <= 399,
                                'custom-text-color': gnumb + 100 >= 400
                            }" class="font-normal text-xl pr-2">{{ gnumb + 100 }}MS</div>
                            <div class="px-4">
                                <button @click="Jogue_Agora5">
                                    <div class="px-6 py-1.5 text-white font-medium text-lg bg-blue-600 rounded-xl">
                                        Jogue Agora
                                    </div>
                                </button>
                            </div>
                        </div>
                        <div class=" flex items-center pb-1">
                            <div class="pl-5 pr-3">
                                <div v-if="gnumb + 77 <= 199" class="px-1 py-1">
                                    <svg xmlns="http://www.w3.org/2000/svg" width="3em" height="3em" viewBox="0 0 24 24">
                                        <path fill="red"
                                            d="M6.5 20q-.625 0-1.062-.437T5 18.5v-3q0-.625.438-1.062T6.5 14q.625 0 1.063.438T8 15.5v3q0 .625-.437 1.063T6.5 20" />
                                    </svg>
                                </div>
                                <div v-if="gnumb + 77 >= 200 && gnumb + 77 <= 399" class="px-1 py-1">
                                    <svg xmlns="http://www.w3.org/2000/svg" width="3em" height="3em" viewBox="0 0 24 24">
                                        <path fill="yellow"
                                            d="M6.5 20q-.625 0-1.062-.437T5 18.5v-3q0-.625.438-1.062T6.5 14q.625 0 1.063.438T8 15.5v3q0 .625-.437 1.063T6.5 20m6 0q-.625 0-1.062-.437T11 18.5v-8q0-.625.438-1.062T12.5 9q.625 0 1.063.438T14 10.5v8q0 .625-.437 1.063T12.5 20" />
                                    </svg>
                                </div>
                                <div v-if="gnumb + 77 >= 400">
                                    <svg class="custom-svg" xmlns="http://www.w3.org/2000/svg" width="3.5em" height="3.5em"
                                        viewBox="0 0 21 21">
                                        <path class="fill-green" fill-rule="evenodd" stroke="stroke-lightgreen"
                                            stroke-linecap="round" stroke-linejoin="round"
                                            d="M5.5 16.5v-3a1 1 0 1 1 2 0v3a1 1 0 0 1-2 0m4 0v-6a1 1 0 1 1 2 0v6a1 1 0 0 1-2 0m4 0v-9a1 1 0 1 1 2 0v9a1 1 0 0 1-2 0" />
                                    </svg>
                                </div>
                            </div>
                            <div class="font-normal text-white text-xl pr-3">Online6</div>
                            <div :class="{
                                'px-1 py-1': gnumb + 77 <= 199,
                                'text-red-400': gnumb + 77 <= 199,
                                'text-yellow-200': gnumb + 77 >= 200 && gnumb + 50 <= 399,
                                'custom-text-color': gnumb + 77 >= 400
                            }" class="font-normal text-xl pr-2">{{ gnumb + 77 }}MS</div>
                            <div class="px-4">
                                <button @click="Jogue_Agora6">
                                    <div class="px-6 py-1.5 text-white font-medium text-lg bg-blue-600 rounded-xl">
                                        Jogue Agora
                                    </div>
                                </button>
                            </div>
                        </div>
                    </div>
                    <div class="  flex mx-auto justify-center pt-8 rounded-full">
                        <div class="rounded-full pl-1 pr-1 pt-1 border-4 border-white">
                            <button class="rounded-full " @click="Jogue_Agora">
                                <span> <svg xmlns="http://www.w3.org/2000/svg" width="2.5em" height="2.5em"
                                        viewBox="0 0 16 16">
                                        <path fill="none" stroke="white" stroke-linecap="round" stroke-linejoin="round"
                                            stroke-width="1.5" d="m11.25 4.75l-6.5 6.5m0-6.5l6.5 6.5" />
                                    </svg>
                                </span>
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<style>
.custom-text-color {
    color: rgb(4, 190, 2);
}

.custom-svg .fill-green {
    fill: rgb(4, 190, 2);
}

.custom-svg stroke-lightgreen {
    stroke: lightgreen;
}

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
}</style>