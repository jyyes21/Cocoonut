<template>
    <div class="flex flex-col md:flex-row bg-green-50 px-5">
        <div class="md:w-1/2 w-full flex items-center justify-center">
            <div class="md:max-w-[400px] max-w-full mx-auto space-y-10 py-28">
                <h1 class="font-[600] text-[25px] w-full flex md:justify-start justify-center">NEWSLETTER</h1>
                <p class="text-[18px] text-stone-500 w-full flex justify-center md:text-start text-center">Abonnez vous à nos newsletter afin de restez informer de toutes nos nouveautés et profiter de bons plans</p>
            </div>
        </div>
        <div class="md:w-1/2 w-full flex items-center justify-center mb-16 md:mb-0">
            <div class="mb-2 flex items-center w-full justify-center space-x-4">
                        <input
                        type="email"
                        name="email"
                        id="email"
                        placeholder="Email"
                        class="placeholder-stone-800/50 flex py-3 px-3 w-full md:max-w-[20vw] max-w-[40vw] rounded-md bg-white border-2 border-stone-200 text-base font-medium text-stone-600 outline-none"
                        />
                        <div class="">
                        <button
                        class="placeholder-stone-800/50 rounded-md duration-300 bg-gray-700 hover:bg-gray-800 py-3 px-8 text-base font-semibold text-white outline-none flex mx-auto"
                        >
                        Souscrire
                        </button>
                    </div>
                    </div>
        </div>
    </div>
</template>