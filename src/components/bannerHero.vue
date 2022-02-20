<template>
    <div class="jumbo-img">
        <div class="jumbo-txt">
        </div>
    </div>
</template>


<script>
    export default {
  name: 'bannerHero'
}
</script>


<style scoped>
   .jumbo-img {
       margin: auto;
       background-size: contain;
       width: 80%;
       background-repeat: no-repeat;
       background-image: url('https://upload.wikimedia.org/wikipedia/commons/thumb/b/b9/Marvel_Logo.svg/1920px-Marvel_Logo.svg.png');
       background-position: center;
       display: flex;
       justify-content: center;
       align-items: center;
   }
   .jumbo-txt {
       margin: 80px;
       color: #fff;
       font-family: sans-serif;
       font-size: 20px;
       text-align: center;
   }
   .jumbo-txt h1 {
       font-size: 100px;
       margin-bottom: 10px;
   }
</style>