<script>

//Importo gli elementi che voglio visualizzare dell'array comics
//che si trova nella componente padre Main
export default {
    props:{
        image: String,
        title: String,
    }
}
</script>

<template lang="">
    <div>
        <img :src="image" alt="">
        {{title}}
    </div>
</template>

<style lang="scss">


    
</style>