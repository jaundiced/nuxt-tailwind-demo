<template>
  <div class="mx-auto pt-20">
    <div class="section">
      <div class="section-title">OUR TEAM</div>
      <div class="section-subtitle">We offer things and stuff.</div>
      <div class="flex justify-center flex-wrap p-10">
        <div class="relative w-48 h-64 m-5 bg-white shadow-lg">
          <p
            class="mx-2 py-2 border-b-2 text-center text-gray-700 font-semibold uppercase"
          >
            Coach
          </p>
          <p class="p-2 text-sm text-gray-700">
            <img src="/Coach.PNG" />
          </p>
        </div>
        <div class="relative w-48 h-64 m-5 bg-white shadow-lg">
          <p
            class="mx-2 py-2 border-b-2 text-center text-gray-700 font-semibold uppercase"
          >
            Glen
          </p>
          <p class="p-2 text-sm text-gray-700">
            <img src="/Glen.PNG" />
          </p>
        </div>
        <div class="relative w-48 h-64 m-5 bg-white shadow-lg">
          <p
            class="mx-2 py-2 border-b-2 text-center text-gray-700 font-semibold uppercase"
          >
            Bonnie
          </p>
          <p class="p-2 text-sm text-gray-700">
            <img src="/Bonnie.PNG" />
          </p>
        </div>
        <div class="relative w-48 h-64 m-5 bg-white shadow-lg">
          <p
            class="mx-2 py-2 border-b-2 text-center text-gray-700 font-semibold uppercase"
          >
            Katy
          </p>
          <p class="p-2 text-sm text-gray-700">
            <img src="/Katy.PNG" />
          </p>
        </div>
        <div class="relative w-48 h-64 m-5 bg-white shadow-lg">
          <p
            class="mx-2 py-2 border-b-2 text-center text-gray-700 font-semibold uppercase"
          >
            Dan
          </p>
          <p class="p-2 text-sm text-gray-700">
            <img src="/Dan.jpg" />
          </p>
        </div>
        <div class="relative w-48 h-64 m-5 bg-white shadow-lg">
          <p
            class="mx-2 py-2 border-b-2 text-center text-gray-700 font-semibold uppercase"
          >
            Daryl
          </p>
          <p class="p-2 text-sm text-gray-700">
            <img src="/Daryl.PNG" />
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Team",
  head: {
    title: "Team",
    meta: [{ hid: "description", name: "description", content: "Team" }],
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
