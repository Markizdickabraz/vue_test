<template>
    <div class="products__section" id="Product">
<div class="products__text--container">
    <div class="block__line"></div>
    <h2 class="products__title">
        Our Expert Teacher
    </h2>
    <p class="products__text">
                  Problems trying to resolve the conflict between the two major
                  realms of Classical physics: Newtonian mechanics
                </p>
                <div class="products__link--container">
                    <a class="products__link" href="#">Learn More<img src="@/assets/img/section-arrow_right.png" alt="img"></a>
                </div>
</div>

<div class="products__img--contaier">
<img class="products__img" src="@/assets/img/technology 1.png" alt="tehnology">
    </div>
    </div>
</template>

<script>
export default {
    name : 'ProductsContainer'
}
</script>

<style>
.products__section {
    padding-top: 80px;
    padding-bottom: 80px;
    display: flex;
    flex-direction: column;
}


.products__text--container{
padding-left: 20px;
}

.block__line {
    width: 94px;
    height: 7px;
    background: #e74040;
    border-radius: 5px;
}

.products__title {
    font-style: normal;
    font-weight: 700;
    font-size: 40px;
    line-height: 50px;
    letter-spacing: 0.2px;
    color: #ffffff;
    padding-top: 3rem;
    padding-bottom: 3rem;
    font-size: calc(1.325rem + .9vw);
}
.products__text {
    font-style: normal;
    font-weight: 400;
    font-size: 14px;
    line-height: 20px;
    letter-spacing: 0.2px;
    color: #ffffff;
    padding-bottom: 3rem;
}

.products__link {
    text-decoration: none;
    font-style: normal;
    font-weight: 700;
    font-size: 14px;
    line-height: 24px;
    letter-spacing: 0.2px;
    color: #8d5cf6;
    border-radius: 15px;
    padding: 10px 20px;
    transition: all 0.3s linear;
    margin-left: -20px;
}

.products__link:hover {
    color: #422a75;
    background-color: rgba(255, 255, 255, 0.628);
}

.products__link img {
    margin-left: 5px;
    vertical-align: middle;
}

.products__img{
    width: 100%;
}
</style>