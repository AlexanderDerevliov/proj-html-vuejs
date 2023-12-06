<script >

export default {
    data() {
        return {
            MainTitle: "TAKEOUT NOW AVAIABLE",
            text: "Enjoy your night out, we offer one of the best experience and amazing atmosphere, delicius products and drinks for a perfect dinner!",




        }
    }
}
</script>

<template>
    <!-- main container -->
    <div class="my_container">


        <div class="my_img-container">


        </div>

        <div class="my_content">

            <hr>



            <!-- content -->
            <div class="content">
                <span>ENJOY YOUR MEAL AT HOME </span>
                <h2>{{ MainTitle }}</h2>
                <p>{{ text }}</p>
                <button><i class="fa-solid fa-car"></i><a>VIEW TAKE OUT MENU</a>
                </button>
            </div>

        </div>




    </div>
</template>

<style lang="scss" scoped>
// main container of header
.my_container {
    background-color: #030303;
    width: 100%;
    display: flex;
    justify-content: space-between;


    //   logo and content style
    .my_content {
        padding: 8rem 7rem;
        width: 45%;
        position: relative;

        hr {
            width: 5%;
            position: absolute;
            top: 22.5%;
            left: 8%;
            // border: 1px solid #ffff;
            color: #ffff;
        }

        // content with paragraphs and main title 
        .content {
            width: 90%;
            margin: 0 auto;



            h2 {
                color: #ffff;
                margin: 2rem 0;
                font-size: 3rem;
            }

            p {
                color: #bcbcbc;
                line-height: 1.5rem;
            }

            span {
                color: #bcbcbc;
                font-size: .8rem;

            }

            // button style plus hover

            button {
                padding: .6rem 2rem;
                margin-top: 3rem;
                color: #ffff;
                background-color: #030303;
                border-color: #ffff;

                a{
                    padding: 0 .5rem;
                }

                // hover on button header
                &:hover {
                    background-color: #ffff;
                    color: #030303;
                    transition: all 1.3s;
                }
            }
        }
    }



    .my_img-container {
        // background image taken from webb

        background-image: url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRpoQWBuiSRcRF4BsDKeDDA2lJ6q6pei-A6SA&usqp=CAU);
        background-size: cover;
        width: 55%;

    }

}
</style>