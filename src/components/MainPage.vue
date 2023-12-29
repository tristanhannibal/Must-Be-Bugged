<script setup>
</script>

<template>
    <div class="main-flex">
        <div class="flex-item">
            <h1>Must Be Bugged</h1>
            <p>Mal'Ganis</p>
        </div>
        <img class="logo flex-item" width="100px" height="100px" src="/src/assets/tabard.png" alt="">
    </div>
</template>

<style scoped>


h1{
    color:var(--color-heading);
    margin: 0.4rem;
}

p{
    font-size:1ch;
    align-self: center;
    float: right;
    margin-right: 30px;
}

.logo{
    max-width: 100%;
    height: auto;
}

.main-flex{
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
}

.flex-item + .flex-item { border-left: 0.5px solid white; }


</style>
