<template>
    <section id="about">
      <h2>自己紹介</h2>
      <!-- <img src="@/assets/profile.jpg" alt="プロフィール写真"> -->
      <p>こんにちは、フロントエンド開発者の[あなたの名前]です。私は、ユーザー体験を向上させるために魅力的でインタラクティブなWebサイトを作成することに情熱を持っています。</p>
    </section>
  </template>
  
  <script>
  export default {
    name: 'About'
  }
  </script>
  
  <style scoped>
  /* About.vue specific styles */
  section {
    text-align: center;
  }
  
  img {
    border-radius: 50%;
    width: 150px;
    height: 150px;
    margin: 1rem 0;
  }
  </style>
  