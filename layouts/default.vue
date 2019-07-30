<template>
  <div class="flex mb-4 h-screen">
    <div class="w-1/4 overflow-y-auto">
      <Menu />
    </div>
    <div class="w-3/4 bg-gray-100 overflow-y-auto">
      <nuxt />
    </div>
  </div>
</template>

<script>
import Menu from '~/components/SideMenu/Menu'
export default {
  components: {
    Menu
  }
}
</script>
