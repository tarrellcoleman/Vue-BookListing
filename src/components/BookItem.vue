<template>
    <div>
        <li>{{book.title}}:{{book.author}}</li>
    </div>
</template>

<script>
    export default {
        name:'BookItem',
        props: ['book']
    }
</script>

<style>
    h1, h2 {
        font-weight: normal
    }
    ul {
        list-style-type: none;
        padding: 0;
    }
    li {
        display: block;
        margin: 0 10px;
    }
</style>