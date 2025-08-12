<!-- About Me Section with Dynamic Fade-in Animation -->

<style>
  @keyframes fadeInUp {
    0% {
      opacity: 0;
      transform: translateY(20px);
    }
    100% {
      opacity: 1;
      transform: translateY(0);
    }
  }
  .fade-in {
    animation: fadeInUp 1s ease forwards;
    opacity: 0;
  }
  .fade-in.delay-1 {
    animation-delay: 0.5s;
  }
  .fade-in.delay-2 {
    animation-delay: 1s;
  }
  .fade-in.delay-3 {
    animation-delay: 1.5s;
  }
  .about-container {
    max-width: 700px;
    margin: 40px auto;
    padding: 24px 30px;
    border-radius: 20px;
    background: linear-gradient(135deg, #0a2e5b, #035388);
    box-shadow: 0 0 40px #0a5ea7cc;
    color: #cbd5e1;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    text-align: center;
  }
  .about-heading {
    color: #58a6ff;
    font-weight: 900;
    font-size: 34px;
    margin-bottom: 20px;
  }
  .about-text {
    font-size: 16px;
    line-height: 1.6;
  }
</style>

<div class="about-container">
  <h2 class="about-heading fade-in delay-1">About Me</h2>
  <p class="about-text fade-in delay-2">
    Passionate Full-Stack & Backend Developer skilled in Python, React, MySQL, and PostgreSQL.
  </p>
  <p class="about-text fade-in delay-3">
    Expert in Tailwind CSS and Git, focused on clean code and continuous growth. 
    Aiming to master scalable backend systems and contribute to innovative open-source projects.
  </p>
</div>
