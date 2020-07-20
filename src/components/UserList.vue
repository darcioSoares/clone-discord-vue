<template>
  <div class="user-list">
        <p class="status">Disponivel 1</p>
        <p class="user"><strong>Jon Cat</strong></p>
        <p class="status">offline 15</p>

        <div class="userOnlines">
            <span class="avatar"></span>            
            <span class="user"><strong>Joaozinho joaquim de assis</strong></span>
            <span class="user"><strong>Mariazinha Correia de assis</strong></span>
            <span class="user"><strong>Fulano dos santos</strong></span>
            <span class="user"><strong>Fulano dos santos</strong></span>
            <span class="user"><strong>Fulano dos santos</strong></span>
            <span class="user"><strong>Fulano dos santos</strong></span>
            <span class="user"><strong>Fulano dos santos</strong></span>
            <span class="user"><strong>Fulano dos santos</strong></span>
            <span class="user"><strong>Fulano dos santos</strong></span>
            <span class="user"><strong>Fulano dos santos</strong></span>
            <span class="user"><strong>Fulano dos santos</strong></span>
            <span class="user"><strong>Fulano dos santos</strong></span>
            <span class="user"><strong>Fulano dos santos</strong></span>
            <span class="user"><strong>Fulano dos santos</strong></span>
            <span class="user"><strong>Fulano dos santos</strong></span>
            <span class="user"><strong>Fulano dos santos</strong></span>
            <span class="user"><strong>Fulano dos santos</strong></span>
            <span class="user"><strong>Fulano dos santos</strong></span>
            <span class="user"><strong>Fulano dos santos</strong></span>
            <span class="user"><strong>Fulano dos santos</strong></span>
            <span class="user"><strong>Fulano dos santos</strong></span>
            <span class="user"><strong>Fulano dos santos</strong></span>
            <span class="user"><strong>Fulano dos santos</strong></span>
            <span class="user"><strong>Fulano dos santos</strong></span>
            <span class="user"><strong>Fulano dos santos</strong></span>
            <span class="user"><strong>Fulano dos santos</strong></span>
            <span class="user"><strong>Fulano dos santos</strong></span>
            <span class="user"><strong>Fulano dos santos</strong></span>
            <span class="user"><strong>Fulano dos santos</strong></span>
            <span class="user"><strong>Fulano dos santos</strong></span>
            <span class="user"><strong>Fulano dos santos</strong></span>
            <span class="user"><strong>Fulano dos santos</strong></span>
           
        </div>
        
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.user-list{
    grid-area:ul;

    display:flex;
    flex-direction: column;

    max-height: calc(100vh - 46px);
    overflow: scroll;

    padding: 3px 6px 0 16px;
    background-color: var(--secondary);
    
    overflow-y: scroll;   
    scrollbar-width: none; /* deixar none a barra de rolagem  para farefox*/  
}

::-webkit-scrollbar{
    width: 4px;
}

::-webkit-scrollbar-trumb{
    background-color:var(--tertiary);
    border-radius:4px;
}

::-webkit-scrollbar-track{
    background-color: var(--secondary)
}
.status{
    margin-top:20px;

    text-transform: uppercase;
    font-size:12px;
    font-weight: 500;
    color: var(--gray);

}
.user{
    display: flex;
    align-items: center;

    margin-top: 5px;
    padding: 5px;

    cursor: pointer;
    border-radius:4px;

    background:transparent;
    transition:background 0.2s;
}
.user:hover{
    background: rgba(255,255,255, 0.1);
}
strong{
    margin-left: 13px;
    font-weight:500;
    color:var(--white);
    opacity: 0.7;

    white-space: nowrap;    
    text-overflow: ellipsis; /*se texto der overflow add ... */
    overflow: hidden;
    
}

.avatar{
    flex-shrink: 0;
    width: 36px;
    height: 36px;

    background-color:var(--primary);
    border-radius:50px;
}

</style>