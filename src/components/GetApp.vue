<template>
  <section className="bg-[#61db98] mx-4 rounded-2xl">
    <img
      :src="footer_top_image"
      alt="footer top image"
      className="w-[70%] mx-auto relative bottom-12"
    />
    <div className="text-center  pb-8">
      <h1 className="text-4xl text-[#21312a] font-semibold">
        Download the app!
      </h1>
      <p className="pt-4 px-6 pb-6">It takes less than 5 minutes to sign up!</p>
      <div className="flex flex-col gap-2 items-center">
        <figure>
          <img :src="playstore" alt="playstore" />
        </figure>
        <figure>
          <img :src="applestore" alt="applestore" />
        </figure>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
import footer_top_image from "../assets/footer-phone_xeixqy.svg";
import playstore from "../assets/playstore_n43eju.svg";
import applestore from "../assets/appstore_o1bj6d.svg";
</script>

<style scoped></style>
