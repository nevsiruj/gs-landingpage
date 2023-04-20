<template>
  <section class="bg-black text-white w-full py-16">
    <div
      class="
        container
        mx-auto
        flex flex-col
        md:flex-row
        items-center
        justify-between
      "
    >
      <div class="md:w-1/2">
        <!-- <img
          src="./assets/banner.jpg"
          alt="Banner"
          class="w-full h-auto rounded-lg shadow-lg animate__animated animate__fadeInLeft"
        /> -->
      </div>
      <div class="md:w-1/2 text-center md:text-left">
        <h2
          class="text-4xl font-bold mb-4 animate__animated animate__fadeInRight"
        >
          FullStack Developer
        </h2>
        <p
          class="
            text-gray-300 text-xl
            mb-6
            animate__animated animate__fadeInRight
          "
        >
          Servicios de desarrollo web a medida
        </p>
        <a
          href="#contact"
          class="
            bg-green-500
            hover:bg-green-700
            text-white
            font-bold
            py-3
            px-6
            rounded
            mt-8
            inline-block
            animate__animated animate__fadeInUp animate__delay-1s
          "
          >Contactar</a
        >
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'HeroSection',
};
</script>

<style scoped>
@import '~animate.css';

img {
  max-height: 400px;
}
</style>
