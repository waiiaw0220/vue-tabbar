<template>

    <div>
        <slot></slot>    
    </div>

</template>




<script>
export default {
    name: "TabBar",
}
</script>




<style scoped>
#tab-bar {
  display: flex;
  background-color: #f6f6f6;

  /* 固定在下方 用fixed */
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;

  box-shadow: 0 -1px 10px rgba(100,100,100,0.2);
}

</style>
