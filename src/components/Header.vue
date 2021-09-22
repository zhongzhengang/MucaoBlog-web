<template>
    <div class="navbar">
        <div class="container">
            <div>
                <a href="/mucao-blog" style="font-size:23px">mucao</a>
            </div>
            <div class="navbar-menu">
                <div class="navbar-start">
                    <a class="navbar-item" href="/mucao-blog">首页</a>
                    <a class="navbar-item" href="/mucao-blog/archives">归档</a>
                    <a class="navbar-item" href="/mucao-blog/categories">分类</a>
                    <a class="navbar-item" href="/mucao-blog/tags">标签</a>
                    <a class="navbar-item" href="/mucao-blog/about">关于</a>
                </div>
                <div class="navbar-end">
                    <a class="navbar-item" href="https://github.com">讨论</a>
                    <a class="navbar-item" href="https://github.com">下载</a>
                    <a class="navbar-item" href="https://github.com">搜索</a>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Header'
    }
</script>

<style scoped>
    .navbar .container {
        display: flex;
        margin-left: 10%;
        margin-right: 10%;
    }

    .navbar-menu {
        display: flex;
        width: 100%;
        font-size: 20px;
    }

    .navbar-start {
        margin-left: 20px;
    }

    .navbar-end {
        margin-left: 70%;
    }

    .navbar-item {
        margin-left: 5px;
        margin-right: 5px;
    }

</style>
