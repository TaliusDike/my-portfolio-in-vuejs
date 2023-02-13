<template>
  <div class="main-container">
    <div class="container-one">
      <div class="profile">
        <img src="../assets/profilepic.jpeg" alt="my-profile-pic" />
        <h3>Arinze "Talius" Dike</h3>
        <p>Software Developer</p>
      </div>
      <div class="social-links">
        
          <div class="link">
            <a href="https://github.com/taliusdike">
            <img src="../assets/github.png" alt="github-logo" />
            <h2>GitHub</h2></a>
            
          </div>

          <div class="link">
            <a href="https://linkedin.com/in/taliusdike">
            <img src="../assets/linkedin.png" alt="linkedin-logo" />
            <h2>LinkedIn</h2></a>
          </div>

          <div class="link">
            <a href="https://twitter.com/taliusdike_">
            <img src="../assets/twitter.png" alt="twitter-logo" />
            <h2>Twitter</h2></a>
          </div>

          <div class="link">
            <a href="https://instagram.com/taliusdike">
            <img src="../assets/instagram.png" alt="instagram-logo" />
            <h2>Instagram</h2></a>
          </div>

          <div class="link">
            <a href="https://facebook.com/taliusdike">
            <img src="../assets/facebook.png" alt="facebook-logo" />
            <h2>Facebook</h2></a>
          </div>
        
      </div>
    </div>

    <div class="container-two">
      <div class="about-me">
        <h1>About Me</h1>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad
          minim veniam, quis nostrud exercitation ullamco...
        </p>
      </div>

      <div class="technology-section">
        <h1>I'm Proficient In:</h1>
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
          <a href="">My Projects</a>
        </div>
        <div class="projects-button">
          <a href="">My Resume</a>
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

.main-container {
    display: flex;
    flex-direction: row;
    background-color: grey;
    border-radius: 25px;
}

.container-one {
    background-color: pink;
    width: 30%;
    padding: 2.5%;
    border-radius: 25px;
}

.profile img {
    height: 5rem;
    border-radius: 50%;
    border: 2px solid red;
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
    background-color: red;
    width: 70%;
    margin: 2.5%;
}

.about-me {
    text-align: left;
}

.logos img{
    height: 3rem;
    /* margin-bottom: 1rem; */
}

.button-container {
    margin-top: 5%;
    display:flex;
    justify-content: center;
}

.projects-button{
    background-color: pink;
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
</style>
