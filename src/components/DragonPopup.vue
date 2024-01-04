<script setup>
</script>
<template>
    <img class="fix" src="/src/assets/dragon_face.png" alt="">
</template>

<style scoped>
@media only screen and (max-width: 1600px) {
  .fix {
    display: none;
  }
}
.fix{
    position:fixed;
    bottom:-291px;
    left:50%;
    transition: transform 1s;
}
.fix:hover{
    transform: translateY(-260px);
    transition: transform 1s;

}
</style>
