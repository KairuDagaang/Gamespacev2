<script setup>
import Homelayout from '@/Layouts/Homelayout.vue';
import { Head } from '@inertiajs/vue3';

</script>

<template>
    <Head title="Dashboard" />

    <Homelayout> 
        <main id="page-trans">
            <header class="welcome">Welcome  {{ $page.props.auth.user.name }}!</header>
            <img src="https://i.pinimg.com/originals/a0/50/34/a050342aa80f73199b7ff03eae27a316.gif" alt="">
        </main>
    </Homelayout>
</template>

<style scoped>
.welcome {
    text-align: center;
    margin-top: 15px;
    font-weight: bold;
    font-size: 25px;
    color: #4a90e2;
}
img {
    margin-top: 15px;
    border-radius: 50%;
    margin-left:320px;
}
</style>
