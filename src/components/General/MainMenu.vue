<template lang="pug">
    .mainmenu
        #mainmenu
            nav
                ul
                    li  
                        router-link(:to="{ name: 'Home', path: '/' }") Home
                    li  
                        router-link(:to="{ name: 'About', path: '/about' }") About
                    li  
                        router-link(:to="{ name: 'Contact', path: '/contact' }") Contact
</template>
<script>
    export default {
        name:'MainMenu',
    }
</script>
<style lang="scss">
    #mainmenu{
        background:black;
        color:white;
        nav{
            ul{
                display: flex;
                padding:10px 0;
                li{
                    list-style: none;
                    margin:0 20px;
                    a{
                        text-decoration: none;
                        color:white;
                        &:hover{
                            color:red;
                        }
                    }
                }
            }
        }
    }
</style>