<template>
    <section id="experience">
      <h2>経験</h2>
      <div class="job">
        <h3>フロントエンド開発者 - 株式会社〇〇 (2021 - 現在)</h3>
        <p>担当したプロジェクトや達成した成果を簡潔に記述します。例：大規模なECサイトのフロントエンドを担当し、ページの読み込み速度を30%改善しました。</p>
      </div>
      <div class="job">
        <h3>ウェブデベロッパー - 株式会社△△ (2019 - 2021)</h3>
        <p>担当したプロジェクトや達成した成果を簡潔に記述します。例：新しい顧客管理システムを開発し、クライアントの満足度を向上させました。</p>
      </div>
    </section>
  </template>
  
  <script>
  export default {
    name: 'Experience'
  }
  </script>
  
  <style scoped>
  /* Experience.vue specific styles */
  .job {
    background: #f9f9f9;
    margin: 1rem 0;
    padding: 1rem;
    border-radius: 4px;
    box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
  }
  </style>
  