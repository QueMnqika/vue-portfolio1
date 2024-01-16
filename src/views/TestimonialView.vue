<template>
  <div>
    <h1>TESTIMONIALS</h1>
    <div class="testimonials-cont">
      <div class="test-cards">
        <div class="rows">
          <img src="../assets/sphathi.jpg" alt="">
          <div>
            <h4>Sphathimandla Makhanya</h4>
            <p>"Qaqambile is an amazing young man full of energy and has a positive outlook on life. He is dedicated and has so much zeal, making it a greate experience to work with him."</p>
          </div>
        </div>
        <div class="rows">
          <div>
            <h4>Caela Ward</h4>
            <p>Que is a passionate hard working individual who always gives his full potential in any task given to him. Que is known for his creative and unique skills. He is a self motivated person who knows how to manage his time sparingly. Que is really an asset to be working with .</p>
          </div>
          <img src="../assets/caela.jpg" alt="">
        </div>
        <div class="rows">
          <img src="../assets/siya.jpg" alt="">
          <div>
            <h4>Siyamthanda Tsobo</h4>
            <p>Qaqambile is Fast-learner relevant and constantly keeps up to date in the technology industry.He always maximises his potential and will not deliver the bare minimum to your team.His work is unique and delivers on time.</p>
          </div>
        </div>
        <div class="rows">
          <div>
            <h4>Abdul Azeez Kemp</h4>
            <p>Que Mnqika is an exceptional, hardworking student who consistently goes above and beyond. His dedication to academics and his commitment to learning is truly admirable. Que's drive and determination make him a role model for his peers, and I have no doubt he will continue to excel in all his endeavors.</p>
          </div>
          <img src="../assets/abdul.jpg" alt="">
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'testimonial'
}
</script>

<style scoped>

  h1{
    padding-top: 2% !important;
  }
  .test-cards{
    padding: 2% 3% !important;
    margin: 3% 1% !important;
  }
  .rows{
    display: flex;
    justify-content: space-around;
    text-align: start;
    padding: 0 5% !important;
    border-top: 1px solid #afafaf;
  }
  .rows div{
    width: 50%;
    margin-top: 5%;
  }

  .rows img{
    border-radius: 50%;
    animation: spin 3s linear;
  }
  @keyframes spin {
    0%{
      transform: rotateY(0deg);
    }
    50%{
      transform: rotateY(180deg);
    }
  }
</style>