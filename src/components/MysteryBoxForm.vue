<template>
    <div class="flex flex-col border border-[#DBDBDB] w-[687px] gap-5 p-6 rounded-[20px]">
        <p class="text-center text-[#2D473E] font-medium text-3xl mb-2">Enter details</p>

        <div class="flex flex-row justify-between gap-3">
            <input
                type="text"
                name="firstname"
                id="firstname"
                class="w-1/2 block w-full rounded-md border-0 py-2 pl-3 pr-1.5 text-gray-900 ring-1 ring-inset ring-gray-400 placeholder:text-gray-400 focus:ring-1 focus:ring-inset focus:ring-[#2D473E] focus:outline-none sm:text-base sm:leading-6"
                placeholder="First name"
            />
            <input
                type="text"
                name="lastname"
                id="lastname"
                class="w-1/2 block w-full rounded-md border-0 py-2 pl-3 pr-1.5 text-gray-900 ring-1 ring-inset ring-gray-400 placeholder:text-gray-400 focus:ring-1 focus:ring-inset focus:ring-[#2D473E] focus:outline-none sm:text-base sm:leading-6"
                placeholder="Last name"
            />
        </div>
        <input
            type="text"
            name="street"
            id="street"
            class="block w-full rounded-md border-0 py-2 pl-3 pr-1.5 text-gray-900 ring-1 ring-inset ring-gray-400 placeholder:text-gray-400 focus:ring-1 focus:ring-inset focus:ring-[#2D473E] focus:outline-none sm:text-base sm:leading-6"
            placeholder="Street"
        />
        <div class="flex flex-row justify-between gap-3">
            <input
                type="text"
                name="postal_code"
                id="postal_code"
                class="w-1/2 block w-full rounded-md border-0 py-2 pl-3 pr-1.5 text-gray-900 ring-1 ring-inset ring-gray-400 placeholder:text-gray-400 focus:ring-1 focus:ring-inset focus:ring-[#2D473E] focus:outline-none sm:text-base sm:leading-6"
                placeholder="Postal code"
            />
            <input
                type="text"
                name="city"
                id="city"
                class="w-1/2 block w-full rounded-md border-0 py-2 pl-3 pr-1.5 text-gray-900 ring-1 ring-inset ring-gray-400 placeholder:text-gray-400 focus:ring-1 focus:ring-inset focus:ring-[#2D473E] focus:outline-none sm:text-base sm:leading-6"
                placeholder="City"
            />
        </div>
        <input
            type="text"
            name="phone_number"
            id="phone_number"
            class="block block w-full rounded-md border-0 py-2 pl-3 pr-1.5 text-gray-900 ring-1 ring-inset ring-gray-400 placeholder:text-gray-400 focus:ring-1 focus:ring-inset focus:ring-[#2D473E] focus:outline-none sm:text-base sm:leading-6"
            placeholder="Phone number"
        />
        <input
            type="text"
            name="email"
            id="email"
            class="block block w-full rounded-md border-0 py-2 pl-3 pr-1.5 text-gray-900 ring-1 ring-inset ring-gray-400 placeholder:text-gray-400 focus:ring-1 focus:ring-inset focus:ring-[#2D473E] focus:outline-none sm:text-base sm:leading-6"
            placeholder="E-mail"
        />

        <button class="my-3 py-3 px-4 font-semibold text-base text-white bg-[#006340] rounded-lg">
            PROCEED TO PAYMENT
        </button>

        <div class="flex flex-row justify-center gap-4">
            <img src="../assets/images/form/mcafee.png" class="w-[93px] h-[40px]" />
            <img src="../assets/images/form/truste.png" class="w-[93px] h-[40px]" />
            <img src="../assets/images/form/ssl.png" class="w-[93px] h-[40px]" />
        </div>
    </div>
</template>
