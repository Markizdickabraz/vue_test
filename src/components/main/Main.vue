<template>
    <main class="main">
        <div class="container">
            <HeroComponent />
            <CoursesComponent />
            <ProductsComponent />
            <BookComponent />
        </div>
    </main>
</template>

<script>
import HeroComponent from '@/components/main/HeroComponent/Hero.vue';
import CoursesComponent from '@/components/main/Courses/Courses.vue';
import ProductsComponent from '@/components/main/Products/Products.vue';
import BookComponent from '@/components/main/Book/Book.vue';

export default {
    name: 'AppMain',
    components: {
        HeroComponent,
        CoursesComponent,
        ProductsComponent,
        BookComponent,
    }
}
</script>

<style>

.main {
    padding-top: 1rem;
}

.container {
    padding-left: 0.75rem;
    padding-right: 0.75rem;
}</style>