<template>
    <div class="wrapper-content wrapper-content--fixed">
      <section>
        <div class="container">
          <h1 class="title">Page not found!</h1>
          <img src="../assets/404.png" alt=""> 
          <p>Go to <router-link class="link" to="/">main page?</router-link></p>
        </div>
      </section>
    </div>
</template>

<style lang="scss" scoped>
    .wrapper-content{
        min-height: 80vh;
        display: flex;
        align-items: center;
        justify-content: center;
    }
    h1{
        text-align: center;
    }
    p{
        padding-top: 30px;
        text-align: center;
    }
</style>