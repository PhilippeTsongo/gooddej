<template>
    <div class="restaurant--card">
        <div class="restaurant--image">

        </div>
        <div class="restaurant--information">
            <div class="top">
                <p class="name">Nom du restaurant</p>
                <p class="price">5$</p>
            </div>
            <p class="time">
                <span>25min - 35min</span>
            </p>
        </div>
    </div>
</template>

<script>
export default {
    name: "RestaurantCard",
}
</script>

<style lang="scss">
    .restaurant--card{
        width: 32%;
        height: 30vh;

        p{
            margin: 0px;
        }

        .restaurant--image{
            background-image: url('/public/img/Capture1.JPG');
            height: 70%;
            background-size: cover;
            background-position: center;
        }
        .restaurant--information{
            .top{
                margin: 10px 0px;
                display: flex;
                align-items: center  ;
                justify-content: space-between;

                .price{
                    background-color: #eeeeeeee;
                    display: flex;
                    height: 30px;
                    width: 30px;
                    justify-content: center;
                    align-items: center;
                    font-size: 0.8rem;
                    border-radius: 50%;
                }
            }
            .time{
                font-size: 0.8rem;
            }
        }
    }
</style>