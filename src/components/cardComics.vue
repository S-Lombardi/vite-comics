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
    <div class="comic-content">
        <!-- Immagine fumetto -->
        <img :src="image" alt="">
        <!-- Titolo serie fumetto -->
        <div class="comic-title">
            {{title}}
        </div>
    </div>
</template>


<style lang="scss" scoped>
@use '../styles/partials/variables' as *;

.comic-title{
    color: white;
    text-transform: uppercase;
    font-size: 12px;
    font-family: $font_family;
}


img{
    aspect-ratio: 3/4;
    object-fit:cover;
}

 
</style>