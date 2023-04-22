<template>
    <header>
      <h1>{{ title }}</h1>
  
    </header>
  </template>
  
  <script>
  export default {
    name: 'MyHeader',
  }
  </script>
  
  <style scoped>
  header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 1rem;
    background-color: #007bff;
    color: #fff;
  }
  
  nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
  }
  
  nav li {
    display: inline-block;
    margin-right: 1rem;
  }
  
  nav a {
    text-decoration: none;
    color: #fff;
  }
  
  nav a:hover {
    text-decoration: underline;
  }
  </style>
  