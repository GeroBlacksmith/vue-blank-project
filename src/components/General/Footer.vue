<template lang="pug">
    .footer
        #footer
            ul 
                li Telefono: -- TELEFONO --
                li Email: -- EMAIL --
                li Direccion: -- DIRECCION --
</template>
<script>
    export default {
        name:"footer",
    }
</script>
<style lang="scss">
    #footer{
        background:black;
        color:white;
        ul{
            display:flex;
            flex-direction: column;
            align-items: flex-start;
            margin-left:20px;
            li{
                list-style: none;
                margin:10px 0;
            }
        }
    }
</style>