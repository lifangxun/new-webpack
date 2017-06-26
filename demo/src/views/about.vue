<template>
    <div>
        <div>
            这是{{page}}页面
        </div>
    </div>
</template>
<style lang="less">
    div {
        background: yellow;
    }
</style>
<script>
    //require('./about.css');
    require('./about.less');
    export default{
        data(){
            return {
                page: 'about'
            }
        },
        components:{
        }
    }
</script>
