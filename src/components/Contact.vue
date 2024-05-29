<template>
    <section id="contact">
      <h2>お問い合わせ</h2>
      <form @submit.prevent="submitForm">
        <label for="name">名前:</label>
        <input type="text" id="name" v-model="form.name" required>
        
        <label for="email">メールアドレス:</label>
        <input type="email" id="email" v-model="form.email" required>
        
        <label for="message">メッセージ:</label>
        <textarea id="message" v-model="form.message" required></textarea>
        
        <button type="submit">送信</button>
      </form>
    </section>
  </template>
  
  <script>
  export default {
    name: 'Contact',
    data() {
      return {
        form: {
          name: '',
          email: '',
          message: ''
        }
      };
    },
    methods: {
      submitForm() {
        alert('メッセージが送信されました。ありがとうございます！');
      }
    }
  }
  </script>
  
  <style scoped>
  /* Contact.vue specific styles */
  form {
    display: flex;
    flex-direction: column;
  }
  
  label {
    margin: 0.5rem 0 0.2rem;
  }
  
  input, textarea {
    margin-bottom: 1rem;
    padding: 0.5rem;
    border: 1px solid #ddd;
    border-radius: 4px;
  }
  
  button {
    background: #3498db;
    color: #fff;
    border: none;
    padding: 0.5rem 1rem;
    border-radius: 4px;
    cursor: pointer;
  }
  
  button:hover {
    background: #2980b9;
  }
  </style>
  