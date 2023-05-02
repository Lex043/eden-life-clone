<template>
  <footer className="mt-8">
    <figure className="flex gap-5">
      <img :src="twitter" alt="twitter" />
      <img :src="instagram" alt="instagram" />
      <img :src="facebook" alt="facebook" />
      <img :src="linkedin" alt="linkedin" />
    </figure>
    <p className="my-5">2023 Eden Life Inc. All Rights Reserved.</p>
  </footer>
</template>

<script setup lang="ts">
import twitter from "../assets/twitter_pxdich.svg";
import instagram from "../assets/instagram_erb6q6.svg";
import facebook from "../assets/facebook_cqsjdf.svg";
import linkedin from "../assets/linkedin_utcbna.svg";
</script>

<style scoped></style>
