<template>
  <div class="container flex flex-col justify-center px-16">
    <img src="/logo.png" class="mt-10 mb-2 px-4" />

    <input
      class="bg-white focus:outline-0 focus:shadow-outline border border-gray-300 rounded-full py-2 px-4 block w-full appearance-none leading-normal mb-20"
      type="search"
      placeholder="Search"
    />

      <Pill />
      <Pill />
      <Pill />
      <Pill />
      <Pill />
      <Pill />
  </div>
</template>

<script>
import Pill from '~/components/SideMenu/Pill'

export default {
  components: {
    Pill
  }
}
</script>


