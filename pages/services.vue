<template>
  <div class="mx-auto pt-20">
    <div class="section">
      <div class="section-title">OUR SERVICES</div>
      <div class="section-subtitle">We offer so many of the things...</div>
      <div class="flex justify-center flex-wrap p-10">
        <div class="relative w-48 h-64 m-5 bg-white shadow-lg">
          <div class="flex items-center w-48 h-20 bg-orange-500">
            <i class="fas fa-bezier-curve fa-3x mx-auto text-white"></i>
          </div>
          <p
            class="mx-2 py-2 border-b-2 text-center text-gray-700 font-semibold uppercase"
          >
            UI Design
          </p>
          <p class="p-2 text-sm text-gray-700">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean ac
            est massa.
          </p>
          <div
            class="absolute right-0 bottom-0 w-8 h-8 bg-gray-300 hover:bg-orange-300 text-center cursor-pointer"
          >
            <i class="fas fa-chevron-right mt-2 text-orange-500"></i>
          </div>
        </div>
        <div class="relative w-48 h-64 m-5 bg-white shadow-lg">
          <div class="flex items-center w-48 h-20 bg-green-500">
            <i class="fas fa-laptop-code fa-3x mx-auto text-white"></i>
          </div>
          <p
            class="mx-2 py-2 border-b-2 text-center text-gray-700 font-semibold uppercase"
          >
            Web Dev
          </p>
          <p class="p-2 text-sm text-gray-700">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean ac
            est massa.
          </p>
          <div
            class="absolute right-0 bottom-0 w-8 h-8 bg-gray-300 hover:bg-green-300 text-center cursor-pointer"
          >
            <i class="fas fa-chevron-right mt-2 text-green-500"></i>
          </div>
        </div>
        <div class="relative w-48 h-64 m-5 bg-white shadow-lg">
          <div class="flex items-center w-48 h-20 bg-yellow-500">
            <i class="fas fa-mobile-alt fa-3x mx-auto text-white"></i>
          </div>
          <p
            class="mx-2 py-2 border-b-2 text-center text-gray-700 font-semibold uppercase"
          >
            Mobile Apps
          </p>
          <p class="p-2 text-sm text-gray-700">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean ac
            est massa.
          </p>
          <div
            class="absolute right-0 bottom-0 w-8 h-8 bg-gray-300 hover:bg-yellow-300 text-center cursor-pointer"
          >
            <i class="fas fa-chevron-right mt-2 text-yellow-500"></i>
          </div>
        </div>
        <div class="relative w-48 h-64 m-5 bg-white shadow-lg">
          <div class="flex items-center w-48 h-20 bg-teal-500">
            <i class="fas fa-search-dollar fa-3x mx-auto text-white"></i>
          </div>
          <p
            class="mx-2 py-2 border-b-2 text-center text-gray-700 font-semibold uppercase"
          >
            SEO
          </p>
          <p class="p-2 text-sm text-gray-700">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean ac
            est massa.
          </p>
          <div
            class="absolute right-0 bottom-0 w-8 h-8 bg-gray-300 hover:bg-teal-300 text-center cursor-pointer"
          >
            <i class="fas fa-chevron-right mt-2 text-teal-500"></i>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Services",
  head: {
    title: "Services",
    meta: [{ hid: "description", name: "description", content: "Services" }],
  },
}
</script>

<style scoped>
.headerTitle {
  margin-top: 10px;
  margin-bottom: 20px;
  @apply text-4xl;
}
</style>
