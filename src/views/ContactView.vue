<template>
    <div class="about-container">
      <div class="image">
        <img src="../assets/que.png" alt="Qaqambile" />
      </div>

      <div class="contact-form">
        <h1>Connect with Qaqambile!</h1>
        <form>
          <label for="name">First Name:</label>
          <input type="text" id="name" required />
          <label for="name">Last Name:</label>
          <input type="text" id="name" required />
          <label for="email">Your Email:</label>
          <input type="email" id="email" required />
  
          <button type="submit">CONNECT</button>
        </form>
        <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d785.8880700106122!2d18.6544787!3d-34.0133529!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x1dcc4f2367fd7ee3%3A0xc4bc5e18d9120976!2s57%20Nyandeni%20Cres%2C%20Ikwezi%20Park%2C%20Cape%20Town%2C%207784!5e1!3m2!1sen!2sza!4v1705410136177!5m2!1sen!2sza" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
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
    border-radius: 25px;
  }
  
  button:hover {
    background-color: #0056b3;
  }

  input{
    width: auto;
    border-radius: 15px;
    border: none;
    box-shadow: 0 0 4px #000;
  }

  iframe{
    padding-left: 13% !important;
    border-radius: 10px;
  }
  </style>
  