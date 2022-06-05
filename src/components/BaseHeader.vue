<template>
<div class="container">
  <header class="header">
    <div class="header_logo">
        <img src="../assets/img/dc-logo.png" alt="">
    </div>
    <div class="header_nav">
        <ul>
         <li><a href="#"></a>CHARACTERS</li>
         <li class="active"><a href="#"></a>COMICS</li>
         <li><a href="#"></a>MOVIES</li>
         <li><a href="#"></a>TV</li>
         <li><a href="#"></a>GAMES</li>
         <li><a href="#"></a>COLLECTIBLES</li>
         <li><a href="#"></a>VIDEOS</li>
         <li><a href="#"></a>FANS</li>
         <li><a href="#"></a>NEWS</li>
         <li><a href="#"></a>SHOP</li>
        </ul>
    </div>
  </header>
</div>
</template>

<script>
export default {
name: 'BaseHeader',

}
</script>

<style lang="scss" scoped>
@import '../assets/style/mixins.scss';
.header {
    display: flex;
    justify-content: space-between;
    margin-top: 1.25rem;

    &_logo img {
        width: 4rem;
        height: 4rem;
        margin-bottom: .6125rem;
    }
    
    &_nav {
        display: flex;
        align-items: center;

        li {
            height: 100%;
            display: flex;
            align-items: center;
        }

        ul {
            @include listInline;
            column-gap: 1.875rem;
            font-size: .75rem;
            font-weight: bold;
            height: 100%;
            align-items: center;

            .active {
                color: var(--primary-color);
                border-bottom: solid 2px var(--primary-color);
            }
        }
    }
}
</style>