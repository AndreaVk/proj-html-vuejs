<template>
    <nav class="nav-bar">
        <ul class="nav-bar__list col-8">
            <li class="nav-bar__item">
                <a href="#Home">Home</a>
            </li>
            <li class="nav-bar__item">
                <a href="#Courses">Courses</a>
            </li>
            <li class="nav-bar__item">
                <a href="#Instructors">Instructors</a>
            </li>
            <li class="nav-bar__item">
                <a href="#Events">Events</a>
            </li>
            <li class="nav-bar__item">
                <a href="#Pages">Pages</a>
            </li>
            <li class="nav-bar__item">
                <a href="#Elements">Elements</a>
            </li>
        </ul>
        
    </nav>
</template>

<script>
export default {
    name:'NavBar',
}
</script>

<style lang="scss" scoped>
.nav-bar {
    font-size: 18px;
    // .nav-bar__list
    &__list {
        display: flex;
        list-style: none;
        align-items: center;
        justify-content: space-between;
    }
    // .nav-bar__item
    &__item {
        margin-left: 55px;
        margin-top: 35px;
        a {
            color: white;
            text-decoration: none;
        }
    }
}
</style>