<script>

export default{
    data(){
        return{
            links:[
                {
                    label:'Characters',
                    link:'#',
                    active: false,
                },
                {
                    label:'Comics',
                    link:'#',
                    active: true,
                },
                {
                    label:'Movies',
                    link:'#',
                    active: false,
                },
                {
                    label:'Tv',
                    link:'#',
                    active: false,
                },
                {
                    label:'Games',
                    link:'#',
                    active: false,
                },
                {
                    label:'Collectibles',
                    link:'#',
                    active: false,
                },
                {
                    label:'Videos',
                    link:'#',
                    active: false,
                },
                {
                    label:'Fans',
                    link:'#',
                    active: false,
                },
                {
                    label:'News',
                    link:'#',
                    active: false,
                },
                {
                    label:'Shop',
                    link:'#',
                    active: false,
                },
            
            ]

        }
    }
}
</script>


<template>
    <header>
        <div class="container">
            <div class="row">
                <!-- LOGO DC -->
                <div class="col-left">
                    <img src="../../public/dc-logo.png" alt="">
                </div>
                <!-- LINK -->
                <div class="col-right">
                    <ul>
                        <li v-for="(link, index) in links" :key="index">
                            <a :class="link.active ? 'active' : ' ' " :href="link.link">{{ link.label }}</a>
                        </li>

                    </ul>
                
                </div>

            </div>
        </div>
    </header>
</template>


<style lang="scss" scoped>
@use '../styles/partials/variables' as *;
.active{
    color: $primary_color;
}
.row{
    justify-content: space-between;
}

ul{
    height: 100%;
    display: flex;
    align-items: center;

    li{
        margin-right: 20px;


        a{
            text-transform: uppercase;
            color: $gray_color;
            
            &:hover {
                color: rgb(131, 161, 184);
    
            }
            
        }
    }
}

</style>