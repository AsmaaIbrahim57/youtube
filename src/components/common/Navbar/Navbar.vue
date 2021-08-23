<template>
    <nav class="main-nav main-padding">
        <a class="logo" href="/">
            <img class="desktop" src="/youtube.png">
            <img class="mobile" src="/youtube-mobile.png">
        </a>
        <section class="search-form">
            <input type="text" class=" font-xmd "/>
            <button class="btn cancel font-sm">
                <i class="fa fa-times"></i>
            </button>
            <button type="submit" class="btn search font-md ">
                <i class="fa fa-search"></i>
            </button>
        </section>
    </nav>
</template>

<script>
export default {
    name: 'Navbar'
}

</script>

<style lang='scss' >
@import './navbar.scss';

</style>