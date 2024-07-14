<template>
    <div class="header">
        <div class="header_logo">
            <img src="../assets/logo.png">
            <span>Буш Мятный</span>
        </div>
        <nav class = "header_nav">
            <router-link to="/" class = "header_item">Home</router-link>
            <router-link to="/about" class = "header_item">About</router-link>
        </nav>
    </div>
</template>
<script lang="ts">
import { Vue } from 'vue-class-component'
export default class HeaderComponent extends Vue {}
</script>
<style lang="scss" scoped>
    .header{
        background-color: #e5bace;
        height: 100vh;
        padding: 10px;
        width: 200px;
    }
    .header_logo{
        display: flex;
        justify-content: center;
        align-items: center;
        font-weight: bold;
    }
    .header_logo>img{
        width: 20%;
    }
    .header_nav{
        padding: 0;
        .header_item {
            font-weight: bold;
            color: #ef0d50;
            display: block;
            padding: 10px 5px;
            &.router-link-exact-active {
                color: #ef0d50;
            }
        }
    }
</style>
