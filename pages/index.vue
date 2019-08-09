<template>
  <div>
    <Upcoming />
    <ScoreChart />
  </div>
</template>

<script>
import Upcoming from '~/components/UpComing/Index'
import ScoreChart from '~/components/ScoreChart/Index'
export default {
  components: {
    Upcoming,
    ScoreChart
  }
}
</script>
