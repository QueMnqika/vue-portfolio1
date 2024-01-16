<template>
  <div class="resume-container">
    <div class="education">
      <h1>EDUCATION HISTORY</h1>
      <div class="education-data">
        <div class="edu-cards">
          <img src="../assets/202106-lifechoiceslogo1 (1).png" alt="">
          <h4>LIFECHOICES ACADEMY</h4>
          <small>Sept 2023 - Current</small>
          <p>FULLSTACK DEVELOPMENT</p>
        </div>
        <div class="edu-cards">
          <img src="../assets/datacamp-logo.png" alt="">
          <h4>DATA CAMP</h4>
          <small>Nov 2022 - Nov 2022</small>
          <p>Intoduction to Python</p>
        </div>
        <div class="edu-cards">
          <img src="../assets/datacamp-logo.png" alt="">
          <h4>DATA CAMP</h4>
          <small>Nov 2022 - Dec 2022</small>
          <p>INTRODUCTION TO DATA SCIENCE WITH PYTHON</p>
        </div>
        <div class="edu-cards">
          <img src="../assets/mtn-logo.png" alt="">
          <h4>MTN BUSINESS ACADEMY</h4>
          <small>Mar 2022 - Jun 2022</small>
          <p>WEB & MOBILE APP DEVELOPMENT</p>
        </div>
        <div class="edu-cards">
          <img src="../assets/thembelihle-high.png" alt="">
          <h4>THEMBELIHLE HIGH SCHOOL</h4>
          <small>Jan 2019 - Nov 2019</small>
          <p>NATIONAL SENIOR CERTIFICATE</p>
        </div>
        <div class="edu-cards">
          <img src="../assets/COM-logo.png" alt="">
          <h4>THE COLLEGE OF MAGIC</h4>
          <small>Jan 2016 - Nov 2016</small>
          <p>Magic Diploma (Merit)</p>
        </div>
      </div>
    </div>
    <div class="work-experience">
      <h1>MY WORK EXPERIENCE</h1>
      <div class="companies">
        <div class="comp-cards">
          <img src="../assets/TGIF.jpg" alt="">
          <h4>THE FOSCHINI GROUP (TFG)</h4>
          <small>Mar 2021 - Dec 2021</small>
          <p>Telemarketing Agent</p>
        </div>
        <div class="comp-cards">
          <img src="../assets/SAC.png" alt="">
          <h4>SA COMMERCIAL</h4>
          <small>Jan 2022 - Jun 2022</small>
          <p>Sales Agent (RCS Loans)</p>
        </div>
        <div class="comp-cards">
          <img src="../assets/TENACITY.png" alt="">
          <h4>TENACITY</h4>
          <small>Nov 2022 - Apr 2023</small>
          <p>New Business Agent</p>
        </div>
      </div>
    </div>
    <div class="skills-cont">
      <h1>MY SKILLS (TECHNICAL)</h1>
      <div class="skills">
        <div class="skills-cards">
        <img src="../assets/icons8-html-5-144.png" alt="">
        <h4>HTML 5</h4>
        <p >Level: <span style="color: rgb(83, 255, 83);">Intermediate</span></p>
      </div>
      <div class="skills-cards">
        <img src="../assets/icons8-css-144.png" alt="">
        <h4>CSS 3</h4>
        <p >Level: <span style="color: rgb(83, 255, 83);">Intermediate</span></p>
      </div>
      <div class="skills-cards">
        <img src="../assets/icons8-bootstrap-144.png" alt="">
        <h4>BOOTSTRAP 5</h4>
        <p >Level: <span style="color: rgb(248, 227, 63);">Beginner</span></p>
      </div>
      <div class="skills-cards">
        <img src="../assets/icons8-javascript-144.png" alt="">
        <h4>JAVASCRIPT</h4>
        <p >Level: <span style="color: rgb(248, 227, 63);">Beginner</span></p>
      </div>
      <div class="skills-cards">
        <img src="../assets/icons8-python-144.png" alt="">
        <h4>PYTHON</h4>
        <p >Level: <span style="color: rgb(248, 227, 63);">Beginner</span></p>
      </div>
      <div class="skills-cards">
        <img src="../assets/icons8-dart-144.png" alt="">
        <h4>DART</h4>
        <p >Level: <span style="color: rgb(250, 51, 51);">Basic</span></p>
      </div>
      <div class="skills-cards">
        <img src="../assets/icons8-flutter-144.png" alt="">
        <h4>FLUTTER</h4>
        <p >Level: <span style="color: rgb(250, 51, 51);">Basic</span></p>
      </div>
      <div class="skills-cards">
        <img src="../assets/VUE.png" alt="">
        <h4>VUE JS</h4>
        <p >Level: <span style="color: rgb(250, 51, 51);">Basic</span></p>
      </div>
      </div>
    </div>
    <div class="cv-btn">
      <h1>Want to see more about me?</h1>
      <a  href="https://drive.google.com/file/d/1Qygl9gUxaoLbQhpJ7U3t3LG2c3z6vYb_/view?usp=sharing" download target="_blank"><button>Download my Resume here</button></a>
      
    </div>
  </div>
</template>

<script>
export default {
  name: 'resume'
}
</script>

<style scoped>
body{
  background-color: #e9e9e9 !important;
}

  .resume-container h1{
    padding-top: 3% !important;
  }
  .education, .work-experience{
    border-bottom: 1px solid #000;
    border-top: 1px solid #000;
  }
  .education-data{
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr;
  }
  .edu-cards{
    margin-bottom: 35px !important;
  }

  .edu-cards img{
    width: 200px;
    border-radius: 25px;
  }

  .companies{
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
  }
  .companies img{
    width: 250px;
    border-radius: 25px;
  }

  img{
    margin: 10%;
  }

  .skills-cont{
    border-bottom: 1px solid #000;
    border-top: 1px solid #000;
  }
  .skills{
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr;
    text-align: center;
  }
  .cv-btn{
    display: flex;
    justify-content: center;
    flex-wrap: wrap-reverse;
  }

  .cv-btn a{
    padding: 2% 5%;

  }

  button{
    border: none;
    border-radius: 15px;
    background-color: #4af611;
    padding: 15px;
    margin: 10px;
    box-shadow: 0 0 8px #000;
  }
</style>
