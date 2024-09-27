<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Profile</title>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
        }
        table {
            width: 100%;
            border-collapse: collapse;
        }
        td {
            padding: 10px;
            vertical-align: top;
        }
    </style>
</head>
<body>

<h1 align="center">Hi there 👋 I'm Anushka Jain!</h1>

<table>
  <tr>
    <td>
      <p>
        - 📫 How to reach me: <a href="mailto:anushkajain260@gmail.com">anushkajain260@gmail.com</a><br><br>
        - ⚡ Fun fact: My name means "a ray of hope"—I start each day with fresh optimism! <br>
        <h3>Languages and Tools:</h3>
        <p align="left">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original-wordmark.svg" alt="Java" width="50" height="50" style="display:inline-block;"/>
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" width="50" height="50" style="display:inline-block;"/>
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" alt="C++" width="50" height="50" style="display:inline-block;"/>
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" alt="Spring Boot" width="50" height="50" style="display:inline-block;"/>
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="React" width="50" height="50" style="display:inline-block;"/>
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" alt="MongoDB" width="50" height="50" style="display:inline-block;"/>
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="MySQL" width="50" height="50" style="display:inline-block;"/>
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" alt="NodeJS" width="50" height="50" style="display:inline-block;"/>
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/swift/swift-original.svg" alt="Swift" width="50" height="50" style="display:inline-block;"/>
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git" width="50" height="50" style="display:inline-block;"/>
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/firebase/firebase-plain.svg" alt="Firebase" width="50" height="50" style="display:inline-block;"/>
        </p>
      </p>
    </td>
    <td style="text-align: center;">
      <img src="https://i.pinimg.com/originals/0c/b0/ae/0cb0aec97240b7d9746073cd3ba6c26f.gif" alt="Animated Image" width="200" height="200"/>
    </td>
  </tr>
</table>

<h3 align="center">Most Used Languages</h3>
<canvas id="languagePieChart" width="400" height="400"></canvas>

<script>
  const ctx = document.getElementById('languagePieChart').getContext('2d');
  const languagePieChart = new Chart(ctx, {
    type: 'pie',
    data: {
      labels: ['Java', 'Python', 'C++', 'Spring Boot', 'React', 'MongoDB', 'MySQL', 'NodeJS', 'Swift', 'Git', 'Firebase'],
      datasets: [{
        label: 'Most Used Languages',
        data: [30, 25, 10, 15, 10, 5, 5, 5, 5, 5, 5], // Adjust these values as needed
        backgroundColor: [
          '#FF6384',
          '#36A2EB',
          '#FFCE56',
          '#4BC0C0',
          '#9966FF',
          '#FF9F40',
          '#FF5733',
          '#C70039',
          '#900C3F',
          '#581845',
          '#FFC300'
        ],
        hoverOffset: 4
      }]
    },
    options: {
      responsive: true,
      plugins: {
        legend: {
          position: 'top',
        },
        title: {
          display: true,
          text: 'Most Used Languages'
        }
      }
    }
  });
</script>

<h3>Let's Connect</h3>
- 📹 Check out my **YouTube Channel**: <a href="https://youtube.com/@DiiCodeJain">Coding With Didiiiiii</a><br>
- 💼 I'm actively seeking full-stack or mobile app development roles. Let's connect!

<p>Thanks for visiting my profile! 😄</p>

</body>
</html>
