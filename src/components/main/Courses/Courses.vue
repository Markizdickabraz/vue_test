<template>
<section class="courses__section">
<div class="card__container">
    <img class="card-img-top" src="@/assets/img/vector-card_school_icon.svg" alt="school">
    <div class="card__body">
        <h4 class="card__title">2,769 online courses</h4>
        <div class="card__line"></div>
        <p class="card__text">
        The gradual accumulation of information about atomic and
        small-scale behaviour...
        </p>
    </div>
</div>
<div class="card__container">
    <img class="card-img-top" src="@/assets/img/vector-card_book_icon.svg" alt="school">
    <div class="card__body">
        <h4 class="card__title">Expert instruction</h4>
        <div class="card__line"></div>
        <p class="card__text">
        The gradual accumulation of information about atomic and
        small-scale behaviour...
        </p>
    </div>
</div>
<div class="card__container">
    <img class="card-img-top" src="@/assets/img/vector-card_character_icon.svg" alt="school">
    <div class="card__body">
        <h4 class="card__title">training Courses</h4>
        <div class="card__line"></div>
        <p class="card__text">
        The gradual accumulation of information about atomic and
        small-scale behaviour...
        </p>
    </div>
</div>
</section>
</template>

<script>
export default {
    name : 'CoursesComponent',
}
</script>

<style>
.courses__section {
    margin-top: 3rem;
    display: flex;
    gap: 10px;
    flex-direction: column;
}

.card__container {
    padding: 35px 40px;
    border-radius: 5px;
    overflow: hidden;
    filter: grayscale(0.5);
    transition: all 0.3s linear;
    background-color: #fff;
    }

    .card__container:hover {
        filter: grayscale(0);
    filter: brightness(1.05);
    transform: scale(1.05);
    box-shadow: 0 0 12px #ffffff;
    }

    .card__title {
    padding: 20px 0px;
    font-style: normal;
    font-weight: 700;
    font-size: 16px;
    line-height: 24px;
    letter-spacing: 0.1px;
    color: #252b42;
    }

    .card__line {
    width: 50px;
    height: 2px;
    background: #e74040;
    margin: 20px 0px;
    }

    .card__text {
    font-style: normal;
    font-weight: 400;
    font-size: 14px;
    line-height: 20px;
    letter-spacing: 0.2px;
    color: #737373;
    }
</style>