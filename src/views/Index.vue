<template>
    <div class='main'>
        <ul>
            <li class='item'>
                <router-link to='home'>
                    <div>VUE主页</div>
                </router-link>
            </li>
            <li class='item'>
                <router-link to='about'>
                    <div>关于</div>
                </router-link>
            </li>
        </ul>
    </div>
</template>

<script lang='ts'>
    import {Vue} from 'vue-property-decorator';

    export default class Index extends Vue {
    }
</script>

<style scoped lang='scss'>
    .main {
        font-size: 16px;
        color: deepskyblue;

        .item {
            padding: 10px;
        }
    }
</style>
