<template>
    <div>
        Usuario:<p>Ba</p>
        <span v-show="login">(Identificado)</span>
        <span v-show="!login">(No Identificado)</span>
    </div>
</template>
<script>
    export default{
        name:"App",
        data(){
            return{
                login:true
            }
        }
    }
</script>