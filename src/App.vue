<template>
  <div id="app">
    <TopHeader/>
    <keep-alive>
      <router-view></router-view>
    </keep-alive>
    <player></player>
  </div>
</template>

<script>
import TopHeader from 'src/components/top-header/TopHeader'
import Player from 'components/player/player'

export default {
  name: 'App',
  components: {
    TopHeader,
    Player
  }
}
</script>

<style>

</style>
