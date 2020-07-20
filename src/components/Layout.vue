<template>
<div class="layout">

<ServerList />
<ServerName />
<ChannelInfo />
<ChannelList />
<UserInfo />
<UserList />
<ChannelData />

</div>
  
</template>

<script>
import ServerList from './ServerList'
import ServerName from './ServeName'
import ChannelInfo from './ChannelInfo'
import ChannelList from './ChannelList'
import UserInfo from './UserInfo'
import UserList from './UserList'
import ChannelData from './ChannelData'

export default {
    components:{
        ServerList,
        ServerName,
        ChannelInfo,
        ChannelList,
        UserInfo,
        UserList,
        ChannelData
    }
}
</script>

<style scoped>
.layout{
    height: 100vh;
/* 
sl - server list
sn - server name
cl - channel list
cd - channel data
ui - user info
ul - user list
*/
display:grid;
grid-template-columns: 71px 240px auto 240px;
grid-template-rows: 46px auto 52px;
grid-template-areas: 
'sl sn ci ci'
'sl cl cd ul'
'sl ui cd ul';
}

</style>