<script>
export default {
    data() {
        return {


        }
    }
}
</script>


<template>
    <div class="container">


        <div class="row">
            <div class="col">
                <div class="card">
                    <h3>HORS D'OEUVRES</h3>
                    <div class="text-menu">
                        <div class="item-price">
                            <h4>AHI SALMON NIGIRI</h4>
                            <p>$48</p>
                        </div>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>

                        <div class="item-price">
                            <h4>UMI MASU SALAD</h4>
                            <p>$21</p>
                        </div>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>

                        <div class="item-price">
                            <h4>TEMAKI WITH CRAB</h4>
                            <p>$32</p>
                        </div>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>

                        <div class="item-price">
                            <h4>CALIFORNIA ROLLS</h4>
                            <p>$22</p>
                        </div>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>

                    </div>

                </div>
            </div>
            <div class="col">
                <div class="card">
                    <h3>MAIN COURSE</h3>
                    <div class="text-menu">
                        <div class="item-price">
                            <h4>BRASED ABALONE</h4>
                            <p>$52</p>
                        </div>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>

                        <div class="item-price">
                            <h4>TWICE COOKED PORK</h4>
                            <p>$21</p>
                        </div>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>

                        <div class="item-price">
                            <h4>KUNF PAO CHICKEN</h4>
                            <p>$32</p>
                        </div>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>

                        <div class="item-price">
                            <h4>CHAR SIU & SUSHIS</h4>
                            <p>$48</p>
                        </div>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>

                    </div>
                </div>
            </div>

            <div class="col">
                <h3>DESSERTS</h3>

                <div class="text-menu">
                    <div class="item-price">
                        <h4>CHOCOLATE BALL CAKE</h4>
                        <p>$13</p>
                    </div>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>

                    <div class="item-price">
                        <h4>LIME PIE WITH CRUST</h4>
                        <p>$14</p>
                    </div>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>

                    <div class="item-price">
                        <h4>RASBERRY PEAR CAKE</h4>
                        <p>$18</p>
                    </div>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>

                    <div class="item-price">
                        <h4>CAFE' AU LAIT</h4>
                        <p>$6</p>
                    </div>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>

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

    .row {
        width: 90%;
        margin: 5rem auto;
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 1rem;

        .col {
            width: calc(100% / 3 - 2rem);
            transition: transform 2s;
            min-height: 600px;
            background-color: #dcdcdc;

            &:hover {
                transform: scale(1.2);
                background-image: url(../assets/img/misc22x.jpg);
                background-size: cover;
                box-shadow: inset #03030380 0px 700px 0px 0px;
                z-index: 1;
                color: #ffff;


            }

            h3 {
                padding-top: 3rem;
                font-size: 1.5rem;

            }

            .text-menu {
                padding: 3rem 4rem;
                text-align: start;

                .item-price {
                    display: flex;
                    justify-content: space-between;
                    align-items: center;
                    padding: 2rem 0;


                    p {
                        font-size: .8rem;
                    }

                    h4 {
                        font-size: 1.2rem;
                    }
                }
            }


        }

    }

}</style>