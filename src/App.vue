<script >
import AppHeader from './components/AppHeader.vue';
import AppAboutUs from './components/AppAboutUs.vue';
import AppDinningExp from './components/AppDinningExp.vue';
import AppCritics from './components/AppCritics.vue';
import AppBigImg from './components/AppBigImg.vue';
import AppPromotions from './components/AppPromotions.vue';
import AppReservation from './components/AppReservation.vue';
import AppMenu from './components/AppMenu.vue';

export default {
  data(){
    return{
     
    }
  },
  components: { AppHeader, AppAboutUs, AppDinningExp, AppCritics, AppBigImg, AppPromotions, AppReservation, AppMenu }
}
</script>

<template>
<AppHeader />
<AppAboutUs />
<AppDinningExp />
<AppCritics />
<AppBigImg />
<AppPromotions />
<AppReservation />
<AppMenu />


</template>

<style lang="scss">
@use "./style/general.scss";
@import "@fortawesome/fontawesome-free/css/all.css";

</style>
