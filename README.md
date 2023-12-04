#my_portfolio
<html><head>
    <title>Alya Rees - Portfolio</title>
    <link rel="stylesheet" href="./style.css">
    <script src="./script.js"></script>
  </head>
  <body>
    <!-- Navigation Bar -->
    <nav>
      <div id="home">
        <div class="profile_name">
          Alya Rees
          <div class="contact_info">
            <img src="html_finalprojimages/envelope.png" alt="https://icons8.com/icon/124377/circled-envelope">
          jdoe@jeemail.com
        </div>
        <div style="clear:both;"></div>
        <div class="contact_info">
          <img src="html_finalprojimages/phone.png" alt="https://icons8.com/icon/124377/circled-envelope">
          +13456764598

        </div>
        </div>
        <div class="topdiv">
          <a class="topmenu" href="#about-me">About Me</a>
          <a class="topmenu" href="#skills">Skills</a>
          <a class="topmenu" href="#projects">Projects</a>
          <a class="topmenu" href="#recommendations">Recommendations</a>
          <!-- Add the links for Skills, Projects and Recommendation here -->

        </div>
      </div>    
    </nav>

    <!-- About Me -->
    <section id="about-me" class="container">
      <div>
        <img src="https://i.ibb.co/ZmBR4Gy/cosmic-sunday-logo-black-white-white-text-abrv-sticker.png" alt="cosmic-sunday-logo-black-white-white-text-abrv-sticker" class="profile_image/">
      </div>

      <div>
          <h1>
            Alya Rees
          </h1>
          <p>
            Aspiring Freelance Web Developer <br> <br> Creative Writing <br> <br> HTML, CSS &amp; JavaScript <br> <br> Journalism, Proof Reading &amp; Editing <br> <br> Cloud Computing <br> <br> Animation &amp; Video Automation <br> <br> Digital Marketing &amp; Content Creation 
          </p>
      </div>
    </section>
              
    <!-- Skills -->
    <section id="skills">
      <h2>Skills</h2>
      <div style="clear:both;"></div>

      <div class="all_skills">
        <div class="skill">
          <img src="html_finalprojimages/html5.png">
          <h6>HTML</h6>
        </div>  

        <div class="skill">
          <img src="html_finalprojimages/js.jpeg">
          <h6>JavaScript</h6>
        </div>  

        <div class="skill">
            <img src="https://1000logos.net/wp-content/uploads/2020/09/CSS-Logo.jpg">
            <h6>CSS</h6>
          </div> 

          <div class="skill">
            <img src="https://cdn-icons-png.flaticon.com/512/1973/1973879.png">
            <h6>Creative Writing</h6>
          </div>  

          <div class="skill">
            <img src="https://as2.ftcdn.net/v2/jpg/03/78/20/11/1000_F_378201105_NjrTzOP3Upq9zQ7EtT7kXC9Fft6cSTbg.jpg">
            <h6>Journalism, Proof Reading &amp; Editing</h6>
          </div>
          
          <div class="skill">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR0Lv61TBfMQJme6x2fqV24L-oNGoJUJ0FgdUiG76sMcg&amp;s">
            <h6>Cloud Computing</h6>
          </div> 

          <div class="skill">
            <img src="https://static.thenounproject.com/png/3890911-200.png">
            <h6>Animation &amp; Video Automation</h6>
          </div> 

          <div class="skill">
            <img src="https://png.pngtree.com/png-clipart/20230504/original/pngtree-sales-marketing-line-icon-png-image_9137786.png">
            <h6>Digital Marketing &amp; Content Creation</h6>
          </div> 
        <!-- Add more skills here -->


      </div>
    </section>
          
    <!-- Projects -->
    <section class="projects" id="projects">
      <h2>
        Projects
      </h2>
      <div style="clear:both;"></div>

        <div id="projects-container" class="projects-container">
          <div class="project-card">
            <h3>Online Business</h3>
            <ul>
              <li>By age 14 I had my own Instagram-based online business with over +50k followers and fruitful sales through an associated online selling platform.</li>
            </ul>
          </div>
          <hr>
          <div class="project-card">
            <h3>Creating a webpage</h3>
            <ul>
              <li>Developed, styled and edited a web page through IBM services using JavaScript, HTML and CSS.</li>
            </ul>
          </div>
          <hr>
          <div class="project-card">
            <h3>Journalism - Proof Reading &amp; Editing</h3>
            <ul>
              <li>Onsite work experience proof reading, editing and writing for a local new paper.</li>
            </ul>
          </div>
    </div>
    </section>
    <div style="clear:both;"></div>

    <!-- Recommendations -->
    <section id="recommendations">
      <h2>Recommendations</h2>
      <div style="clear:both;"></div>
      <div class="all_recommendations" id="all_recommendations">
        <div class="recommendation">
          <span>“</span>
          Alya has great problem solving skills and is a very fast learner. She has a great understanding of Web Development key concepts and is always eager to learn!
          <span>”</span>
        </div>
        <div class="recommendation">
          <span>“</span>
          I recently hired Alya to help me develop my first webpage for my developing small business. She was highly committed to the project throughout the entire process and always provided great customer service and speedy responses!
          <span>”</span>
        </div>
        <div class="recommendation">
          <span>“</span>
          When working with Alya she was always consistent in delivering high-quality work on time. I highly recommend hiring Alya as a freelancer!
          <span>”</span>
        </div>
        <div class="recommendation">
            <span>“</span>
            Working with Alya has been nothing but pleasant and smooth sailing. She is an amazing freelancer and has proved that she would to be a real asset to any company.
            <span>”</span>
          </div>
      </div>
    </section>

    <!-- Recommendation Form -->
    <section id="contact">
      <div class="flex_center">
        <fieldset>
          <legend class="introduction">Leave a Recommendation</legend>          
          <input type="text" placeholder="Name (Optional)"> <br>
          <textarea id="new_recommendation" cols="500" rows="10" placeholder="Message"></textarea>
          <div class="flex_center">
            <button id="recommend_btn" onclick="addRecommendation()">Submit</button>
          </div>
        </fieldset>
      </div>
    </section>

    <div class="iconbutton">
      <a href="#home">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="white" width="63px">
            <path stroke-linecap="round" stroke-linejoin="round" d="M15 11.25l-3-3m0 0l-3 3m3-3v7.5M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path>
          </svg>
        <!--Add the code here for the logo to appear and the icon to be actionable-->
      </a>
    </div>

    <div class="popup" id="popup">
      <img src="html_finalprojimages/checkmark--outline.svg">
      <h3>Thanks for leaving a recommendation</h3>
      <button onclick="showPopup(false)">Ok</button>
    </div>
  

</body></html>
