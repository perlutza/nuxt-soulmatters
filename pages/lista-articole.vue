<template>
<div>
    <div v-for="item in post" :key="item.title">
        <h3>{{item.title}}</h3>
        <img :src="item.image" />
    </div>
</div>
</template>

<script>
export default {
  asyncData: async ({ app }) => ({
    post: await app.$content('/posts').getAll() 
  })
}
</script>

<style>

</style>