<script >
import AppHeader from './components/AppHeader.vue';
import AppAboutUs from './components/AppAboutUs.vue';
import AppDinningExp from './components/AppDinningExp.vue';

export default {
  data(){
    return{
     
    }
  },
  components: { AppHeader, AppAboutUs, AppDinningExp }
}
</script>

<template>
<AppHeader />
<AppAboutUs />
<AppDinningExp />


</template>

<style lang="scss">
@use "./style/general.scss";
@import "@fortawesome/fontawesome-free/css/all.css";

</style>
