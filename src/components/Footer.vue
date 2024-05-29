<template>
    <footer>
      <p>&copy; 2024 [あなたの名前]</p>
      <ul>
        <li><a href="https://twitter.com/yourprofile" target="_blank">Twitter</a></li>
        <li><a href="https://github.com/yourprofile" target="_blank">GitHub</a></li>
        <li><a href="https://linkedin.com/in/yourprofile" target="_blank">LinkedIn</a></li>
      </ul>
    </footer>
  </template>
  
  <script>
  export default {
    name: 'Footer'
  }
  </script>
  
  <style scoped>
  /* Footer.vue specific styles */
  ul {
    display: flex;
    justify-content: center;
    padding: 0;
  }
  
  ul li {
    margin: 0 0.5rem;
  }
  
  a {
    color: #3498db;
  }
  </style>
  