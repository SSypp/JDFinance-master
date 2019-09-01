<template>
    <!-- //vue中的动态绑定样式的方法 -->
    <div :class="[btnClass,cname]">
        <!-- 插槽的使用 -->
        <slot />
    </div>
</template>
<script>
export default {
    props:{
        cname:{
            type:String,
            default:''
        }
    },
    data() {
        return {
            btnClass:'btn'
        }
    },
}
</script>
<style lang="scss">
@import './../../css/element.scss';
.btn{
     @include btn;
    }
</style>