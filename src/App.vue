<script>
import AppTitle from './components/AppTitle.vue';
export default{
  data(){
    name: 'Yeah'
  },
  components:{
    AppTitle: AppTitle
  }

}
</script>

<template>
<AppTitle />
<p>{{ name }}</p>
</template>

<style>
/* stile css */
</style>