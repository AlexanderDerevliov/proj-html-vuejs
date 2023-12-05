<script >
export default {
  data() {
    return {

    }
  }
}
</script>

<template>
  <div class="my_container">
    <!-- upper row -->
    <div class="my_upRow">
      <!-- text area -->
      <div class="text-area">
        <span><strong>HAC TELLUS, FELIS RISUS AT</strong> Lorem ipsum dolor sit amet consectetur adipisicing elit.
          Necessitatibus sit sed repellendus animi esse odit rem, facilis laborum tempore dolore itaque nemo eveniet
          quibusdam recusandae tempora mollitia. Dicta, aliquid possimus.</span>

        <h2>FOOD IS OUR COMMON GROUND, A UNIVERSAL EXPERIENCE.</h2>


        <p>Autem doloremque repellat assumenda, rerum incidunt sed ullam unde, sequi hic sit, nesciunt minus quae? Iste,
          architecto.</p>

        <img src="../assets/img/signature.png" alt="">


      </div>
      <!-- immage area -->
      <div class="my_img-area">
        <p>California Rolls - $22</p>
      </div>

    </div>
    <div class="my_downRow">
      <div class="col">
        <div class="card">

          <img src="../assets/img/sushi-1.png" alt="">

          <h4>THE BEST TABLE IN TOWN</h4>

          <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Repellendus placeat quaerat quod
            repellat pariatur.</p>

          <button><a>EXPLORE THE MENU</a>
          </button>


        </div>
      </div>
      <div class="col">
        <div class="card">

          <img src="../assets/img/sushi-2.png" alt="">

          <h4>PERFECT FOR GROUPS</h4>

          <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Repellendus placeat quaerat quod
            repellat pariatur.</p>

          <button><a>MAKE A RESERVATION</a>
          </button>

        </div>
      </div>
      <div class="col">
        <div class="card">

          <img src="../assets/img/sushi-3.png" alt="">

          <h4>FRESH PRODUCE EVERYDAY</h4>

          <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Repellendus placeat quaerat quod
            repellat pariatur.</p>

          <button><a>LEARN MORE ABOUT US</a>
          </button>

        </div>
      </div>

    </div>
  </div>
</template>

<style lang="scss" scoped>
.my_container {
  width: 80%;
  margin: 0 auto;
  min-height: 600px;
  margin-top: 2rem;
  gap: 1rem;

  .my_upRow {
    width: 100%;
    min-height: 550px;
    padding: 3rem;
    display: flex;
    justify-content: space-evenly;


    .text-area {
      width: 45%;
      padding: 3rem;



      h2 {
        color: #030303;
        margin: 2rem 0;
        font-size: 2rem;
      }

      span {
        color: #030303;
        font-size: .8rem;

      }



      p {
        line-height: 1.5rem;
      }

      img {
        height: 80px;
        width: 80px;
        margin-top: 1.5rem;
      }

    }

    .my_img-area {
      width: 35%;
      background-size: cover;
      position: relative;
      background-image: url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRvzqvqRCWclBlusCjYqgbD05Vuce_dKc5vUg&usqp=CAU);

      p {
        color: #ffff;
        position: absolute;
        bottom: 5%;
        left: 31%;


      }
    }



  }

  .my_downRow {
    width: 75%;
    margin: 3rem auto;
    min-height: 300px;
    display: flex;
    justify-content: space-evenly;
    gap: 2rem;

    .col {
      width: 100%;


      .card {
        padding: 1rem;
        text-align: center;

        h4 {
          margin: 2rem 0;

        }

        button {
                padding: .6rem 1rem;
                margin-top: 2rem;
                color: #030303;
                background-color: #ffff;
                border-color: #030303;

                // hover on button header
                &:hover {
                    background-color: #030303;
                    color: #ffff;
                    transition: all 1.3s;
                }
            }


      }
    }

  }
}
</style>