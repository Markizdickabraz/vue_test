<template>
    <main class="main">
        <div class="container">
            <HeroComponent />
            <CoursesComponent />
        </div>
    </main>
</template>

<script>
import HeroComponent from '@/components/main/HeroComponent/Hero.vue';
import CoursesComponent from '@/components/main/Courses/Courses.vue';

export default {
    name: 'AppMain',
    components: {
        HeroComponent,
        CoursesComponent,
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