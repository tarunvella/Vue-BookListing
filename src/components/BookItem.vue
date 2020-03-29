<template>
    {{book.title}} : {{ book.author}}
</template>

<script>
  export default {
    name: 'BookItem',
    props: ['book']
  };
</script>

<style scoped>

</style>
