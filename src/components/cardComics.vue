<script>
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

        CARD

    </div>
</template>

<style lang="scss">


    
</style>