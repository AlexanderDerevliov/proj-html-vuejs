<script >
import AppHeader from './components/AppHeader.vue';
import AppAboutUs from './components/AppAboutUs.vue';

export default {
  data(){
    return{
     
    }
  },
  components: {AppHeader, AppAboutUs,}
}
</script>

<template>

<AppHeader />
<AppAboutUs />
</template>

<style lang="scss">
@use "./style/general.scss";
@import "@fortawesome/fontawesome-free/css/all.css";

</style>
