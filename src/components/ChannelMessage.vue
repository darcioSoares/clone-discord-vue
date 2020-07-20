<template>
  <div class="message">
      <div>
          <div class="main">
              <span class="avatar"></span>
              <div class="sub">
                  <div>
                    <span class="author"><strong>Jon</strong></span>
                    <span class="date">21/06/2020</span>
                  </div>
                 <span class="content">
                     hello my friend
                 </span>
              </div>
          </div>

          <div class="main">
              <span class="avatar"></span>
              <div class="sub">
                  <div>
                    <span class="author"><strong>Mary</strong></span>
                    <span class="date">22/06/2020</span>
                  </div>
                 <span class="content">
                     Good morning
                 </span>
              </div>
          </div>

           <div class="main">
              <span class="avatar"></span>
              <div class="sub">
                  <div>
                    <span class="author"><strong>Maike</strong></span>
                    <span class="date">28/07/2020</span>
                  </div>
                 <span class="content">
                     Good night, my friend
                 </span>
              </div>
          </div>
          <div class="main">
              <span class="avatar"></span>
              <div class="sub">
                  <div>
                    <span class="author"><strong>Fulano</strong></span>
                    <span class="date">21/06/2020</span>
                  </div>
                 <span class="content">
                     hello my friend
                 </span>
              </div>
          </div>

          <div class="main">
              <span class="avatar"></span>
              <div class="sub">
                  <div>
                    <span class="author"><strong>Mary</strong></span>
                    <span class="date">22/06/2020</span>
                  </div>
                 <span class="content">
                     Good morning
                 </span>
              </div>
          </div>

           <div class="main">
              <span class="avatar"></span>
              <div class="sub">
                  <div>
                    <span class="author"><strong>Maike</strong></span>
                    <span class="date">28/07/2020</span>
                  </div>
                 <span class="content">
                     Good night, my friend
                 </span>
              </div>
          </div>
          <div class="main">
              <span class="avatar"></span>
              <div class="sub">
                  <div>
                    <span class="author"><strong>Fulano</strong></span>
                    <span class="date">21/06/2020</span>
                  </div>
                 <span class="content">
                     hello my friend
                 </span>
              </div>
          </div>

          <div class="main">
              <span class="avatar"></span>
              <div class="sub">
                  <div>
                    <span class="author"><strong>Fulano</strong></span>
                    <span class="date">22/06/2020</span>
                  </div>
                 <span class="content">
                     Good morning
                 </span>
              </div>
          </div>

           <div class="main">
              <span class="avatar"></span>
              <div class="sub">
                  <div>
                    <span class="author"><strong>Fulano</strong></span>
                    <span class="date">28/07/2020</span>
                  </div>
                 <span class="content">
                     Good night, my friend
                 </span>
              </div>
          </div>
          <div class="main">
              <span class="avatar"></span>
              <div class="sub">
                  <div>
                    <span class="author"><strong>Fulano</strong></span>
                    <span class="date">21/06/2020</span>
                  </div>
                 <span class="content">
                     hello my friend
                 </span>
              </div>
          </div>

          <div class="main">
              <span class="avatar"></span>
              <div class="sub">
                  <div>
                    <span class="author"><strong>Fulano</strong></span>
                    <span class="date">22/06/2020</span>
                  </div>
                 <span class="content">
                     Good morning
                 </span>
              </div>
          </div>

           <div class="main">
              <span class="avatar"></span>
              <div class="sub">
                  <div>
                    <span class="author"><strong>Fulano</strong></span>
                    <span class="date">28/07/2020</span>
                  </div>
                 <span class="content">
                     Good night, my friend
                 </span>
              </div>
          </div>
          
         
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
    .message{
        display: flex;
        align-items:center;

        padding: 4px 16px;
        margin-right: 4px;

       background-color: transparent;
        
    }
    .main{ 
        display: flex;
        align-items: center;
        padding: 2px;    
        margin-top:16px;    
    }
    strong{
        margin-left: 14px;
        color: var(--white);
        font-size:16px;
        
    }
    .content{
        margin-left:14px;
        text-align: left;
        color:var(--white);
        font-size:14px;
    }

    .avatar{
        width:40px;
        height:40px;

        background-color: var(--secondary);
        border-radius:50%;
    }
    .date{
        margin-left: 15px;
        color:var(--gray);
        font-size:13px;
    }
    .sub{
        display:flex;
        flex-direction: column;
    }
    
</style>