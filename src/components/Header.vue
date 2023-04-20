<template>
  <header class="bg-gray-900 text-white w-full py-4 px-8">
    <div class="container mx-auto flex justify-between items-center">
      <h1
        class="
          text-2xl
          font-bold
          text-green-500
          cursor-pointer
          hover:text-green-400
          transition-colors
          duration-300
        "
      >
        Gonzalo Suarez
      </h1>
      <nav class="text-green-500">
        <ul class="flex">
          <li class="mx-4">
            <a href="#services" class="hover:text-green-400">Servicios</a>
          </li>
          <li class="mx-4">
            <a href="#portfolio" class="hover:text-green-400">Portafolio</a>
          </li>
          <li class="mx-4">
            <a href="#contact" class="hover:text-green-400">Contacto</a>
          </li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: 'Header',
};
</script>

<style>
header {
  transition: background-color 0.5s ease;
}

header:hover {
  background-color: #222;
}
</style>
