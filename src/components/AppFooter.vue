<script >
export default {
  data() {
    return {

    }
  }
}
</script>

<template>
  <div class="container">
    <div class="smallContainer">
      <div class="social">
        <img src="../assets/img/logo-ristorante.png" alt="">

        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Libero pariatur aut, voluptatem nisi vero praesentium
          quos officia quaerat, ut laboriosam possimus itaque natus provident harum, corporis dicta molestias odit.
          Maxime!</p>



        <a class="social-m" href=""><i class="fa-brands fa-facebook"></i></a>
        <a class="social-m" href=""><i class="fa-brands fa-instagram"></i></a>
        <a class="social-m" href=""><i class="fa-brands fa-youtube"></i></a>
        <a class="social-m" href=""><i class="fa-brands fa-telegram"></i></a>
      </div>
    </div>

    <p>Copyright 2012 1019 Avada | All Rights Recived | Powered By Wordpress</p>
  </div>
</template>

<style lang="scss" scoped>
.container {
  width: 100%;
  min-height: 600px;
  background-color: #030303;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  padding-top: 6rem ;
  
  

   p {
    color: #ffff;
    margin: 1rem 0;
    
   }

  .smallContainer {
    width: 100%;
    min-height: 400px;
    background-image: url(../assets/img/images.jpeg);
    background-size: cover;
    box-shadow: inset #03030380 0px 700px 0px 0px;
    

    p {
        margin: 2rem 0;
        color: white;
      }
      

    .social {
      width: 50%;
      margin: 0 auto;
      padding: 5rem 0;
      text-align: center;

      img {
        padding: 3rem 0;
      }

      a {
      color: #ffff;
      text-decoration: none;
      padding: .5rem;
      font-size: 2rem;
    }
    }
  }


}
</style>