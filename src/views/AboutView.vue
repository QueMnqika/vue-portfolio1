<template>
  <div class="abt-container">
    <h1>ABOUT QAQAMBILE</h1>
    <div class="about">
      <div class="about-content">
        <div class="pic">
          <img src="../assets/que.png" alt="">
        </div>
        <div class="abt">
          <div class="text">
            <h2>Introduction</h2>
            <p>Qaqambile is a hardworking and dedicated individual with a passion for UI/UX & Front-end development, I am driven to constantly improve my skills and knowledge. With a strong ability to work both independently and collaboratively, I am a valuable team member who is committed to delivering high-quality work. As someone who taught myself to code in 2020, I am constantly seeking new challenges and opportunities to grow as a software developer. I am excited to bring my passion, drive, and skills to a team where I can make a meaningful impact and contribute to innovative solutions.</p>
          </div>
          <div class="text">
            <h2>Giving back to the community</h2>
            <p>I have been involved with the College of Magic for more than 5 years and on the year I was a graduate, I volunteered in the organization for 6 months before I got an opportunity from the UCT Local School Learning Programme from Grade 10 to Grade 12. I volunteered alongside Anne Pawley who was the owner of the tuck shop at that time, serving breakfast and luncc to the Magic in Community student who does not have the means of such crucial meals of the day.</p>
          </div>
          <div class="text">
            <h2>Activities & Hobbies</h2>
            <ul>
              <li>Video Gaming</li>
              <li>Social Media Video Editing</li>
              <li>Logo and Poster Design</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'about',
}  
</script>

<style scoped>

  h1{
    padding-top: 2% !important;
  }
  .about-content{
   display: grid;
   grid-template-columns: 1fr 1fr;
  }

  img{
    height: 100vh !important;
  }

  ul{
    list-style: none;
  }
  
  li{
    font-size: 17px;
  }

  .text{
    border-bottom: 1px solid #000;
    margin-top: 5%;
  }
</style>