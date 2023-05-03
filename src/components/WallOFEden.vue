<template>
  <section className="bg-[#f7f8fe]">
    <h1 className="text-3xl font-semibold text-center py-9">The Wall of 💚</h1>
    <figure
      className="grid grid-cols-3 px-4 gap-6 py-10 justify-center md:place-items-center md:w-[50%] md:mx-auto"
    >
      <img className="w-20" :src="cowrywise" alt="cowrywise" />
      <img className="w-20" :src="flutterwave" alt="flutterwave" />
      <img className="w-20" :src="paystack" alt="paystack" />
      <img className="w-20" :src="kuda" alt="kuda" />
      <img className="w-20" :src="buycoins" alt="buycoins" />
      <img className="w-20" :src="piggyvest" alt="piggyvest" />
    </figure>
    <CustomerReview />
  </section>
</template>

<script setup lang="ts">
import cowrywise from "../assets/cowrywise_wtcvv5.svg";
import flutterwave from "../assets/flutterwave_cmhzbz.svg";
import paystack from "../assets/paystack_zez4ir.svg";
import kuda from "../assets/kuda_irz12h.svg";
import buycoins from "../assets/buycoins_bkcrvh.svg";
import piggyvest from "../assets/piggyvest_wyio8s.svg";
import CustomerReview from "./CustomerReview.vue";
</script>
