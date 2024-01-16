<template>
  <div class="about">
    <div class="projects-cont">
      <h1>My Projects</h1>
      <div class="proj-cards">
        <div class="cards">
          <img src="../assets/w3school.png" alt="">
          <h4>W3School page clone</h4>
          <span>I cloned a page of W3Schools using HTML5 & CSS3</span>
          <div>
            <a href="https://poetic-custard-9b1e27.netlify.app" target="_blank"><button>Visit the site</button></a>
          </div>
        </div>
        <div class="cards">
          <img src="../assets/freshe.png" alt="">
          <h4>FreshE Cafe</h4>
          <span>I built the e-commerce using HTML5 & CSS3</span>
          <div>
            <a href="freshecafe.netlify.app" target="_blank"><button>Visit the site</button></a>
          </div>
        </div>
        <div class="cards">
          <img src="../assets/calculator.png" alt="" height="216px">
          <h4>Basic Calculator</h4>
          <span>I built this calculator using HTML, CSS and JavaScript.</span>
          <div>
            <a href="https://que-calculator-2.netlify.app" target="_blank"><button>Visit the site</button></a>
          </div>
        </div>
        <div class="cards">
          <img src="../assets/zonime.png" alt="">
          <h4>Zonime</h4>
          <span>I built my e-commerce using HTML5, CSS3, Bootstrap5 & a little of Javascript.</span>
          <div>
            <a href="https://zonime.netlify.app" target="_blank"><button>Visit the site</button></a>
          </div>
        </div>
        <div class="cards">
          <img src="../assets/bmi.png" alt="">
          <h4>BMI Calculator</h4>
          <span>I also built this BMI Calculator using HTML5, CSS3 and JavaScript.</span>
          <div>
            <a href="https://que-bmi-calculator.netlify.app/" target="_blank"><button>Visit the site</button></a>
          </div>
        </div>
        <div class="cards">
          <img src="../assets/temp.png" alt="">
          <h4>Temperature Converter</h4>
          <span>I also built this Temperature Converter using HTML5, CSS3 and JavaScript.</span>
          <div>
            <a href="https://que-temp-converter.netlify.app" target="_blank"><button>Visit the site</button></a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'projects'
}
</script>

<style scoped>

  h1{
    padding-top: 2% !important;
  }
  .cards h4, span{
    padding: 2% !important;
  }
  .proj-cards{
    display: grid;
    grid-template-rows: 1fr 1fr 1fr;
    grid-template-columns: 1fr 1fr;
    padding: 5%;
    animation: fadein 2s linear;
  }

  .proj-cards img{
    border-radius: 25px;
    box-shadow: 0 0 10px #000;
  }

  button{
    border: none;
    box-shadow: 0 0 8px #000;
    background-color: yellow;
    border-radius: 25px;
    padding: 10px;
    margin-top: 15px;
  }
  button:hover{
    border: none;
    box-shadow: 0 0 8px #000;
    background-color: rgb(121, 255, 39);
    border-radius: 25px;
    padding: 10.9px;
    margin-top: 15px;
  }

  @keyframes fadein {
    0%{
      opacity: 0 ;
    }

    100%{
      opacity: 1;
    }
  }
</style>