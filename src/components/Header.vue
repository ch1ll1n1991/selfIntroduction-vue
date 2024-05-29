<template>
    <header>
      <h1>私の自己紹介</h1>
      <nav>
        <ul>
          <li><router-link to="#about">自己紹介</router-link></li>
          <li><router-link to="#skills">スキル</router-link></li>
          <li><router-link to="#experience">経験</router-link></li>
          <li><router-link to="#contact">お問い合わせ</router-link></li>
        </ul>
      </nav>
    </header>
  </template>
  
  <script>
  export default {
    name: 'Header'
  }
  </script>
  
  <style scoped>
  /* Header.vue specific styles */
  nav ul {
    display: flex;
    justify-content: center;
    padding: 0;
  }
  
  nav ul li {
    margin: 0 1rem;
  }
  
  nav ul li a {
    color: #fff;
    font-weight: bold;
  }
  </style>
  