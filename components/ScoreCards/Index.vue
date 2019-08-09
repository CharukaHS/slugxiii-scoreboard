<template>
  <div>
    <h1>Cards</h1>
    <div class="flex flex-wrap justify-center">
      <Card />
      <Card />
      <Card />
      <Card />
    </div>
  </div>
</template>

<script>
import Card from '~/components/ScoreCards/Card'
export default {
  components: {
    Card
  }
}
</script>

