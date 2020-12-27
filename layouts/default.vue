<template>
  <div>
    <NavBar />
    <nuxt />
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
  },
}
</script>
