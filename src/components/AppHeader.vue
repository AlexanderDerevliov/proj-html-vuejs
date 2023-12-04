<script >

export default {
    data() {
        return {
            menuNavigation: [
                "Home",
                "Culinary-History",
                "Our Team",
                "Our Menu",
                "Take out",
                "Bulletin",
                "Reservation"


            ],

            MainTitle: "FINE DINING EXPERIENCE",
            Introduction: "Enjoy your night out, we offer one of the best experience and amazing atmosphere, delicius products and drinks for a perfect dinner!",




        }
    }
}
</script>

<template>

    <!-- main container -->
    <div class="my_header-container">
        <!-- here goes the left side with logo and under there is a description -->
        <div class="my_logo-content">

            <hr>

            <!-- here goes just logo -->
            <section class="logo">
                <img src="../assets/img/logo-ristorante.png" alt="">

                <!-- content -->
                <div class="content">
                    <span>THE BEST TABLE IN TOWN </span>
                    <h1>{{ MainTitle }}</h1>
                    <p>{{ Introduction }}</p>
                    <button><a>Explore The Menu</a>
                    </button>
                </div>
            </section>
        </div>

        <!-- here goes navigation menu -->
        <div class="my_nav-container">
            <nav>
                <ul>
                    <li v-for="item in menuNavigation" :key="item"><a href="">{{ item }} </a></li>
                    <li> <a><i class="fa-solid fa-cart-shopping"></i></a>
                    </li>

                </ul>
            </nav>

            <!-- position absolute for two elements -->
            <div class="demos">
                <i class="fa-solid fa-book"></i>
                <span>Demos</span>
            </div>
            <div class="on_sale">
                <p>$ 39</p>
                <span>On sale</span>
            </div>


        </div>

    </div>
</template>

<style lang="scss" scoped>

// main container of header
.my_header-container {
    background-color: #030303;
    width: 100%;
    min-height: 600px;
    display: flex;
    justify-content: space-between;
    position: absolute;

    //   logo and content style
    .my_logo-content {
        padding: 1.3rem 4rem;
        width: 45%;

       hr {
        width: 7%;
        position: relative;
        top: 27.5%;
        left: 4%;
       }

        // content with paragraphs and main title 
        .content {
            padding-top: 5rem;
            width: 70%;
            margin: 0 auto;



            h1 {
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
                margin-top: 2rem;
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






    // navigation style
    .my_nav-container {
          
       


        // background image taken from webb

        background-image: url(https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/549e9b77-4c90-4c7f-8d0e-772a4ba70576/detu7o7-2822eeb6-d3ae-4744-a868-ade51aaae2f9.jpg/v1/fit/w_828,h_466,q_70,strp/restaurant_interior_sunset_version_by_arsenixc_detu7o7-414w-2x.jpg?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7ImhlaWdodCI6Ijw9MTQwNiIsInBhdGgiOiJcL2ZcLzU0OWU5Yjc3LTRjOTAtNGM3Zi04ZDBlLTc3MmE0YmE3MDU3NlwvZGV0dTdvNy0yODIyZWViNi1kM2FlLTQ3NDQtYTg2OC1hZGU1MWFhYWUyZjkuanBnIiwid2lkdGgiOiI8PTI1MDAifV1dLCJhdWQiOlsidXJuOnNlcnZpY2U6aW1hZ2Uub3BlcmF0aW9ucyJdfQ.almAXwER8I6AeytonXWuxNS5ir-AigObrdYJgnlMB5k);
        background-size: cover;
        margin: 0 auto;
        width: 55%;

    //    list of menu in unordered list
        ul {
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: .8rem;
            gap: 2rem;
            padding-top: 2.6rem;

            li {
                list-style-type: none;
            }

            a {
                color: #bcbcbc;
                text-decoration: none;

                // hover on anchor tag

                &:hover {
                    color: #ffff;
                    padding: .5rem;
                    border-radius: 10px;
                    transition: all 2s;
                }
            }
        }

    }

    .demos {
        width: 50px;
        height: 50px;
        padding: .2rem;
        text-align: center;
        background-color: #ffff;
        color: rgb(2, 2, 37);
        border-radius: 5px;
        position: relative;
        left: 93%;
        top: 8%;
        span {
            font-size: .6rem;
        }
        i{
            font-size: 1.4rem;
        }
    }
    .on_sale {
        width: 50px;
        height: 50px;
        padding: .2rem;
        text-align: center;
        background-color: #ffff;
        color: rgb(2, 2, 37);
        border-radius: 5px;
        position: relative;
        left: 93%;
        top: 9%;
        

        p {
            color: rgb(106, 211, 106);
            font-weight: bold;
            font-size: 1.2rem;
        }
        span {
            font-size: .6rem;
        }

        
    }
}
</style>