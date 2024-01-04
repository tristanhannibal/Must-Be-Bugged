<script setup>
</script>
<template>
    <div class="about-item">
      <h3>
        <slot name = title></slot>
      </h3>
      <div class="body">
        <slot name="body"></slot>
      </div>
      <div class="footer">
        <slot name="footer"></slot>
      </div>
    </div>
</template>

<style scoped>
  .about-item{
    max-width: 700px;
  }
  .body{
    line-height: 1.2;
  }

</style>
