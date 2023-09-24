<template>
    <div class="w-full bg-stone-200 flex flex-col lg:flex-row">
        <div class="lg:w-8/12 w-full h-[750px] flex items-end bg-[url('https://cdn.discordapp.com/attachments/1130776962495950940/1154972553870331904/Rectangle_169.png')] bg-cover bg-no-repeat bg-center">
            <div class="mx-auto mb-14">
                <div class="bg-stone-100/80 flex py-6 sm:px-24 px-10 overflow-hidden justify-center">
                    <ul class=" flex flex-col space-y-4">
                    <li class="flex space-x-3 items-center">
                        <svg width="16" height="20" viewBox="0 0 16 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M7.99999 0C3.58899 0 -1.01081e-05 3.589 -1.01081e-05 7.995C-0.0290101 14.44 7.69599 19.784 7.99999 20C7.99999 20 16.029 14.44 16 8C16 3.589 12.411 0 7.99999 0ZM7.99999 12C5.78999 12 3.99999 10.21 3.99999 8C3.99999 5.79 5.78999 4 7.99999 4C10.21 4 12 5.79 12 8C12 10.21 10.21 12 7.99999 12Z" fill="#D1B39F"/>
                        </svg>
                        <p class="sm:text-[20px] text-[15px]">19 Rue Yves Toudic, 75010 Paris</p>
                    </li>
                    <li class="flex space-x-3 items-center">
                        <svg width="18" height="18" viewBox="0 0 18 18" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M2.9457 17.0266L0.659766 14.7385C0.497652 14.5771 0.369026 14.3852 0.281276 14.174C0.193527 13.9627 0.148383 13.7362 0.148438 13.5074C0.148438 13.0412 0.331055 12.6029 0.659766 12.2742L3.12187 9.81211C3.28328 9.65 3.47512 9.52137 3.68639 9.43362C3.89765 9.34587 4.12417 9.30073 4.35293 9.30078C4.81914 9.30078 5.25742 9.4834 5.58613 9.81211L7.38652 11.6125C8.31542 11.1911 9.16046 10.6051 9.88086 9.88301C10.6048 9.16268 11.1928 8.31772 11.6168 7.38867L9.81641 5.58828C9.65429 5.42688 9.52567 5.23503 9.43792 5.02377C9.35017 4.81251 9.30502 4.58599 9.30508 4.35723C9.30508 3.89102 9.4877 3.45274 9.81641 3.12402L12.2764 0.659767C12.4381 0.497454 12.6303 0.368718 12.8419 0.280964C13.0536 0.19321 13.2805 0.148171 13.5096 0.148439C13.9758 0.148439 14.4141 0.331056 14.7428 0.659767L17.0266 2.94356C17.5529 3.46777 17.8516 4.1918 17.8516 4.93516C17.8516 5.09199 17.8387 5.24238 17.8129 5.39063C17.3359 8.28672 15.7955 11.1592 13.4795 13.4773C11.1656 15.7934 8.29531 17.3316 5.39063 17.815C4.50332 17.9611 3.59023 17.6668 2.9457 17.0266Z" fill="#D1B39F"/>
                        </svg>
                        <p class="sm:text-[20px] text-[15px]">01 23 45 67 89</p>
                    </li>
                    <li class="flex space-x-3 items-center">
                        <svg width="22" height="22" viewBox="0 0 22 22" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M19.9375 3.4375H2.0625C1.68223 3.4375 1.375 3.74473 1.375 4.125V17.875C1.375 18.2553 1.68223 18.5625 2.0625 18.5625H19.9375C20.3178 18.5625 20.625 18.2553 20.625 17.875V4.125C20.625 3.74473 20.3178 3.4375 19.9375 3.4375ZM18.2016 5.77715L11.4232 11.0516C11.2557 11.1826 11.0215 11.1826 10.8539 11.0516L4.07344 5.77715C4.04788 5.75742 4.02913 5.73019 4.01982 5.69928C4.01052 5.66836 4.01112 5.63531 4.02154 5.60475C4.03196 5.57419 4.05169 5.54766 4.07794 5.52888C4.1042 5.51009 4.13568 5.49999 4.16797 5.5H18.107C18.1393 5.49999 18.1708 5.51009 18.1971 5.52888C18.2233 5.54766 18.243 5.57419 18.2535 5.60475C18.2639 5.63531 18.2645 5.66836 18.2552 5.69928C18.2459 5.73019 18.2271 5.75742 18.2016 5.77715Z" fill="#D1B39F"/>
                        </svg>
                        <p class="sm:text-[20px] text-[15px]">edjour.marielaure@gmail.com</p>
                    </li>
                    </ul>
                </div>
            </div>
        </div>
        <div class="md:w-6/12 w-full h-full mx-auto lg:px-5 px-5">
            <div>
                <span class="text-[35px] w-full flex justify-center font-[600] py-18">CONTACTEZ-NOUS</span>
            </div>
            <div class="flex items-center justify-center">

                <div class="mx-auto w-full max-w-[550px]">
                    <form>
                    <div class="mb-5 flex justify-between space-x-10">
                        <div class="w-full">
                        <input
                        type="text"
                        name="nom"
                        id="nom"
                        placeholder="Nom"
                        class="placeholder-stone-800/50 w-full rounded-md shadow-inner bg-stone-200 pt-3 px-6 text-base font-medium text-stone-600 outline-none"
                        />
                        <hr class="mb-5 mt-2 bg-black w-full h-1 rounded-full">
                        </div>
                        
                        <div class="w-full">
                        <input
                        type="text"
                        name="prenom"
                        id="prenom"
                        placeholder="Prénom"
                        class="placeholder-stone-800/50 w-full rounded-md shadow-inner bg-stone-200 pt-3 px-6 text-base font-medium text-stone-600 outline-none"
                        />
                        <hr class="mb-5 mt-2 bg-black w-full h-1 rounded-full">
                        </div>
                    </div>
                    <div class="mb-2">
                        <input
                        type="phone"
                        name="phone"
                        id="phone"
                        placeholder="Téléphone"
                        class="placeholder-stone-800/50 w-full rounded-md shadow-inner bg-stone-200 pt-3 px-6 text-base font-medium text-stone-600 outline-none"
                        />
                    </div>
                    <hr class="mb-5 bg-black w-full h-1 rounded-full">
                    <div class="mb-2">
                        <input
                        type="email"
                        name="email"
                        id="email"
                        placeholder="E-mail"
                        class="placeholder-stone-800/50 w-full rounded-md shadow-inner bg-stone-200 pt-3 px-6 text-base font-medium text-stone-600 outline-none"
                        />
                    </div>
                    <hr class="mb-5 bg-black w-full h-1 rounded-full">
                    <div class="mb-2">
                        <input
                        type="text"
                        name="subject"
                        id="subject"
                        placeholder="Sujet"
                        class="placeholder-stone-800/50 w-full rounded-md shadow-inner bg-stone-200 pt-3 px-6 text-base font-medium text-stone-600 outline-none"
                        />
                    </div>
                    <hr class="mb-5 bg-black w-full h-1 rounded-full">
                    <div class="mb-2">
                        <textarea
                        rows="4"
                        name="message"
                        id="message"
                        placeholder="Message"
                        class="placeholder-stone-800/50 w-full resize-none rounded-md shadow-inner bg-stone-200 pt-3 px-6 text-base font-medium text-stone-600 outline-none"
                        ></textarea>
                    </div>
                    <hr class="mb-10 bg-black w-full h-1 rounded-full">
                    <div>
                        <button
                        class="placeholder-stone-800/50 rounded-md duration-300 bg-orange-600/60 hover:bg-orange-700/60 py-3 px-8 text-base font-semibold text-white outline-none flex mb-10 mx-auto"
                        >
                        S'inscrire
                        </button>
                    </div>
                    </form>
                </div>
                </div>
        </div>
    </div>
</template>