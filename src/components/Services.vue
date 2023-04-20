<template>
  <section class="bg-white w-full py-16" id="services">
    <div class="container mx-auto">
      <h2
        class="
          text-3xl
          font-bold
          text-gray-900 text-center
          mb-8
          animate__animated animate__fadeInUp
        "
      >
        Servicios
      </h2>
      <div class="flex flex-wrap justify-between">
        <div class="w-full md:w-1/2 lg:w-1/3 px-4 mb-8">
          <div
            class="
              bg-blue-500
              hover:bg-blue-700
              rounded-lg
              p-4
              transition
              duration-300
              ease-in-out
              cursor-pointer
              transform
              hover:scale-105
              shadow-md
              animate__animated animate__fadeInRight
            "
          >
            <h3 class="text-xl font-bold mb-4 text-white">
              Desarrollo Frontend
            </h3>
            <p class="text-gray-100">
              Desarrollo de aplicaciones web modernas y escalables utilizando
              tecnologías como Vue.js, React y Angular.
            </p>
          </div>
        </div>
        <div class="w-full md:w-1/2 lg:w-1/3 px-4 mb-8">
          <div
            class="
              bg-green-500
              hover:bg-green-700
              rounded-lg
              p-4
              transition
              duration-300
              ease-in-out
              cursor-pointer
              transform
              hover:scale-105
              shadow-md
              animate__animated animate__fadeInLeft
            "
          >
            <h3 class="text-xl font-bold mb-4 text-white">
              Desarrollo Backend
            </h3>
            <p class="text-gray-100">
              Desarrollo de API's y aplicaciones web en el servidor utilizando
              tecnologías como Node.js, Express.js y Laravel.
            </p>
          </div>
        </div>
        <div class="w-full md:w-1/2 lg:w-1/3 px-4 mb-8">
          <div
            class="
              bg-indigo-500
              hover:bg-indigo-700
              rounded-lg
              p-4
              transition
              duration-300
              ease-in-out
              cursor-pointer
              transform
              hover:scale-105
              shadow-md
              animate__animated animate__fadeInRight
            "
          >
            <h3 class="text-xl font-bold mb-4 text-white">Desarrollo Móvil</h3>
            <p class="text-gray-100">
              Desarrollo de aplicaciones móviles nativas para iOS y Android
              utilizando tecnologías como Swift, Kotlin y React Native.
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Services',
};
</script>

<style scoped>
@import '~animate.css';
</style>
