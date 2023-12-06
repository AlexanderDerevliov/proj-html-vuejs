<script >
import AppHeader from './components/AppHeader.vue';
import AppAboutUs from './components/AppAboutUs.vue';
import AppDinningExp from './components/AppDinningExp.vue';
import AppCritics from './components/AppCritics.vue';
import AppBigImg from './components/AppBigImg.vue';
import AppPromotions from './components/AppPromotions.vue';

export default {
  data(){
    return{
     
    }
  },
  components: { AppHeader, AppAboutUs, AppDinningExp, AppCritics, AppBigImg, AppPromotions }
}
</script>

<template>
<AppHeader />
<AppAboutUs />
<AppDinningExp />
<AppCritics />
<AppBigImg />
<AppPromotions />


</template>

<style lang="scss">
@use "./style/general.scss";
@import "@fortawesome/fontawesome-free/css/all.css";

</style>
