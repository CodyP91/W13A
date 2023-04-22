<template>
    <article>
      <h2>Buttons</h2>
      <button class="primary">Primary</button>
      <button class="secondary">Secondary</button>
      <button class="tertiary">Tertiary</button>
    </article>
  </template>
  
  <script>
  export default {
    name: 'MainContent'
  }
  </script>
  
  <style scoped>
  article {
    flex: 1;
    padding: 1rem;
  }
  
  button {
    border: none;
    border-radius: 4px;
    color: #fff;
    cursor: pointer;
    padding: 0.5rem 1rem;
  }
  
  .primary {
    background-color: #007bff;
  }
  
  .secondary {
    background-color: #6c757d;
  }
  
  .tertiary {
    background-color: #28a745;
  }
  </style>
  
  