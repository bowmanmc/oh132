<template>
<div class="Header">

</div>
</template>

<script>
export default {
    name: 'Header',
};
</script>

<style lang="scss">
@import "../defaults/colors";

.Header {
    background: $color-primary;
    background-blend-mode: multiply;
    background-image: url('/img/Ohio_Statehouse_3-bw.jpg');
    background-position: center center;
    background-repeat: no-repeat;
    background-size: cover;
    min-height: 83%;
}
</style>
