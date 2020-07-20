<template>
  <div class="serve-name">
      <p class="title">Servidor teste</p>
      <span class="icon">^</span>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.serve-name{
    grid-area:sn;

    display:flex;
    align-items: center;
    justify-content: space-between;

    padding: 0 11px 0 16px;
    background-color: var(--secondary);

    box-shadow: rgba(0, 0, 0, 0.2) 0px 1px 0px 0px;
    z-index: 2;
}
.title{
    
    font-size:16px;
    font-weight: bold;
    color:var(--white)
}
.icon{
    width:28px;
    height: 28px;
    color: var(--white);
    cursor: pointer;
    font-size: 30px;
}

</style>