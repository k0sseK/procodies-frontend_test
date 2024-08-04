<script setup lang="ts">
import ProductCard from '../components/ProductCard.vue'
import MysteryBoxForm from '../components/MysteryBoxForm.vue'
import Footer from '../components/Footer.vue'
</script>

<template>
    <div class="flex flex-row gap-4">
        <ProductCard />
        <div>
            <div class="space-y-3 mb-5">
                <p class="font-extrabold text-5xl text-[#293632] w-[687px]">
                    Chance to win a StockX Mystery Box today!
                </p>
                <p class="text-xl text-[#293632]">Unleash the Excitement Of Mystery Electronics</p>
            </div>
            <MysteryBoxForm />
        </div>
    </div>

    <div class="mt-10 mb-6 text-center w-full">
        <p class="text-5xl text-[#2D473E] font-bold">
            Top Tech Mystery Box<br />
            at Unbeatable Prices
        </p>
        <p class="mt-2 text-xl text-[#006340] font-medium">
            Fast shipping | Easy returns | Special discounts for students
        </p>
    </div>

    <div class="space-y-12">
        <div class="flex flex-row items-center gap-x-8 px-3">
            <img
                src="../assets/images/mysterybox/stockx5.png"
                class="rounded-[2rem] w-[583px] h-[583px]"
            />
            <div class="flex flex-col gap-y-6">
                <p class="font-bold text-[42px] text-[#293632]">
                    Curious about the <span class="text-[#006340]">StockX</span> Mystery Box?
                </p>
                <div class="flex flex-col text-base space-y-2">
                    <span>
                        Experience the thrill of unboxing cutting-edge gadgets with Stockx Mystery
                        Boxes. Each box is a treasure trove of high-quality electronics, handpicked
                        to elevate your tech game.
                    </span>
                    <span>
                        Expect the unexpected! Our boxes are packed with the latest gadgets, from
                        smartphones to gaming consoles, ensuring you get the best tech surprises
                        every time.
                    </span>
                </div>
            </div>
        </div>

        <div class="flex flex-row items-center gap-x-8 px-3">
            <div class="flex flex-col gap-y-6">
                <p class="font-bold text-[42px] text-[#293632]">
                    Why is everyone buzzing about these boxes?
                </p>
                <div class="flex flex-col text-base space-y-2">
                    <span>
                        StockX Mystery Boxes are not just about products; they’re about the
                        experience. Imagine the excitement of unveiling top-tier electronics at a
                        fraction of the cost.
                    </span>
                    <span>
                        Our boxes include a variety of premium tech items, making it a must-have for
                        every tech enthusiast. Join the buzz and see why everyone is raving about
                        the unbeatable value and surprise factor of Stockx Mystery Boxes!
                    </span>
                </div>
            </div>
            <img
                src="../assets/images/mysterybox/stockx6.png"
                class="rounded-[2rem] w-[583px] h-[583px]"
            />
        </div>
    </div>

    <Footer />
</template>
