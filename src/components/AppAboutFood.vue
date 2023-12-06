<script>
export default {
    data(){
        return{
            title: "BRAISED ABALONE",
            text: "Voluptates tempore magni incidunt fuga eligendi, architecto excepturi sit.",


        }
    }
}
</script>


<template>
    <div class="container">
        <div class="card-container">
            <div class="content">
                    <h2>{{ title }}</h2>

                    <hr>
                    <p>{{ text }}</p>
                    <button><a>VIEW IN THE MENU</a>
                    </button>
 

                </div>

        </div>
    </div>

</template>

<style lang="scss" scoped>

.container {
    width: 100%;
    min-height: 600px;
    background-image: url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRunan8f8HZRbjpjOjlukgnz4TLQ1-c9UGFIg&usqp=CAU);
    background-size: cover;
    position: relative;

    .card-container {
        width: 300px;
        background-color: #030303;
        height: 360px;
        position: absolute;
        top: 14%;
        left: 13%;

       .content {
        padding: 2rem;
        color: #ffff;
        text-align: start;

        

        hr {
                width: 15%;
                margin: 2rem 0;
                // border: 1px solid #ffff;
                color: #ffff;
            }

            h2 {
                color: #ffff;
                margin: 1.5rem 0;
                font-size: 1.5rem;
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
}

</style>