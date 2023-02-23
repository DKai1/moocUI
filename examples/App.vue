<template>
    <div id="app">
        <img alt="Vue logo" src="./assets/logo.png">
        <Demo/>
        <m-card
                img-src="vue.png"
                summary="vue3.0实现todolist "
        />
        <br>

        <m-card
                img-src="vueJs.png"
                :width="370"
                :img-height="90"
        >
            路线专为想学Vue却无从下手的人群设计，以实际项目为例，逐层深入，学透Vue。
            <template v-slot:footer>
                <div class="bottom">
                    <p class="collect">· 4步骤 · 6门课</p>
                    <p class="collect">20111人收藏</p>
                </div>
            </template>
        </m-card>

        <br>
        <m-card
                img-src="vue.png"
                summary="vue3.0实现todolist "
        >
            <template v-slot:footer>
                <div class="footer">
                    <div class="level">进阶 · 16969人报名</div>
                    <div class="price">免费</div>
                </div>
            </template>
        </m-card>
    </div>
</template>

<script>

    export default {
        name: 'App',
    }
</script>

<style>
    #app {
        font-family: Avenir, Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
        margin-top: 60px;
    }

    .footer {
        float: left;
    }

    .level {
        font-size: 12px;
        color: #9199a1;
        line-height: 18px;
        padding: 0 8px;
        margin-bottom: 8px;
    }

    .price {
        float: left;
        font-size: 12px;
        color: #9199a1;
        line-height: 18px;
        padding: 0 8px;
        margin: 0;
    }

    .collect {
      margin: 0;
      padding: 0;
    }
    .bottom {
      padding: 0 10px;
      margin-bottom: 10px;
      font-size: 12px;
      color: #9199a1;
      display: -webkit-box;
      display: -ms-flexbox;
      display: -webkit-flex;
      display: flex;
      -webkit-box-pack: justify;
      -ms-flex-pack: justify;
      -webkit-justify-content: space-between;
      justify-content: space-between;
    }
</style>
