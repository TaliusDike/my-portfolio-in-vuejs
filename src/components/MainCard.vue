<template>
  <div class="wrapper">
  <div class="main-container">
    <div class="container-one">
      <div class="profile">
        <img src="../assets/profilepic.jpeg" alt="my-profile-pic" />
        <h3>Arinze "Talius" Dike</h3>
        <p>Software Developer</p>
      </div>
      <div class="social-links">
        
          <div class="link">
            <a href="https://github.com/taliusdike" target="_blank">
            <img src="../assets/github.png" alt="github-logo" />
            <h2>GitHub</h2></a>
            
          </div>

          <div class="link">
            <a href="https://linkedin.com/in/taliusdike" target="_blank">
            <img src="../assets/linkedin.png" alt="linkedin-logo" />
            <h2>LinkedIn</h2></a>
          </div>

          <div class="link">
            <a href="https://twitter.com/taliusdike_" target="_blank">
            <img src="../assets/twitter.png" alt="twitter-logo" />
            <h2>Twitter</h2></a>
          </div>

          <div class="link">
            <a href="https://instagram.com/taliusdike" target="_blank">
            <img src="../assets/instagram.png" alt="instagram-logo" />
            <h2>Instagram</h2></a>
          </div>

          <div class="link">
            <a href="https://facebook.com/taliusdike" target="_blank">
            <img src="../assets/facebook.png" alt="facebook-logo" />
            <h2>Facebook</h2></a>
          </div>
        
      </div>
    </div>

    <div class="container-two">
      <div class="about-me">
        <h1>About Me</h1>
        <p>
            I'm a budding Software Engineer and Content Creator, who's putting in the work to become world-class soonest. I'm passionate about sharing knowledge, documentation, and web engineering.
        </p>

        <ul class="list-items">
            <li>😊 Pronouns: He/him</li>
            <li>💡 I'm currently studying at AltSchool Africa School of Software Engineering Class of 2022.</li>
            <li>🌱 I’m currently learning HTML, CSS, and JavaScript.</li>
            <li>😊 I’m looking for help with open source projects, hackathons, internships, and entry-level opportunities.</li>
            <li>💼 Job interests: Front Engineer internship opportunity, Technical Writing, Open Source.</li>
            <li>📫 Contact me by emailing ebeledikea@gmail.com.</li>
        </ul>



      </div>

      <div class="technology-section">
        <h1>I'm proficient in:</h1>
        <div class="logos">
          <img src="../assets/html.png" alt="html-logo" />
          <img src="../assets/css.png" alt="css-logo" />
          <img src="../assets/javascript.png" alt="javascript-logo" />
          <img src="../assets/react.png" alt="react-logo" />
          <img src="../assets/vue.png" alt="vue-logo" />
        </div>
      </div>

      <div class="button-container">
        <div class="projects-button">
          <a href="https://github.com/TaliusDike" target="blank">My Projects</a>
        </div>
        <div class="projects-button">
          <a href="">My Resume</a>
        </div>
      </div>
    </div>
  </div>
</div>
</template>

<script>
export default {};
</script>

<style scoped>
img {
  height: 25px;
}

.wrapper{
display: flex;
justify-content: center;
}

.main-container {
    display: flex;
    flex-direction: row;
    background-color: #A0D4FF;
    border-radius: 25px;
    width: 70%;
    box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px 
}

.container-one {
    background-color: #1292EE;
    width: 30%;
    padding: 2.5%;
    border-radius: 25px;
    box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px 
}

.profile img {
    height: 5rem;
    border-radius: 50%;
    border: 2px solid #A0D4FF;
}

.link a{
    text-decoration: none;
    color: black;
    font-size: 12px;
    display: flex;
    flex-direction: column;
    gap: 0;
    align-items:center;
}

.link img {
    height: 3rem;
}

.link a:hover {
    color: #2c3e50;
    font-size: 13px;
}

.container-two {
    width: 70%;
    margin: 2.5%;
}

.about-me {
    text-align: left;
}

.logos img{
    height: 2.5rem;
    /* margin-bottom: 1rem; */
}

.button-container {
    margin-top: 5%;
    display:flex;
    justify-content: center;
}

.projects-button{
    background-color: #1292EE;
    margin: 5px;
    padding: 7px;
    border-radius: 10px;
}

.projects-button a {
    text-decoration: none;
    color: black;
    font-size: 1.2rem;
    font: bold;
}

.projects-button a:hover{
    color: #2c3e50;
    font-size: 1.3rem;
}


@media only screen and (max-width: 950px) {
  .main-container {
    width: 95%;
  }
}


@media (min-width:320px) and (max-width: 480px) {
  .main-container {
    display: flex;
    flex-direction: column;
    /* justify-content: center; */
    align-items: center;
    box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px 
  }

  .container-one{
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 95%;

    /* flex-wrap: wrap; */
  }

  .profile img{
    height: 3rem;
  }

  .social-links{
    display: flex;
  }

  .social-links img {
    height: 1.5rem;
  }

  .link h2{
    font-size: 15px;
    margin-right: 7px;
  }

.container-two h1 {
  text-align: center;
}

.about-me p{
  text-align: justify;
}


}



</style>
