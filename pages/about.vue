<template>
    <div>
        <Title title="About"/>  
        <p> Is this actually working is it??</p>
    </div>
</template>

<script>
export default {
    name: 'About',
    layout: 'auth',
    data() {
        return {
            title: "About"
        }
    }
}
</script>

<style>
    h1 {
        text-align: center;
    }
    p {
        text-align: center;
    }
</style>