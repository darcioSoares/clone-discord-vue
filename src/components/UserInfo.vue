<template>
  <div class="user-info">
      <div class="profile">
          <span class="icon"></span>
          <div class="userData">
                <span>Joao</span>  
                <span>#2828</span>
          </div>
                  
      </div>
      <span>Icon</span>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.user-info{
    grid-area: ui;

    display: flex;
    align-items: center;
    justify-content: space-between;

    padding: 10px;

    background-color: var(--quaternary);
    box-shadow: rgba(0,0,0, 0.2) 0px  1px 0px 0px;

}
.profile{
    display:flex;
    align-items:center;

}
.profile > div{
    display: flex;
    flex-direction: column;
    margin-left: 4px;
}
.icon{
    width:32px;
    height: 32px;
    border-radius: 50%;

    background-color: var(--gray);
}
.userData span:nth-child(2){
    color:var(--white);
    font-size:12px
}

</style>