<template>
    <Page class="page">
        <ActionBar class="action-bar">
            <Label class="action-bar-title" text="Timeline"></Label>
        </ActionBar>

        <ScrollView>
            <StackLayout>
                <Post />
                <Post />
            </StackLayout>
        </ScrollView>
    </Page>
</template>

<script>
    import Post from './Post'
    export default {
        components: { Post }
    };
</script>

<style scoped lang="scss">
    @import '../app-variables';
    .fa {
        color: $accent-dark;
    }

    .info {
        font-size: 20;
    }

    .page{
        background: #ccc;
    }
</style>
