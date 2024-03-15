<template>
        <section class="hero__section">
            <h5 class="sub__title">Online training</h5>
        <h1 class="hero__title">25K+ STUDENTS TRUST US</h1>
        <h4 class="title">Our goal is to make online education work for everyone</h4>
        <div class="hero__btn">
            <a class="hero__btn--left" href="#Hero">Get Qoute Now</a>
            <a class="hero__btn--right" href="#Hero">Lern More</a>
        </div>
        </section>
</template>

<script>
export default {
    name: 'HeroComponent'
}
</script>

<style>
.sub__title {
    padding-top: 1.5rem;
    padding-bottom: 0.5rem;
    font-style: normal;
    font-weight: 600;
    font-size: 14px;
    line-height: 24px;
    letter-spacing: 0.1px;
    color: #ffffff;;
}

.hero__title {
    font-style: normal;
    font-weight: 700;
    letter-spacing: 0.2px;
    color: #ffffff;
    max-width: 542px;
    font-size: 50px;
    line-height: 60px;
    padding-bottom: 0.5rem;
}
.title {
    font-style: normal;
    font-weight: 400;
    font-size: 18px;
    line-height: 25px;
    letter-spacing: 0;
    color: #ffffff;
    max-width: 408px;
    padding-bottom: 0.5rem;
}

.hero__btn {
    margin-top: 3rem;
}

.hero__btn--left {
    text-decoration: none;
    font-style: normal;
    font-weight: 700;
    font-size: 14px;
    line-height: 22px;
    text-align: center;
    letter-spacing: 0.2px;
    color: #ffffff;
    padding: 10px 20px;
    border-radius: 5px;
    background-color: #8d5cf6;
    transition: all 0.3s ease;
}

.hero__btn--left:hover {
    color: #ffffff;
    background-color: #422a75;
}

.hero__btn--right {
text-decoration: none;
    font-style: normal;
    font-weight: 700;
    font-size: 14px;
    line-height: 22px;
    text-align: center;
    letter-spacing: 0.2px;
    color: #ffffff;
    padding: 10px 20px;
    border-radius: 5px;
    border: 1px solid #ececec;
    transition: all 0.3s ease;
    margin-left: 4px;
}

.hero__btn--right:hover {
    border: 1px solid #707070;
    background-color: #707070;
    color: #ffffff;
}
</style>