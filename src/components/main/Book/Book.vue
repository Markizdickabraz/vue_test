<template>
    <section class="book__section">
        <div class="book__container">
            <h2 class="book__title">Approdable Packages</h2>
            <p class="book__text">
                  Problems trying to resolve the conflict between the two major
                  realms of Classical physics: Newtonian mechanics
                </p>
                <div class="products__link--container">
                    <a class="products__link" href="#">Learn More<img src="@/assets/img/section-arrow_right.png" alt="img"></a>
                </div>

                <div class="book__img--container">
                    <a class="book__img--link" href="#"><img src="@/assets//img/section-video-button.png" alt="img"></a>
                </div>
        </div>
    </section>
</template>

<script>
export default {
name : 'BookComponent'

}
</script>

<style>
.book__section {
    padding-top: 80px;
    padding-bottom: 80px;
}

.book__title {
    font-style: normal;
    letter-spacing: 0.2px;
    color: #ffffff;
    padding-top: 3rem;
    padding-bottom: 3rem;
    font-size: calc(1.325rem + .9vw);
    font-weight: 500;
    line-height: 1.2;
}

.book__text {
    font-style: normal;
    font-weight: 400;
    font-size: 14px;
    line-height: 20px;
    letter-spacing: 0.2px;
    color: #ffffff;
    padding-bottom: 3rem;
}

.book__img--container {
    min-height: 363px;
    background: url('@/assets/img/section-books.jpg') center no-repeat;
    background-size: cover;
    border-radius: 25px;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
}

.book_img--link {
transition: all 0.3s linear;
}

.book_img--link:hover {
    transform: scale(1.1);
    filter: brightness(0.8);
    cursor: pointer;

}
</style>