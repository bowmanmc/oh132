<template>
<div id="App">
    <Header />
</div>
</template>

<script>
import Header from './components/Header.vue';

export default {
    name: 'App',
    components: {
        Header,
    },
};
</script>

<style lang="scss">
@import 'defaults/base';
</style>
