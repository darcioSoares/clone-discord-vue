<template>
  <div class="channel-info">
      <span class="HashtagIcon">#</span>
      <h2 class="title">Chat-livre</h2>
      <span class="separator"></span>
      <h2 class="description">Canal aberto para conversas</h2>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.channel-info{
    grid-area: ci;
    
    display:flex;
    align-items: center;

    padding: 0 17px;
    background-color: var(--primary);
    box-shadow: rgba(0,0,0, 0.2) 0px 1px 0px 0px;
    z-index:2;

}
.HashtagIcon{
    width: 24px;
    height: 24px;

    color:var(--symbol)
}
.title{
    margin-left:9px;
    font-size: 16px;
    font-weight: bold;
    color: var(--white)
}
.separator{
    height: 24px;
    width: 2px;

    background-color: var(--white);
    opacity: 0.2;    
    margin: 0 13px;

}
.description{
    font-size: 15px;
    color:var(--gray);
}

</style>