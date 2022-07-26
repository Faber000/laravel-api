<template>
  <div class="card">
    <h2>{{title}}</h2>
    <div>{{content}}</div>
  </div>
</template>

<script>
export default {
    name: 'BaseCard',
    props: {
        title: {
            type: String
        },
        slug: {
            type: String,
        },
        content: {
            type: String
        },  
    }
}
</script>

<style lang="scss" scoped>
.card {
    background-color: white;
    border-radius: 10%;
    padding: 10px;
}
</style>