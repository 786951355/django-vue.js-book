<style lang="less">
</style>

<template>
    <div>
        <Card>
            111111
        </Card>
    </div>
</template>

<script>
export default {
    methods: {
        backPage () {
            this.$router.go(-1);
        },
        goHome () {
            this.$router.push({
                name: 'home_index'
            });
        }
    }
};
</script>
