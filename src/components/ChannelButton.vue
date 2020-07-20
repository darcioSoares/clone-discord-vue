<template>
  <div class="channel-button">
      <div>
          <span>#</span>
          <span class="chat">chat-livre</span>
      </div>
      <div >
          <span class="hashtag">##</span>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
    .channel-button{
        display:flex;
        align-items: center;
        justify-content: space-between;

        cursor:pointer;

        padding: 5px 3px;
        border-radius: 5px;

        background-color: transparent;
        transition: background-color 0.2s;
        
    }

    .channel-button:hover{
        background-color:var(--quinary);
        color:var(--white);  
        
    }   

    div{
        display:flex;
        align-items: center;
    }
        

</style>