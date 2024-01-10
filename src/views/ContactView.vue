<template>
    <div class="about-container">
      <!-- Left side with your image -->
      <div class="image">
        <img src="../assets/logo.png" alt="Qaqambile" />
      </div>
  
      <!-- Right side with contact form -->
      <div class="contact-form">
        <h2>Contact Me</h2>
        <form>
          <label for="name">First Name:</label>
          <input type="text" id="name" required />
          <label for="name">Last Name:</label>
          <input type="text" id="name" required />
          <label for="email">Your Email:</label>
          <input type="email" id="email" required />
  
          <button type="submit">CONNECT</button>
        </form>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        
      };
    },
    methods: {
      
    },
  };
  </script>
  
  <style scoped>
  .about-container {
    display: grid;
    grid-template-rows: repeat(1, 1fr);
    grid-template-columns: repeat(2, 1fr);
    gap: 20px;
    padding: 40px;
  }
  
  .image img {
    width: 80%;
    height: auto;
    border-radius: 15px;
  }
  
  .contact-form {
    display: flex;
    flex-direction: column;
  }
  
  form {
    display: flex;
    flex-direction: column;
    padding: 25px;
  }
  
  label {
    margin-bottom: 5px;
  }
  
  input {
    padding: 8px;
    margin-bottom: 10px;
  }
  
  button {
    padding: 10px;
    background-color: #007BFF;
    color: #fff;
    cursor: pointer;
    border: none;
    border-radius: 5px;
  }
  
  button:hover {
    background-color: #0056b3;
  }
  </style>
  