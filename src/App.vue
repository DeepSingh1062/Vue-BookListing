<template>
  <div id="app">
    <img src="./assets/logo.png">
    <book-list></book-list>
    <book-form @addBook='appendBook'></book-form>
  </div>
</template>

<script>
import BookList from './components/BookList';
import BookForm from './components/BookForm';
export default {
  name: 'app',
  components: {
    BookList,
    BookForm
  },
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
