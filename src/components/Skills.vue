<template>
    <section id="skills">
      <h2>スキル</h2>
      <ul>
        <li>HTML5</li>
        <li>CSS3</li>
        <li>JavaScript</li>
        <li>レスポンシブデザイン</li>
        <li>バージョン管理 (Git)</li>
        <li>React.js</li>
        <li>Vue.js</li>
      </ul>
    </section>
  </template>
  
  <script>
  export default {
    name: 'Skills'
  }
  </script>
  
  <style scoped>
  /* Skills.vue specific styles */
  ul {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
  }
  
  li {
    background: #3498db;
    color: #fff;
    margin: 0.5rem;
    padding: 0.5rem 1rem;
    border-radius: 4px;
  }
  </style>
  