<template>
    <div class="bg-white w-full lg:h-auto h-[16vh]">
    <div class="flex justify-center h-full w-5/6 mx-auto">
        <div class="flex flex-col-reverse md:flex-row w-full justify-around items-center">
        <div class="w-1/3 flex justify-center">
            <ul class="flex space-x-10 items-center">
                <li><button class="hover:text-[#ba9453] duration-300 ">ACCEUIL</button></li>
                <li><button class="hover:text-[#ba9453] duration-300 ">SHOP</button></li>
                <li><button class="hover:text-[#ba9453] duration-300 ">INSPIRATIONS</button></li>
            </ul>
        </div>
        <div class="w-1/3 hidden justify-center lg:flex">
            <a href="/">
                <img src="https://cdn.discordapp.com/attachments/1130776962495950940/1154413114809384970/1-removebg-preview_1.png" alt="">
            </a>
        </div>
        <div class="w-1/3 flex justify-center">
            <div class="mx-8 hover:rotate-[10deg] hover:scale-[1.03] ease-in-out duration-300">
                <box-icon name='search-alt'></box-icon>
            </div>
            <ul class="flex space-x-3">
                <li><box-icon class="hover:scale-[1.05] duration-300" name='user-circle'></box-icon></li>
                <li><box-icon class="hover:scale-[1.05] duration-300" name='heart' type='solid' ></box-icon></li>
                <li><box-icon class="hover:scale-[1.05] duration-300" name='basket'></box-icon></li>
            </ul>
        </div>
    </div>
    </div>
</div>
</template>