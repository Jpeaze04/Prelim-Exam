<template>
    <nav id="navbarExample" class="navbar navbar-expand-lg fixed-top navbar-light" aria-label="Main navigation">
     <div class="container">
          <a class="navbar-brand logo-text" href="#">JPEAZE:]</a> 
         <button class="navbar-toggler p-0 border-0" type="button" id="navbarSideCollapse" aria-label="Toggle navigation">
             <span class="navbar-toggler-icon"></span>
         </button>
         <div class="navbar-collapse offcanvas-collapse" id="navbarsExampleDefault">
             <ul class="navbar-nav ms-auto navbar-nav-scroll">
                 <li class="nav-item">
                     <a class="nav-link active" aria-current="page" href="#header">Home</a>
                 </li>
                 <li class="nav-item">
                     <a class="nav-link" href="#services">Skills</a>
                 </li>
                 <li class="nav-item">
                     <a class="nav-link" href="#details">About</a>
                 </li>
                 <li class="nav-item">
                     <a class="nav-link" href="#features">Projects</a>
                 </li>
   
             </ul>
             <span class="nav-item">
                 <a class="btn-solid-sm" href="#contact">Contact Me</a>
             </span>
         </div> 
     </div> 
   </nav>
   <header id="header" class="header">
     <div class="container">
         <div class="row">
             <div class="col-lg-6 col-xl-5">
                 <div class="text-container">
                     <h1 class="h1-large">Hi! I'm Jhona Lajao - Lajao</h1>
                     <h2 class="h2-large">I am a Graphic Designer and Front- End Developer</h2>
              
               <h5 class="h5">Broom Broom skrrt</h5>
                     <a class="btn-solid-lg" href="#features"> See my portfolio →</a>
                 </div>
             </div> 
             <div class="col-lg-6 col-xl-7">
                 <div class="image-container">
                     <img class="img-fluid" src="assets/images/rawr.png" alt="image" />
                 </div> 
             </div> 
         </div> 
     </div> 
   </header> 
   <div id="services" class="cards-1 bg-gray">
     <div class="container">
         <div class="row">
             <div class="col-lg-12">
   <h1>My Skills</h1>
   
   <h5>HTML</h5>
   <div class="container">
     <div class="skills html">50%</div>
   </div>
   
   <h5>CSS</h5>
   <div class="container">
     <div class="skills css">40%</div>
   </div>
   
   <h5>JavaScript</h5>
   <div class="container">
     <div class="skills js">20%</div>
   </div>
   
   <h5>SQL</h5>
   <div class="container">
     <div class="skills sql">10%</div>
   </div>
   
   <h5>Vue</h5>
   <div class="container">
     <div class="skills vue">10%</div>
   </div>
   
   
                 <br>
             </div> 
         </div>
         
         <div class="row">
             <div class="col-lg-12">
                 
               
   
                 
             </div>
         </div>
     </div>
   </div> 
   <div id="details" class="basic-1">
     <div class="container">
         <div class="row">
             <div class="col-lg-6 col-xl-7">
                 <div class="image-container">
                     <img class="img-fluid" src="assets/images/jho.png" alt="alternative" />
                 </div> 
             </div> 
             <div class="col-lg-6 col-xl-5">
                 <div class="text-container">
                   <h4 class="h1-large">About </h4>
       
                     <p> I am Jhona Lajao - Lajao a Graphic Designer and Front-End Developer.
                       Born in 2000 . A 4th year college student in La Consolacion College - Bacolod
                       taking up BSIT. I do believe web design can be more diverse and inspiring to
                       every student who pursue web developing. With a mission to present the possibilities
                       of web design. I am pursuing new expressions through expressions and thoughts.
                     </p>
                     <a class="btn-solid-reg" href="#contact">Contact Me</a>
                 </div> 
             </div> 
         </div>
     </div> 
   </div>

    

           
               
                  
       
   <div id="features" class="accordion-1">
     <div class="container">
         <div class="row">
             <div class="col-xl-12">
                 <h2 class="h2-heading">My Portfolio</h2>
                 <p class="p-heading"></p>
             </div> 
         </div>   
         
         <div class="row">
             <div class="col-xl-5">
                 <div class="accordion" id="accordionExample">
                     
                    
                     <div class="accordion-item">
                         <div class="accordion-icon">
                             <span class="fas fa-tv"></span>
                         </div> 
                         <div class="accordion-header" id="headingOne">
                             <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
                                WEB BANNER DESIGN
                             </button>
                         </div>
                         <div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="headingOne" data-bs-parent="#accordionExample">
                             <div class="accordion-body">Web Banner<img class="img-fluid" src="assets/images/banner.jpg" alt="alternative"/></div>
                         </div>
                     </div>
                    
                    
                     <div class="accordion-item">
                         <div class="accordion-icon blue">
                             <span class="fas fa-microphone"></span>
                         </div> 
                         <div class="accordion-header" id="headingTwo">
                             <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
                                BLENDER
                             </button>
                         </div>
                         <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo" data-bs-parent="#accordionExample">
                             <div class="accordion-body">Table Cabinet<img class="img-fluid" src="assets/images/Table Cabinet.png" alt="alternative"/></div>
                         </div>
                     </div>
                    
                    
                     <div class="accordion-item">
                         <div class="accordion-icon purple">
                             <span class="fas fa-video"></span>
                         </div> 
                         <div class="accordion-header" id="headingThree">
                             <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
                                WEB DESIGN
                             </button>
                         </div>
                         <div id="collapseThree" class="accordion-collapse collapse" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
                             <div class="accordion-body">PARALLAX<img class="img-fluid" src="assets/images/pj.jpg" alt="alternative"/></div>
                             <div class="accordion-body">Log In Page<img class="img-fluid" src="assets/images/login.jpg" alt="alternative"/></div>
                         </div>
                     </div>
                    
                     
                    
                     <div class="accordion-item">
                         <div class="accordion-icon orange">
                             <span class="fas fa-tools"></span>
                         </div> 
                         <div class="accordion-header" id="headingFour">
                             <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseFour" aria-expanded="false" aria-controls="collapseFour">
                               UI/UX DESIGN
                             </button>
                         </div>
                         <div id="collapseFour" class="accordion-collapse collapse" aria-labelledby="headingFour" data-bs-parent="#accordionExample">
                             <div class="accordion-body">Ecommerce<img class="img-fluid" src="assets/images/ecommerce.png" alt="alternative"/></div>
                             <div class="accordion-body">Mobile<img class="img-fluid" src="assets/images/nightandday.png" alt="alternative"/></div>
                         </div>
                     </div>
                    
                 </div> 
             </div> 
             <div class="col-xl-7">
                 <div class="image-container">
                     <img class="img-fluid" src="assets/images/pj.jpg" alt="alternative"/>
                 </div> 
             </div> 
         </div>
     </div> 
   </div> 
   
   <div id="contact" class="form-1">
     <div class="container">
         <div class="row">
             <div class="col-lg-6">
                 <div class="text-container">
                     <div class="section-title"></div>
                     <h3>GOT A PROBLEM TO SOLVE?</h3>
                     <p>Get your space suit ready and tell me your ideas to develop your dream application.</p>
                    
                 </div> 
             </div> 
             <div class="col-lg-6">
                
                 <form>
                     <div class="form-group">
                         <input type="text" class="form-control-input" placeholder="Name" required />
                     </div>
                     <div class="form-group">
                         <input type="email" class="form-control-input" placeholder="Email" required />
                     </div>
                     <div class="form-group">
                         <input type="text" class="form-control-input" placeholder="Industry" required />
                     </div>
                     <div class="form-group">
                         <input type="text" class="form-control-input" placeholder="Your product" required />
                     </div>
                     <div class="form-group">
                         <button type="submit" class="form-control-submit-button">Hit Me up</button>
                     </div>
                 </form>
               
             </div> 
         </div>
     </div> 
   </div>
   <div class="footer bg-gray">
     <img class="decoration-circles" src="assets/images/decoration-circles.png" alt="alternative" />
     <div class="container">
         <div class="row">
             <div class="col-lg-12">
                 <h4>If you want to find out which are the right influencers for your product marketing campaigns then follow me on social media</h4>
                 <div class="social-container">
                     <span class="fa-stack">
                         <a href="#your-link">
                             <i class="fas fa-circle fa-stack-2x"></i>
                             <i class="fab fa-facebook-f fa-stack-1x"></i>
                         </a>
                     </span>
                     <span class="fa-stack">
                         <a href="#your-link">
                             <i class="fas fa-circle fa-stack-2x"></i>
                             <i class="fab fa-twitter fa-stack-1x"></i>
                         </a>
                     </span>
                     <span class="fa-stack">
                         <a href="#your-link">
                             <i class="fas fa-circle fa-stack-2x"></i>
                             <i class="fab fa-pinterest-p fa-stack-1x"></i>
                         </a>
                     </span>
                     <span class="fa-stack">
                         <a href="#your-link">
                             <i class="fas fa-circle fa-stack-2x"></i>
                             <i class="fab fa-instagram fa-stack-1x"></i>
                         </a>
                     </span>
                     <span class="fa-stack">
                         <a href="#your-link">
                             <i class="fas fa-circle fa-stack-2x"></i>
                             <i class="fab fa-youtube fa-stack-1x"></i>
                         </a>
                     </span>
                 </div> 
             </div> 
         </div>
     </div> 
   </div> 
   <div class="copyright bg-gray">
     <div class="container">
         <div class="row">
             <div class="col-lg-6 col-md-12 col-sm-12">
                 <ul class="list-unstyled li-space-lg p-small">
                     <li><a href="#">Article Details</a></li>
                     <li><a href="#">Terms & Conditions</a></li>
                     <li><a href="#">Privacy Policy</a></li>
                 </ul>
             </div> 
             <div class="col-lg-3 col-md-12 col-sm-12">
                 <p class="p-small statement">Copyright © <a href="#">Jhona Lajao-Lajao </a></p>
             </div> 
             <div class="col-lg-3 col-md-12 col-sm-12">
                 <p class="p-small statement">Distributed by <a href="https://JhonaL.com" target="_blank">Jhona Lajao-Lajao </a></p>
             </div> 
         </div> 
     </div> 
   </div>
   <button id="myBtn">
     <img src="assets/images/up-arrow.png" alt="alternative" />
   </button>
   </template>
   
   
   
   <style>
   #app {
     font-family: Avenir, Helvetica, Arial, sans-serif;
     -webkit-font-smoothing: antialiased;
     -moz-osx-font-smoothing: grayscale;
     text-align: center;
     color: red;
     margin-top: 60px;
   }
   </style>