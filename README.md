<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pankaj Hadole's GitHub</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f9;
      color: #333;
      margin: 0;
      padding: 0;
    }

    .container {
      max-width: 800px;
      margin: 0 auto;
      padding: 20px;
      text-align: center;
    }

    h2 {
      margin-top: 20px;
      color: #4a90e2;
    }

    .intro {
      margin-top: 20px;
      font-size: 1.1em;
    }

    .links {
      margin: 20px 0;
    }

    .links a {
      margin: 0 10px;
      text-decoration: none;
    }

    .tech-stack img {
      margin: 5px;
      transition: transform 0.2s;
    }

    .tech-stack img:hover {
      transform: scale(1.1);
    }

    footer {
      margin-top: 30px;
    }

    #lion-gif {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      width: 200px;
      height: 200px;
      opacity: 0;
      transition: width 0.5s, height 0.5s, opacity 0.5s;
    }

    #lion-gif.roaring {
      width: 400px;
      height: 400px;
      opacity: 1;
    }
  </style>
</head>

<body>

  <div class="container">

    <!-- Header -->
    <h2>👋 Hello, World! I'm Pankaj Hadole 🚀</h2>
    <p>
      <samp>🎓 Pursuing BTECH in Information Technology at JSPM's RSCOE Pune<br>
        💻 Full Stack Web Developer | Python | JavaScript | React | ML<br>
        🌟 Passionate Learner | Tech Enthusiast | Mentor</samp>
    </p>

    <!-- Intro -->
    <p class="intro">
      <samp>🤩 Welcome to my GitHub! I'm an enthusiastic Full Stack Web Developer with a passion for Python, JavaScript,
        React, and HTML/CSS. Graduated from Government Polytechnic Amravati with a diploma in Information Technology.
        Currently pursuing BTECH in IT at JSPM's RSCOE Pune. I have a strong foundation in web development and excel in
        creating interactive and responsive websites. Experienced in Python and Java, I recently developed a Face
        Recognition-based Attendance System using Machine Learning for my final year project.</samp>
    </p>

    <!-- Resume -->
    <div class="links">
      <a href="http://tinyurl.com/Pankajsresume" target="_blank">
        <img src="https://img.shields.io/badge/Resume-%23FF5722?style=for-the-badge&logo=google-drive&logoColor=white"
          alt="Resume">
      </a>
    </div>

    <!-- Portfolio and Social Links -->
    <div class="links">
      <a href="https://phcoder05.github.io/My-Portfolio/" target="_blank">
        <img src="https://img.shields.io/badge/Portfolio-%230077B5?style=for-the-badge&logo=github&logoColor=white"
          alt="Portfolio">
      </a>
      <a href="https://www.linkedin.com/in/pankaj-hadole-722476232/" target="_blank">
        <img src="https://img.shields.io/badge/LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white"
          alt="LinkedIn">
      </a>
      <a href="https://twitter.com/pankaj_hadole" target="_blank">
        <img src="https://img.shields.io/badge/Twitter-%231DA1F2?style=for-the-badge&logo=twitter&logoColor=white"
          alt="Twitter">
      </a>
      <a href="mailto:pankajhadole05@gmail.com" target="_blank">
        <img src="https://img.shields.io/badge/Email%20Me-%23D14836?style=for-the-badge&logo=gmail&logoColor=white"
          alt="Email Me">
      </a>
      <a href="https://leetcode.com/PHCoder05/" target="_blank">
        <img src="https://img.shields.io/badge/LeetCode-%23F89F1B?style=for-the-badge&logo=leetcode&logoColor=white"
          alt="LeetCode">
      </a>
    </div>

    <!-- Tech Stack -->
    <h3>Languages and Tools:</h3>
    <div class="tech-stack">
      <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"
        alt="JavaScript" />
      <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React" />
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
      <img src="https://img.shields.io/badge/Shell-5391FE?style=for-the-badge&logo=gnu-bash&logoColor=white" alt="Shell" />
      <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
    </div>

    <!-- Footer -->
    <footer>
      <p>🌟 Don't forget to star some of my repositories! 🌟</p>
    </footer>

  </div>

  <!-- Lion GIF -->
  <img id="lion-gif" src="https://gifdb.com/images/high/scary-lion-roar-jumping-on-you-xvme3dx02oj2v5k3.webp" alt="Roaring Lion">

  <script>
    window.addEventListener('load', function () {
      const lionGif = document.getElementById('lion-gif');
      lionGif.classList.add('roaring');
      setTimeout(() => {
        lionGif.style.opacity = '0';
      }, 3000);
    });
  </script>

</body>

</html>
