<template>
  <section className="pt-40 pb-20">
    <header className="text-center mb-4">
      <h1 className="font-semibold text-lg text-[#21312A]">Not in Lagos?</h1>
      <p className="text-[#21312A] text-[0.91rem] py-3">
        We're coming to your city. Be the first to know when we touch down.
      </p>
    </header>
    <form className="text-center">
      <input
        type="text"
        placeholder="Enter your email"
        className="text-[#21312A] outline-none pl-2 w-full border-2 h-16"
      />
      <select
        name="city"
        id="city"
        className="w-full h-16 outline-none border-2 px-2 mb-4"
      >
        <option value="" className="text-[#21312A] font-semibold">
          Select your city
        </option>
        <option value="Abia">Abia</option>
        <option value="Abuja">Abuja</option>
        <option value="Adamawa">Adamawa</option>
        <option value="Akwa Ibom">Akwa Ibom</option>
        <option value="Bauchi">Bauchi</option>
        <option value="Bayelsa">Bayelsa</option>
        <option value="Benue">Benue</option>
        <option value="Bornu">Bornu</option>
        <option value="Cross River">Cross River</option>
        <option value="Delta">Delta</option>
        <option value="Ebonyi">Ebonyi</option>
        <option value="Edo">Edo</option>
        <option value="Ekiti">Ekiti</option>
        <option value="Enugu">Enugu</option>
        <option value="Gombe">Gombe</option>
        <option value="Imo">Imo</option>
        <option value="Jigawa">Jigawa</option>
        <option value="Kaduna">Kaduna</option>
        <option value="Kano">Kano</option>
        <option value="Kastina">Kastina</option>
        <option value="Kebbi">Kebbi</option>
        <option value="Kogi">Kogi</option>
        <option value="Kwara">Kwara</option>
        <option value="Nasarawa">Nasarawa</option>
        <option value="Niger">Niger</option>
        <option value="Ogun">Ogun</option>
        <option value="Ondo">Ondo</option>
        <option value="Osun">Osun</option>
        <option value="Oyo">Oyo</option>
        <option value="Plateu">Plateu</option>
        <option value="Rivers">Rivers</option>
        <option value="Sokoto">Sokoto</option>
        <option value="Taraba">Taraba</option>
        <option value="Yobe">Yobe</option>
        <option value="Zamfara">Zamfara</option>
      </select>
      <button
        className="bg-[#03a84e] text-white w-full py-4 rounded-md font-semibold text-lg mt-2"
      >
        Send Message
      </button>
    </form>
  </section>
</template>

<script setup lang="ts"></script>
