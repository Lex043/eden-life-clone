<template>
  <section className="mt-10 px-6">
    <figure className="flex flex-col gap-4 items-start">
      <img :src="logo" alt="eden logo" />
      <p>
        10x-ing the quality of life <br />
        on the continent.
      </p>
    </figure>
    <section className="mt-8 flex gap-8 justify-between flex-wrap">
      <ul className="text-[#21312a] flex flex-col gap-5">
        <li className="font-semibold">Sevices</li>
        <li>Food</li>
        <li>Cleaning</li>
        <li>Laundry</li>
      </ul>
      <ul className="text-[#21312a] flex flex-col gap-5">
        <li className="font-semibold">Company</li>
        <li>About Us</li>
        <li>Companies</li>
        <li>Pricing</li>
        <li>Careers</li>
      </ul>
      <ul className="text-[#21312a] flex flex-col gap-5">
        <li className="font-semibold">Other</li>
        <li>FAQs</li>
        <li>Blog</li>
        <li>Contact Us</li>
        <li>Terms & Conditions</li>
        <li>Private Policy</li>
      </ul>
    </section>
    <LastFooter />
  </section>
</template>

<script setup lang="ts">
import logo from "../assets/eden-logo_lcepc6.svg";
import LastFooter from "./LastFooter.vue";
</script>

<style scoped></style>
