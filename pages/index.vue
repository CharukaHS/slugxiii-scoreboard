<template>
  <div>
    <Upcoming />
    <ScoreChart />
    <ScoreCard />
  </div>
</template>

<script>
import Upcoming from '~/components/UpComing/Index'
import ScoreChart from '~/components/ScoreChart/Index'
import ScoreCard from '~/components/ScoreCards/Index'
export default {
  components: {
    Upcoming,
    ScoreChart,
    ScoreCard,
  }
}
</script>
