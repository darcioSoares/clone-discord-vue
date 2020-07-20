<template>
  <div class="channel-data">
      <div class="messages">

         <ChannelMsg />

      </div>
        
      <div class="input-wrapper">
          <input id="inputDig" type="text" placeholder="@   Conversa em Chat-livre">
          <span class="input-icon"></span>
      </div>

  </div>
</template>

<script>
import ChannelMessage from './ChannelMessage'

export default {
    components:{
        ChannelMsg : ChannelMessage
    }
}
</script>

<style scoped>
    .channel-data{
        grid-area:cd;

        display: flex;
        flex-direction: column;
        justify-content: space-between;

        background-color:var(--primary)

    }

    .messages{
        padding: 20px 0;

        display: flex;
        flex-direction: column;

        max-height: calc(100vh - 46px - 68px);

        overflow-y: scroll;
    }
    ::-webkit-scrollbar{
        width:8px
    }
    ::-webkit-scrollbar-thumb{
        background-color: var(--tertiary);
        border-radius:4px
    }

    ::-webkit-scrollbar-track{
        background-color: var(--secondary)
    }

    .input-wrapper{
        width:100%;
        padding: 0 16px;
    }
    input{
        width:100%;
        height: 44px;

        padding: 0 10px 0 57px;
        border-radius:7px;
        color:var(--white);
        background-color:var(--chat-input);

        position:reletive;
    }

    ::placeholder{
        color:var(--gray);
        font-size: 20px;
    }

</style>