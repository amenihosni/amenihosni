<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">


<style>
  /* Add animation keyframes */
  @keyframes slideInFromLeft {
    0% {
      transform: translateX(-100%);
      opacity: 0;
    }
    100% {
      transform: translateX(0);
      opacity: 1;
    }
  }

  @keyframes slideInFromRight {
    0% {
      transform: translateX(100%);
      opacity: 0;
    }
    100% {
      transform: translateX(0);
      opacity: 1;
    }
  }

  /* Apply animation to stats elements */
  .stats-container {
    display: flex;
    justify-content: space-around;
    margin-top: 20px;
    animation: slideInFromLeft 1s ease-out;
  }

  .streak-container {
    margin-top: 20px;
    animation: slideInFromRight 1s ease-out;
  }
</style>

</head>
<body>

<h1 align="center">
    <img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=35&center=true&vCenter=true&width=500&height=70&duration=4000&lines=Hi+There!+👋;+I'm+Ameni+Hosni!;" />
</h1>

<h3 align="center">🌱A passionate IT student from Tunisia🌱 </h3>
<div align="center">
  <img src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExdHVqNG9lbzNseG5kdDQwb2xxYng4enA3ZHRvbmcxeWFqYzE4ZTQ1MiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/paTz7UZbPfTZFRYnnB/giphy.gif" alt="Passionate IT student" width="300" height="300"/>
</div>

<p align="right"> <img src="https://komarev.com/ghpvc/?username=amenihosni&label=Profile%20views&color=0e75b6&style=flat" alt="amenihosni" /> </p>

<h3 align="center">🐍 I’m currently learning **JAVA, Python**🐍</h3>
 
<div align="center"> 
  <a href="mailto:amenihosni71@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-333333?style=for-the-badge&logo=gmail&logoColor=red" />
  </a>
    <a href="https://www.linkedin.com/in/ameni-hosni-7a99971b0" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank" />
  </a>
</div>

<h2 align="center">⚒️ Languages-Frameworks-Tools ⚒️</h2>
<br/>
<div class="icon-container" align="center">
    <a href="https://www.arduino.cc/" target="_blank" rel="noreferrer">
        <img src="https://cdn.worldvectorlogo.com/logos/arduino-1.svg" alt="arduino" width="40" height="40"/>
    </a>
    <!-- Add other icons as needed -->
</div>

<h2 align="center">⚡ Stats ⚡</h2>

<!-- Stats section with animations -->
<div class="stats-container" align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=amenihosni&show_icons=true&locale=en&layout=compact" alt="Top Languages" />
</div>

<div class="streak-container" align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=amenihosni&" alt="GitHub Streak" />
</div>

</body>
</html>
