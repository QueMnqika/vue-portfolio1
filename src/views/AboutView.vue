<template>
  <div class="container-fluid">
    <div class="about">
      <h2>{{ introHeading }}</h2>
      <p>{{ description }}</p>
      <div class="pic-text">
        <div class="picture">
          <img src="" alt="">
        </div>
        <div class="text">
          <h2>My Achievements?</h2>
          <div>
            <p>{{ showingAwards()}}</p>
          </div>
        </div>
      </div>
    </div>    
  </div>
</template>
<script>
export default {
  name: 'about',
  data(){
    return{
      introHeading: 'Who is Qaqambile?',
      description: 'I am a hardworking and dedicated individual with excellent team working skills. I have the ability to work efficiently, both independently and as part of a team. I bring a positive attitude and a willingness to learn new things, that is where my passion for the tech industry began in 2020 when I started teaching yourself how to code for the very first time before I came to Life Choices Academy. Since then, I have been determined to become a great software developer and have continuously developing my skills through self-learning and practice. My commitment to self-improvement and the passion for coding are an evidence of my work and my desire to succeed a developer within the industry.',
      awards: ['App Development', 'Introduction to Data Science in Python', 'Introduction to Python']
    }
  },
  methods: {
    showingAwards(){
      for (let award in this.awards) {
        return 
      }
    }
  }
}
</script>

<style scoped>
  
</style>