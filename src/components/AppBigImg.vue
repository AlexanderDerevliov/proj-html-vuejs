<script>

export default {
    data() {
        return{
            dish: "KUNG PAD CHICKEN - $32"

        }
    }
}
</script>


<template>
        <div class="background-img">
            <div class="text">
                <p>{{ dish }}</p>
            </div>
        </div>
</template>

<style lang="scss" scoped>

.background-img {
    width: 100%;
    margin: 5rem 0;
    min-height: 500px;
    display: flex;
    justify-content: center;
    background-size: cover;
    background-image: url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRnenKLS4ypqt_EoGmsd1YqD923Cvg4u4wtBg&usqp=CAU);

    .text {
        color: #ffff;
        font-size: 1rem;
        align-self: end;
        padding-bottom: 2rem;

    }
}




</style>


