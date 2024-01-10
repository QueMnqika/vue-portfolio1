<template>
  <div class="resume-container">
    <h1>My Resume</h1>

    <div class="education">
      <table>
        <tr>
          <th>School Name</th>
          <th>Course/Grade</th>
          <th>Year</th>
        </tr>
        <tr>
          <td>Life Choices Academy</td>
          <td>FullStack Development</td>
          <td>2023</td>
        </tr>
        <tr>
          <td>Thembelihle High School</td>
          <td>National Senior Certificate (NSC)</td>
          <td>2019</td>
        </tr>
        <tr>
          <td>MTN Business App Academy</td>
          <td>Mobile App Development</td>
          <td>2022</td>
        </tr>
        <tr>
          <td>Data Camp</td>
          <td>Intro to Python</td>
          <td>2022</td>
        </tr>
        <tr>
          <td>Data Camp</td>
          <td>Introduction to Data Science in Python</td>
          <td>2022</td>
        </tr>
        <tr>
          <td>College of Magic</td>
          <td>Theatre Production</td>
          <td>2016</td>
        </tr>
      </table>
    </div>
  </div>
</template>

<script>
export default {
  name: 'resume'
}
</script>

<style scoped>
table{
  border: 1px solid #000;
}
</style>
