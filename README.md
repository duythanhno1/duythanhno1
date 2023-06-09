<!-- CSS Style -->
<style>
  /* Center align */
  .center {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 100vh;
    text-align: center;
  }

  /* Animated text */
  .animated-text {
    font-size: 30px;
    font-weight: bold;
    color: #333;
    animation: text-animation 3s infinite;
  }

  @keyframes text-animation {
    0% { color: #333; }
    50% { color: #FF9800; }
    100% { color: #333; }
  }

  /* Skill icons */
  .skills {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    list-style-type: none;
    padding: 0;
  }

  .skills li {
    margin: 10px;
    opacity: 0;
    animation: fade-in 2s forwards;
  }

  @keyframes fade-in {
    0% { opacity: 0; }
    100% { opacity: 1; }
  }
</style>

<!-- Content -->
<p align="center">
  <img src="https://media2.giphy.com/media/ttknk7M3d3UBEeZsii/giphy.gif?cid=ecf05e47bpqbt4obwf45j5gmo0u0ivwfs7q398fcfwt9x4bh&ep=v1_gifs_search&rid=giphy.gif&ct=g" width="600" alt="Animated GIF"/>
</p>

<div class="center">
  <h2 class="animated-text">Hi there, I'm Duy Thanh 🙋‍♂️</h2>

  <p>
    <img src="https://github.githubassets.com/images/icons/emoji/octocat.png" width="20" height="20" alt="Octocat"/> 
    Open source is something I'm interested in.
  </p>

  <p>
    Game development is an area I'm focusing on right now. 🎮
  </p>

  <h2>Skills</h2>

  <ul class="skills">
    <li>
      <img src="https://img.icons8.com/color/48/000000/c-programming.png" alt="C" title="C" width="40" height="40" />
    </li>
    <li>
      <img src="https://img.icons8.com/color/48/000000/c-sharp-logo.png" alt="C#" title="C#" width="40" height="40" />
    </li>
    <li>
      <img src="https://img.icons8.com/color/48/000000/java-coffee-cup-logo.png" alt="Java" title="Java" width="40" height="40" />
    </li>
    <li>
      <img src="https://img.icons8.com/color/48/000000/html-5--v1.png" alt="HTML" title="HTML" width="40" height="40" />
    </li>
    <li>
      <img src="https://img.icons8.com/color/48/000000/css3.png" alt="CSS" title="CSS" width="40" height="40" />
    </li>
    <li>
