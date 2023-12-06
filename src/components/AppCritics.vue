<script>
export default {
    data() {
        return {
            Title: "NEW YORK TIMES",
            Introduction: "Ducimus, libero exercitationem voluptates corrupti similique ipsum accusamus nesciunt nihil? A quis perspiciatis autem praesentium omnis voluptatem earum temporibus similique ullam tempore."
        }
    }
}
</script>

<template>
    <div class="my_container">

        <p><em>What Critics are saying about us</em></p>

        <div class="container-up">

            <!-- rightside background img -->
            <div class="leftside"></div>

            <!-- rightside content text -->
            <div class="rightside">

                <!-- content -->
                <div class="content">

                    <!-- text inside -->
                    <span>MEGGY STEWART </span>
                    <h2>{{ Title }}</h2>
                    <div class="stars">
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                    </div>

                    <hr>
                    <p>{{ Introduction }}</p>
                    <button><a>READ FULL ARTICLE</a>
                    </button>

                </div>

            </div>
        </div>

        <div class="container-down">

            <div class="col-left">
                <div class="content">
                    <span>MERY MAXEY</span>
                    <h2>THE GUARDIAN</h2>
                    <div class="stars">
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                    </div>

                    <hr>
                    <p>{{ Introduction }}</p>
                    <button><a>READ FULL ARTICLE</a>
                    </button>


                </div>
            </div>
            <div class="col-right">
                <div class="content">
                    <span>PATRICK MONROE</span>
                    <h2>GLOBE AND MAIL</h2>
                    <div class="stars">
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                    </div>

                    <hr>
                    <p>{{ Introduction }}</p>
                    <button><a>READ FULL ARTICLE</a>
                    </button>


                </div>
            </div>

        </div>

    </div>
</template>

<style lang="scss" scoped>
.my_container {
    width: 65%;
    margin: 0 auto;
    padding-top: 4rem;
    text-align: center;

    .stars {
        display: flex;
        color: #ffff;
        gap: .4rem;
    }

    p {
        font-size: 1.4rem;
    }

    .container-up {
        width: 100%;
        margin-top: 3rem;
        display: flex;
        min-height: 400px;

        .leftside {
            width: 50%;
            background-image: url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSZwp3fFZi5jxOantLXaZAJ9LAPyGgtmKAxCA&usqp=CAU);
            background-size: cover;
        }



        .rightside {
            padding: 4rem 6rem;
            width: 50%;
            background-color: #030303;
            text-align: left;
            transition: transform .8s;

            &:hover {
                transform: scale(1.2);


            }


            hr {
                width: 15%;
                margin: 2rem 0;
                // border: 1px solid #ffff;
                color: #ffff;
            }

            h2 {
                color: #ffff;
                margin: 2rem 0;
                font-size: 2rem;
            }

            p {
                color: #bcbcbc;
                line-height: 1.5rem;
                font-size: 1.2rem;

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

    // ended upper row

    // container downside 

    .container-down {
        width: 100%;
        min-height: 500px;
        margin-top: 2rem;
        display: flex;
        text-align: left;
        gap: 2rem;


        hr {
            width: 15%;
            margin: 2rem 0;
            // border: 1px solid #ffff;
            color: #ffff;

        }

        h2 {
            color: #ffff;
            margin: 2rem 0;
            font-size: 2rem;

        }

        p {
            color: #bcbcbc;
            line-height: 1.5rem;
            font-size: 1.2rem;

        }

        span {
            color: #bcbcbc;
            font-size: .8rem;

        }

        button {
            padding: .6rem 2rem;
            margin-top: 3rem;
            color: #ffff;
            background-color: #03030300;
            border-color: #ffff;

            // hover on button header
            &:hover {
                background-color: #ffff;
                color: #030303;
                transition: all 1.3s;
            }
        }

    }


    .col-left {
        width: 50%;
        background-image: url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcShzz_ehjH_arfiaJHMm4TFyazKReodNchzPw&usqp=CAU);
        background-size: cover;
        padding: 4rem;
        transition: transform 1s;
        box-shadow: inset #03030393 0px 700px 0px 0px;

        &:hover {
            transform: scale(1.2);



        }


    }


    .col-right {
        width: 50%;
        background-image: url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSIrs8UlUP1W17POStfE3f4JSauXNZcpoOhdg&usqp=CAU);
        background-size: cover;
        padding: 4rem;
        transition: transform .8s;
        box-shadow: inset #03030393 0px 700px 0px 0px;
        &:hover {
            transform: scale(1.2);


        }


    }
}
</style>