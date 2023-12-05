<script >
import AppHeader from './components/AppHeader.vue';
import AppAboutUs from './components/AppAboutUs.vue';
import AppDinningExp from './components/AppDinningExp.vue';
import AppCritics from './components/AppCritics.vue';

export default {
  data(){
    return{
     
    }
  },
  components: { AppHeader, AppAboutUs, AppDinningExp, AppCritics }
}
</script>

<template>
<AppHeader />
<AppAboutUs />
<AppDinningExp />
<AppCritics />


</template>

<style lang="scss">
@use "./style/general.scss";
@import "@fortawesome/fontawesome-free/css/all.css";

</style>
