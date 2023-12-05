<script >

export default {
    data() {
        return {
            MainTitle: "THE BEST TABLE IN TOWN",
            Introduction: "Enjoy your night out, we offer one of the best experience and amazing atmosphere, delicius products and drinks for a perfect dinner!",




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
                <span>FINE DINING EXPERIENCE </span>
                <h2>{{ MainTitle }}</h2>
                <p>{{ Introduction }}</p>
                <button><a>EXPLORE THE MENU</a>
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
    min-height: 600px;
    display: flex;
    justify-content: space-between;


    //   logo and content style
    .my_content {
        padding: 1.3rem 7rem;
        width: 45%;
        position: relative;

        hr {
            width: 5%;
            position: absolute;
            top: 26.5%;
            left: 8%;
            // border: 1px solid #ffff;
            color: #ffff;
        }

        // content with paragraphs and main title 
        .content {
            padding-top: 8rem;
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

        background-image: url(https://ae01.alicdn.com/kf/H6f12ac7d96b743509ed03cde2908dec0R/Vancasso-Haruka-Set-di-piatti-per-Sushi-in-porcellana-in-stile-giapponese-con-2-piatti-per.jpg);
        background-size: cover;
        width: 55%;

    }

}
</style>