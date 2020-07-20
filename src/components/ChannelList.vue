<template>
  <div class="channel-list">
      <div class="category">
          <span class="text">Canais de texto</span>
          <span class="icon">+</span>
      </div>

    <ChannelButton />
    <ChannelButton />
    <ChannelButton />
    <ChannelButton />

  </div>
</template>

<script>
import ChannelButton from './ChannelButton'

export default {
    components:{
        ChannelButton
    }

}
</script>

<style scoped>

.channel-list{
    grid-area: cl;
    
display:flex;
flex-direction: column;

padding: 24px 9.5px 0 16px;
background-color:var(--secondary)

}
.category{
    display:flex;

    align-items: center;
    justify-content: space-between;

    margin-bottom:6px;


}
.text{
    text-transform: uppercase;
    font-size:12px;
    font-weight: 500;
    color: var(--gray)

}
.icon{
    width:21px;
    height: 21px;

    color: var(--symbol);
    cursor: pointer;
}

</style>