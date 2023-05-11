<template>
  <div class="headerComponent">
    <HeaderBanner/>
    <HeaderUtil/>
    <HeaderGNB/>
  </div>
</template>

<script>
import HeaderBanner from './header/HeaderBanner.vue';
import HeaderUtil from './header/HeaderUtil.vue';
import HeaderGNB from './header/HeaderGNB.vue';
export default {
  name: 'HeaderComponent',
  components: {
    HeaderBanner,
    HeaderUtil,
    HeaderGNB
  }
}
</script>

<style scoped>
  .headerComponent { 
    background: #666;

  }
</style>