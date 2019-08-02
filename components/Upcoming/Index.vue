<template>
  <div>
    <h1>Upcoming Events</h1>
    <div class="overflow-x-scroll overflow-y-hidden">
      <div class="h-40 inline-flex px-5 py-2">
        <Cards />
        <Cards />
        <Cards />
        <Cards />
        <Cards />
      </div>
    </div>
  </div>
</template>

<script>
import Cards from '~/components/UpComing/Cards'
export default {
  components: {
    Cards
  }
}
</script>
