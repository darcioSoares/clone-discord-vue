<template>
  <div class="button">
      
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.button{
    display: flex;
    align-self: center;
    justify-content: center;
    flex-shrink: 0; /* não pode ser complimido  contrario flex-grow*/ 
    
    width:48px;
    height: 48px;
    border-radius:50px;
    margin-bottom: 8px;

    background-color: var(--primary);
    cursor: pointer;       
    }

    .button:hover{
        border-radius: 16px;
        background-color: var(--discord);
    }

</style>