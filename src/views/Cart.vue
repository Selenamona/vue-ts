<template>
  <div class="cart">
      <Header/>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import Component from 'vue-class-component';
import Header from '@/components/common/header.vue';
 
export default Vue.extend({
  components: {
    Header
  }
})
</script> 

