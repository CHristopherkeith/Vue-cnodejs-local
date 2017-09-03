<template>
    <div>
        <img class="index" src="../assets/images/index.png">
    </div>
</template>
<script>
    require('../assets/scss/CV.scss');
    require('../assets/scss/iconfont/iconfont.css');
    require('../assets/scss/github-markdown.css');

    export default {
        mounted() {
            // console.log(this.$el);
            setTimeout(() => {
                // console.log(this);
                this.$router.push({
                    name: 'list'
                });
            }, 2000);
        }
    };
</script>
<style lang="scss">
    .index {
        width: 100%;
        background-color: #fff;
        margin-top: 40%;
    }
</style>
