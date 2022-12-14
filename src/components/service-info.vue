<template>
    <div v-for="service in services">
        <div class="image">
            <img src="{{service.icon}}" alt="">
            {{imageSrc}}
            
        </div>
        <div class="title">
            <p>{{service.title}}</p>
        </div>
        <div class="txt">
            <p>{{service.text}}</p>
        </div>
        
    </div>
</template>
<script>
export default {
    
    name: 'service-info',
    props: {
        services: Array
    },
    created() {
        console.log('icon', this.imageSrc);
    }

}
</script>
<style>
    
</style>