<template>
    <nav>
        <router-link to="/">Home</router-link>
        <router-link to="/about">About</router-link>
    </nav>
</template>
<script lang="ts">
import { Vue } from 'vue-class-component'
export default class HeaderComponent extends Vue {}
</script>
