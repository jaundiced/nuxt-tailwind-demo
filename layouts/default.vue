<template>
  <div>
    <NavBar />
    <div
      class="container mx-auto shadow-xl bg-gray-100 text-blue-500 border-blue-200 text-xl w-3/4 p-10"
    >
      <nuxt />
    </div>
  </div>
</template>

<script>
import NavBar from "@/components/navbar.vue"
export default {
  name: "AppLayout",
  components: { NavBar },
  head: {
    bodyAttrs: {
      class: "font-sans bg-blue-900",
    },
    link: [
      {
        rel: "stylesheet",
        href:
          "https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.9.0/css/all.min.css",
      },
    ],
  },
}
</script>
