<template>
    <div>
        <h1>Frutas:</h1>
        <p>{{frutas}}</p>
        <ul>
            <li :v-for="fruta in frutas">{{fruta}}</li>
        </ul>
    </div>
</template>
<script>
    export default{
        name:"App",
        data(){
            frutas:['Manzan','Pera','Sandia','Melon']
        }
    }
</script>