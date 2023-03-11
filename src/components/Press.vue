<template>
  <section className="bg-[#fffcfa] pt-14 px-4">
    <h1 className="font-semibold font-ptserif text-2xl text-center px-8">
      Check us out in the press.
    </h1>
    <figure
      className="flex gap-14 justify-center items-center flex-wrap mt-5 mb-20"
    >
      <img :src="futureAfrica" alt="future Africa" className="w-20" />
      <img :src="press" alt="press" className="w-10" />
      <img :src="techcabal" alt="techcabal" className="w-20" />
      <img :src="techpoint" alt="techpoint" className="w-20" />
    </figure>
  </section>
</template>

<script setup lang="ts">
import futureAfrica from "../assets/future-africa.d9209b3.svg";
import techcabal from "../assets/techcabal.67288ea.svg";
import techpoint from "../assets/techpoint.5d67bf9.svg";
import press from "../assets/press2.aa8fb35.svg";
</script>
