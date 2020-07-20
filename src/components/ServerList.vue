<template>
  <div class="server-list">

    <ServeButton />

  </div>
</template>

<script>
import ServeButton from './ServeButton'

export default {
    components:{
        ServeButton
    }
}
</script>

<style scoped>
.server-list{
    grid-area: sl;

    display:flex;
    flex-direction: column;
    align-items: center;

    background-color: var(--tertiary); 
    padding: 10px 0;

    max-height: 100vh;
    overflow-y: scroll;   

    scrollbar-width: none; /* deixar none a barra de rolagem  para farefox*/
    
}
/* não vai aparecer a barra de rolagem. Depende do navegador
nesse caso só serve para alguns navegadores */

::-webkit-scrollbar{ /* deixar none a barra de rolagem  para chrome*/
    display:none;
}


</style>