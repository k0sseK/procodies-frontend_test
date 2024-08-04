<script setup lang="ts">
import ProductCard from '../components/ProductCard.vue'
import MysteryBoxForm from '../components/MysteryBoxForm.vue'
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
</template>
