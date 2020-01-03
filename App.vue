<template>
  <view class="container">
    <Statusbar color="#459fed" />
    <Header title="Helsinki App" />  
  </view>
</template>

<script>
import Statusbar from './components/Statusbar'
import Header from './components/Header'

export default {
  components: {
    Statusbar,
    Header
  }
}
</script>

<style>

.container {
    flex: 1;
    background-color: #fff;
    
}
</style>

