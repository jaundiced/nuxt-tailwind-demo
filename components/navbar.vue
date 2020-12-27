<template>
  <div class="flex justify-between items-center py-4 bg-blue-900">
    <div class="flex-shrink-0 ml-10 cursor-pointer">
      <i class="fas fa-folder-open fa-2x text-orange-500"></i>
      <span class="ml-1 text-3xl text-blue-200 font-semibold">Demo</span>
    </div>
    <i class="md:invisible mr-10 md:mr-0 text-blue-200 cursor-pointer"></i>
    <ul class="hidden md:flex overflow-x-hidden mr-10 font-semibold">
      <li
        :class="
          this.$route.name == 'index'
            ? activeLinkListItem
            : inActiveLinkListItem
        "
      >
        <nuxt-link class="text-blue-200" to="/">Home</nuxt-link>
      </li>
      <li
        :class="
          this.$route.name == 'services'
            ? activeLinkListItem
            : inActiveLinkListItem
        "
      >
        <nuxt-link class="text-blue-200" to="/services">Services</nuxt-link>
      </li>
      <li
        :class="
          this.$route.name == 'projects'
            ? activeLinkListItem
            : inActiveLinkListItem
        "
      >
        <nuxt-link class="text-blue-200" to="/projects">Projects</nuxt-link>
      </li>
      <li
        :class="
          this.$route.name == 'team' ? activeLinkListItem : inActiveLinkListItem
        "
      >
        <nuxt-link class="text-blue-200" to="/team">Team</nuxt-link>
      </li>
      <li
        :class="
          this.$route.name == 'about'
            ? activeLinkListItem
            : inActiveLinkListItem
        "
      >
        <nuxt-link class="text-blue-200" to="/about">About</nuxt-link>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "NavBar",
  data() {
    return {
      activeLinkListItem: "mr-6 p-1 border-b-2 border-orange-500",
      inActiveLinkListItem: "mr-6 p-1",
    }
  },
}
</script>
<style scoped>
.nuxt-link-exact-active {
  cursor: default;
  @apply text-blue-400;
}
</style>
