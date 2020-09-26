<template>
    <div>
        <img src="../assets/spotify-transp-white-1.png" >
        <div class="level">
            <div class="level-item has-text-centered " :class="{'has-text-white':active1}" v-on:mouseover="active1 = true" @mouseleave="active1=false">
                <ion-icon name="home"></ion-icon>
                <p class="has-text-weight-semibold is-size-5">Home</p>
            </div>
        </div>

        <div class="level">
            <div class="level-item has-text-centered" :class="{'has-text-white':active2}" v-on:mouseover="active2 = true" @mouseleave="active2=false">
                <ion-icon name="browsers"></ion-icon>
                <p class="has-text-weight-semibold is-size-5">Browse</p>
            </div>
        </div>

        <div class="level">
            <div class="level-item has-text-centered" :class="{'has-text-white':active3}" v-on:mouseover="active3 = true" @mouseleave="active3=false">
                <ion-icon name="radio-outline" ></ion-icon>
                <p class="has-text-weight-semibold is-size-5">Radio</p>
                
            </div>
        </div>
            
        
    </div>
</template>

<script>
export default {
    name: "SideNavbar",
    data() {
        return {
            active1: false,
            active2: false,
            active3: false
        }
    }
}
</script>

<style scoped>
    
    .level {
        color: gray;
    }

    p {
        margin-left: 10px;
    }

    ion-icon {
        size: 64px;
    }

    .highlight {
        text-decoration-line: line-through;
    }
</style>