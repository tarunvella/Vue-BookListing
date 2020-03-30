<template>
  <form action="#" method="post">
    <input type="text" name="title" placeholder="Book Title">
    <input type="text" name="author" placeholder="Book Author">
    <button type="submit" name="button">Add Book</button>
  </form>
</template>

<script>
  export default {
    name: 'BookForm',
    props: ['books'],
    data() {
      return {
        bookTitle: '',
        bookAuthor: ''
      }
    }
  }
</script>

<style scoped>

</style>
