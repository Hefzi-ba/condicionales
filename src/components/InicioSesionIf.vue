<template>
<hr/> 
    <div>
        Usuario:<P>Otro Usuario</P>
        <span v-if="login">(Identificado)</span>
        <span v-else>(No Identificado)</span>
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
