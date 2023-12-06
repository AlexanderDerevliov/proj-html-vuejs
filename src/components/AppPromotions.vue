<script>
export default {
    data() {
        return {

            admin: "By Admin | 7th January 2020 | Category: News "

        }
    }
}
</script>


<template>
    <div class="container">
        <h2><em>Latest News & Promotions</em>
        </h2>

        <div class="row">
            <div class="col">
                <div class="card">
                    <div class="card-img">
                        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSuTurchhT1Tu6DyPUvEVobY6aiNYAPajdNSA&usqp=CAU" alt="immage of coofee">
                    </div>

                    <div class="card-text">
                        <h3>THE BEST COFFEE IN TOWN</h3>

                        <p>{{ admin }}</p>
                    </div>

                </div>
            </div>
            <div class="col">
                <div class="card">
                    <div class="card-img">
                        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSZwp3fFZi5jxOantLXaZAJ9LAPyGgtmKAxCA&usqp=CAU" alt="immage of chef">
                    </div>

                    <div class="card-text">
                        <h3>DISCOVER OUR NEW MENU</h3>
                        <p>{{ admin }}</p>

                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card-img">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSTIdz4bY31Rc78_m5NxJC09yOmW_wpzSE7Hg&usqp=CAU" alt="card payments">
                </div>

                <div class="card-text">
                    <h3>WE NOW ACCEPT SQUARE!</h3>
                    <p>{{ admin }}</p>

                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.container {
    width: 100%;
    padding: 3rem 0;
    text-align: center;

    h2{
        font-size: 1.8rem;
    }

    .row {
        width: 90%;
        margin: 5rem auto;
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 2rem;

        .col {
            width: calc(80% / 3 - 2rem);
            transition: transform 1s;

            &:hover {
                transform: scale(1.2);
               
                
            }

            .card-img {
                img {
                    width: 100%;
                    height: 500px;
                }
                
            }

            .card-text {
                padding: 2rem 0;

                p {
                    margin: 1rem 0;
                    font-size: .8rem;
                    color: #bcbcbc ;
                }
            }
        }

    }

}
</style>