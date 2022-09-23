<!-- <script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script> -->
<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Raleway:ital,wght@0,400;1,100&display=swap" rel="stylesheet">

<nav id="navbar">
    <div class="container">
    <div class="nav-content">

      <ul>
        <li><a href="#welcome-section">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </div>
  </div>
</div>
</nav>

<section id="welcome-section">
   <div class="container">
      <h1>Hey, I am Shashwat Dixit</h1>
  </div>
  
</section>

<section id="projects">
    <div class="container">
      <h2 class="project-tile">These are some of my works</h2>
      <div class="cards">
         <a class="card" href="https://github.com/noobdixit/SQL_DataExploration" target="_blank">
          <img 
               alt="Data Exploration Using SQL"
               src="https://raw.githubusercontent.com/noobdixit/ProjectImages/4f8cf330b791d0cb629311fbebeea82105c05374/covid19-1600x900.jpg" />
          <figcaption>Data Exploration</figcaption>
        </a>
        <a class="card" href="https://public.tableau.com/app/profile/shashwat.dixit/viz/COVIDDashBoard_16634434947710/Dashboard1?publish=yes" target="_blank">
        <img 
             alt="Data Visualization using Tableau"
             src="https://raw.githubusercontent.com/noobdixit/ProjectImages/main/Screenshot%20(332).png"  />
        <figcaption>Data Visualization</figcaption>
      </a>

      <a class="card" href="https://github.com/noobdixit/ExcelDashBoard" target="_blank">
        <img 
             alt="Excel DashBoard"
             src="https://raw.githubusercontent.com/noobdixit/ProjectImages/main/Screenshot%20(334).png" />
        <figcaption>Excel Dashboard</figcaption>
      </a>

      <a class="card" href="https://drive.google.com/file/d/12GwFBlOP3bWrqnr8tUwR1oLo9Yg84VDo/view?usp=sharing" target="_blank">
        <img 
             alt="Product landing project"
             src="https://raw.githubusercontent.com/noobdixit/ProjectImages/main/Screenshot%20(336).png" />
        <figcaption>Product Development</figcaption>
      </a>

      </div>
  </div>
</section>

<section id="contact">
  <div class="container">
    <h2 class="project-tile">Let us get in touch</h2>
    <p>You can Contact me through<p>
    <ul>
      <li><a id="profile-link" target="_blank" href="https://www.linkedin.com/in/shashwat-dixit-254b911a1"><i class="linkedin-Shashwat"></i> Linkedin</a></li>
      <li><a target="_blank" href="https://github.com/noobdixit"><i class="Github-Shashwat"></i> Github</a></li>
    </ul>
  </div>
</section>

<footer>
  <div class="container">
    <div class="footer-content">

      <p>Thanks for visiting Shashwat Dixit, Signing Off!</p>
    </div>
  </div>
</footer>
<style>
html {
    scroll-behavior: smooth
  }
  
  body {
    font-family: 'Lato', 'Lucida Grande', 'Lucida Sans Unicode', Tahoma, Sans-Serif;
   background-image: url('https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/b6221f28-67ed-43d5-8500-82e620bc77d1/d2s3qw9-a868b371-d50a-4552-a714-c3d4a79ba6a5.jpg?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOiIsImlzcyI6InVybjphcHA6Iiwib2JqIjpbW3sicGF0aCI6IlwvZlwvYjYyMjFmMjgtNjdlZC00M2Q1LTg1MDAtODJlNjIwYmM3N2QxXC9kMnMzcXc5LWE4NjhiMzcxLWQ1MGEtNDU1Mi1hNzE0LWMzZDRhNzliYTZhNS5qcGcifV1dLCJhdWQiOlsidXJuOnNlcnZpY2U6ZmlsZS5kb3dubG9hZCJdfQ.jpCjj0DFG90dTdxh1DgeWOuuIsBpoV_poU2UJaf7x1g');
    background-size: cover;
    background-repeat: no-repeat;
    -ms-overflow-style: none;  /* IE and Edge */
    scrollbar-width: none;  /* Firefox */
  }
  
  body::-webkit-scrollbar { /* Chrome, Safari, Opera */
    display: none;
  }
  
  h1, h2 {
    font-family: 'Raleway', sans-serif;
    font-size: 45px;
  }
  
  .container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
  }
  
  
  /*============= Header ===============*/
  #navbar {
      width: 100%;
      background-color: #be3144;
      position: fixed;
      top: 0;
      left: 0;
      right: 0;
    border-bottom: 2px solid #000;
        z-index: 5;
  }
  
  .nav-content {
      display: flex;
      width: 100%;
    align-items: center;
  }
  
  .nav-content .logo{
      display: flex;
      width: 15%;
  }
    
  
  
  .nav-content ul{
      font-size: 18px;
      font-weight: bold;
      padding: 0;
      list-style: none;
      width: 85%;
      display: flex;
      justify-content: flex-end;
  }
  
  .nav-content ul li{
      display: inline-block;
    margin-right: 20px;
  }
  
  .nav-content ul li:last-child{
    margin-right: 0;
  }
  
  .nav-content ul li a{
      text-decoration: none;
    color: #ffffff;
    transition: all .4s ease-in-out;
  }
  
  .nav-content ul li a:hover {
    color: #000;
  }
  
  /*============= Welcoming ===============*/
  #welcome-section{
      width: 100%;
      min-height: 100vh;
      display: flex;
      align-items: center;
    color: #ffffff;
     transition: all .5s ease-in-out;
  }
  
  #welcome-section:hover{
    transform: scale(1.25);
  }
  
  /*============= projects ===============*/
  #projects {
    background-color: #fff;
    padding: 20px 0;
    min-height: 100vh;
    align-items: center;
    display: flex;
  }
  
  #projects .project-tile {
    padding-bottom: 30px;
    padding-top: 73px;
  }
  
  #projects .cards {
    display: grid;
      grid-template-columns: 1fr;
      grid-gap: 20px;
  }
  
  #projects .cards .card{
    display: block;
    width: 100%;
    position: relative;
    transition: all 0.5s ease-in-out;
  }
  
  #projects .card:hover{
    transform: scale(1.1);
      position: relative;
      z-index: 10;
  }
  
  #projects .cards .card img{
    width: 100%;
    max-height: 300px;
    height: 100%;
    border-radius: 4px;
  }
  
  #projects .cards .card figcaption{
       position: absolute;
      z-index: 2;
      color: #fff;
      font-size: 20px;
      bottom: 0;
      margin: 0 auto;
      padding: 10px 0;
      text-align: center;
      width: 100%;
      background-color: rgb(0,0,0,.8);
  }
  
  
  /*============= Contact ===============*/
  #contact {
    color: #fff;
    display: flex;
    min-height: 80vh;
    align-items: center;
    text-align: center;
  }
  
  
  
  #contact h2{
   margin-bottom: 0
  }
  
  
  #contact ul{
      padding: 0;
      font-size: 30px;
      list-style: none;
      width: 100%;
  }
  
  #contact ul li{
    display: inline-block;
    margin-right: 40px;
    margin-bottom: 15px;
    transition: all .5s ease-in-out;
  }
  
  #contact ul li:last-child{
    margin-right: 0;
  }
  
  #contact ul li:hover{
    transform: scale(1.2)
  }
  
  #contact ul li a{
    text-decoration: none;
    color: #ffffff;
  }
  
  /*============= Footer ===============*/
  footer {
    width: 100%;
    background-color: #fff;
    border-top: 2px solid #be3144
  }
  
  footer .footer-content{
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 10vh;
  }
  
  footer .footer-content .logo{
    min-width: 80px;
    margin-right: 20px;
  }
  
  footer .footer-content .logo img{
    width: 100%;
  }
  
  /*============= Media query ===============*/
  @media(min-width: 400px){
    .nav-content .logo{
      width: 10%;
    }
  }
  @media (min-width: 600px){
    .nav-content ul {
      font-size: 24px;
    }
    .nav-content ul li a{
        padding: 46px;
    }
    .nav-content ul li a:hover {
      background-color: #000;
      color: #be3144;
    }
    #projects .cards {
      grid-template-columns: 1fr 1fr;
    }
  }
  
  @media (min-width: 900px){
    #projects .cards {
      grid-template-columns: 1fr 1fr 1fr;
    }
  }
  
  </style>
