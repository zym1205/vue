<template>
    <div class="shijianxiushifu">
        <h3>事件修饰符</h3>
        <a @click.prevent="click11" href="https://www.baidu.com">百度百度</a>
    </div>

</template>


<script>
export default {
    name:'shijianxiushifu',
    data() {
        return {
        }
    },
    methods: {
        click11(e) {
            console.log('点击了百度百度')
        },
        clickDiv() {
            console.log('点击了div')
        },
        clickP() {
            console.log('点击了p')
        }
    }
}
</script>

<style scoped>
.shijianxiushifu{
    color:blueviolet
}
</style>