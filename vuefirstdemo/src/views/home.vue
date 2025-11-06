<template>
    <div class="home-container">
        <h1>Vue3教学</h1>
        <hr>
        <Mobanyufa></Mobanyufa>
        <Shuxingbangding></Shuxingbangding>
        <Tiaojianxuanran></Tiaojianxuanran>
        <liebiaoxuanran></liebiaoxuanran>  
        <keyguanlizhuangtai></keyguanlizhuangtai> 
        <Shijianchuancan></Shijianchuancan>
        <Shijianxiushifu></Shijianxiushifu>
        <Shuzubianhuazhence></Shuzubianhuazhence>
        <Jisuanshuxing></Jisuanshuxing>
        <Classbangding></Classbangding>
        <Stylebangding></Stylebangding>
        <Watchzhenting></Watchzhenting>
    </div>
</template>


<script>
import Mobanyufa from '../components/mobanyufa.vue';
import Shuxingbangding from '../components/shuxingbangding.vue'
import Tiaojianxuanran from '../components/tiaojianxuanran.vue'
import liebiaoxuanran from '../components/liebiaoxuanran.vue';
import keyguanlizhuangtai from '../components/keyguanlizhuangtai.vue'
import Shijianchuancan from '../components/shijianchuancan.vue'
import Shijianxiushifu from '../components/shijianxiushifu.vue';
import Shuzubianhuazhence from '../components/shuzubianhuazhence.vue';
import Jisuanshuxing from '../components/jisuanshuxing.vue';
import Classbangding from '../components/classbangding.vue';
import Stylebangding from '../components/stylebangding.vue';
import Watchzhenting from '../components/watchzhenting.vue';

export default {
    name: 'home',
    components: {
        Mobanyufa,
        Shuxingbangding,
        Tiaojianxuanran,
        liebiaoxuanran,
        keyguanlizhuangtai,
        Shijianchuancan,
        Shijianxiushifu,
        Shuzubianhuazhence,
        Jisuanshuxing,
        Classbangding,
        Stylebangding,
        Watchzhenting

    },
}
</script>

<style scoped>
.home-container {
    position: relative;
    z-index: 10;
}

h1 {
    z-index: 11;
    color: aqua;
}

</style>