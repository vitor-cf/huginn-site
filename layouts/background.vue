<template>
    <div class="back bg-[#02071B] h-[100vh] w-full">
        <header class="flex justify-center p-6">
            <div class="flex justify-between items-center w-[98%]">
                <div>
                    <h1 class="text-[32px] text-white"><strong class="text-[#848EBD]">ATLÉTICA</strong> HUGINN</h1>
                </div>
                <div>
                    <ul class="flex space-x-5">
                        <li class="text-[24px] text-white">LOJA</li>
                        <li class="text-[24px] text-white">PROSEL</li>
                        <li class="text-[24px] text-white">EVENTOS</li>
                        <li class="text-[24px] text-white">DIRETORIA</li>
                        <li class="text-[24px] text-white">MODALIDADES</li>
                    </ul>
                </div>
            </div>
        </header>
            <slot/>

    </div>
</template>
<style scoped>
.back {
    background-image:url('assets/imgs/logo.svg') ;
    background-size: 100%;
    background-repeat: no-repeat;
}
</style>