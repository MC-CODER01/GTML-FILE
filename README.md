!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio - CodeCreators</title>
  <link rel="stylesheet" href="index.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/solid.min.css">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@iconscout/unicons@4.0.8/css/line.min.css">
</head>
<body>
  <!---Nav menu---->
  <div class="container"></div>
  <nav id="header">
    <div class="nav-logo">
      <p class="nav-name">Logo</p>
    </div>
    <div class="nav-menu"  id="myNavMenu">
      <ul class="nav_menu_list">
        <li class="nav_list">
          <a href="#home" class="nav_link active-link">Home</a>
          <div class="circle"></div>
        </li>
        <li class="nav_list">
          <a href="#about" class="nav_link ">About</a>
          <div class="circle"></div>
        </li>
        <li class="nav_list">
          <a href="#projects" class="nav_link ">Projects</a>
          <div class="circle"></div>
        </li>
        <li class="nav_list">
          <a href="#contact" class="nav_link ">Contact</a>
          <div class="circle"></div>
        </li>
      </ul>
    </div>
  <!----Dark Mode---->
  <div class="mode">
    <div class="moon-sun" id="toggle-switch">
      <i class="fa fa-moon"  id="moon"></i>
      <i class="fa fa-sun"  id="sun"></i>
    </div>
  </div>
  <div class="nav-menu-btn">
    <i class="uil uil-bars" onclick="myMenuFunction()"></i>
  </div>
  </nav>

  <!---main--->

  <main class="wrapper">
    <section class="feartured-box" id="home">
      <div class="featured-text">
        <div class="hello">
          <p>Hello I'm</p>
        </div>
        <div class="featured-name">
          <span class="typedText"></span>
        </div>
        <div class="text-info">
          <p>My name is Chiemezie Michael Chidubem! I'm a passionate web developer with experience in creating dynamic and responsive websites. I love coding and am constantly learning new technologies to enhance my skills</p>
        </div>
        <div class="text-btn">
          <button class="btn hire-btn">Hire Me</button>
          <button class="btn">Download CV<i class="uil uil-file"></i></button>
        </div>
        <div class="socical_icons">
          <div class="icon_circle"></div>
          <div class="icon"><i class="uil uil-instagram"></i></div>
          <div class="icon"><i class="uil uil-linkedin-alt"></i></div>
          <div class="icon"><i class="uil uil-behance-alt"></i></div>
          <div class="icon"><i class="uil uil-github-alt"></i></div>
      </div>
      </div>
      <div class="featured-image">
        <div class="image">
          <img src="fufu.jpg" alt="">
        </div>
      </div>
    </section>
    <!----about box---->
    <section class="section"  id="about">
      <div class="top-header">
        <h1>About Me</h1>
      </div>
      <div class="row">
        <div class="col">
          <div class="about-info">
            <figure class="about-me">
              <figcaption>
                <img src="prob.png" alt="" class="profile" />
<h2>Web Developer</h2>
<p>My name is Chiemezie Michael Chidubem! I'm a passionate web developer with experience in creating dynamic and responsive websites. I love coding and am constantly learning new technologies to enhance my skills</p>
            </figure>
            <button class="about-me-btn">Hire me</button>
          </div>
        </div>
        <div class="skill">
          <div class="skill-box">
            <span cllass="title">HTML</span>
            <div class="skill-bar html">
              <span class="skill-per">
              <span class="tooltip">80%</span>
            </span>
            </div>
          </div>
          <div class="skill-box">
            <span class="title">CSS</span>
            <div class="skill-bar css">
              <span class="skill-per">
              <span class="tooltip">80%</span>
            </span>
            </div>
          </div>
          <div class="skill-box">
            <span class="title">Python</span>
            <div class="skill-bar ">
              <span class="skill-per python">
              <span class="tooltip">70%</span>
            </span>
            </div>
          </div>
          <div class="skill-box">
            <span class="title">JavaScript</span>
            <div class="skill-bar">
              <span class="skill-per javascript">
              <span class="tooltip">40%</span>
            </span>
            </div>
          </div>
          <div class="skill-box">
            <span class="title">PHP</span>
            <div class="skill-bar">
              <span class="skill-per php">
              <span class="tooltip">30%</span>
            </span>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!----projects box---->
    <section class="section" id="projects">
      <div class="top-header">
        <h1>Projects</h1>
      </div>
      <div class="project-container">
        <div class="project-box">
          <i class="uil uil-briefcase-alt"></i>
          <h3>Project 1</h3>
          <label>CodeGenie:
            CodeGenie is an AI-powered platform that helps programmers debug, optimize, and learn coding efficiently. It identifies errors, suggests solutions, and provides step-by-step explanations tailored to the user’s expertise. The platform supports multiple programming languages and features a collaborative workspace for real-time coding and knowledge sharing.
          </label>
        </div>
        <div class="project-box">
          <i class="uil uil-users-alt"></i>
          <h3>Project 2</h3>
          <label>SmartCode: SmartCode is an automated web application that streamlines the code review process for developers. It uses machine learning to analyze code for errors, efficiency, and adherence to best practices. The platform provides instant feedback, offers improvement suggestions, and generates detailed reports, helping developers improve code quality and speed up the review process.</label>
        </div>
        <div class="project-box">
          <i class="uil uil-award"></i>
          <h3>Projects 3</h3>
          <label>CyberGuard: CyberGuard is a cutting-edge, AI-powered security platform designed to detect, analyze, and prevent cyber threats in real time. Using advanced machine learning algorithms, CyberGuard continuously monitors network traffic and user behavior to identify unusual patterns that could indicate security breaches. The system offers automated threat responses, generates detailed reports, and provides actionable insights to strengthen security protocols. </label>
        </div>
      </div>
    </section>
<!----contact box---->
<section class="section" id="contact">
  <div class="top-header">
    <h1>Let's Work Together</h1>
    <span>Do You Have A Project In Your Mind, contact me here</span>
  </div>
  <div class="row">
    <div class="col">
      <div class="contact-info">
        <h2>Find me <i class="uil uil-corner-right- down"></i></h2>
        <p><i class="uil uil-envelope"></i>Email: michaelchiemezie02@gmail.com</p>
        <p><i class="uil uil-phone"></i>Phone: +2348163525196</p>
      </div>
    </div>
    <div class="col">
      <div class="form-control">
        <div class="form-inputs">
          <input type="text" class="input-field" placeholder="Your Name" />
          <input type="text" class="input-field" placeholder="Your Email" />
        </div>
        <div class="text-area">
          <input type="text" class="input-subject" placeholder="Your Subject" >
          <textarea placeholder="Message"></textarea>
        </div>
        <div class="form-button">
          <button class="btn">Send<i class="uil uil-message"></i></button>
        </div>
      </div>
    </div>
  </div>
</section>
  </main>
  <!----Footer---->
    <footer>
      <div class="middle-footer">
        <ul class="footer-menu">
          <li class="footer_menu_list">
            <a href="#home">Home</a>
          </li>
          <li class="footer_menu_list">
            <a href="#about">About</a>
          </li>
          <li class="footer_menu_list">
            <a href="#projects">Projects</a>
          </li>
          <li class="footer_menu_list">
            <a href="#contact">Contact</a>
          </li>
        </ul>
      </div>
      <div class="footer-social-icons">
        <div class="icon"><i class="uil uil-instagram"></i></div>
        <div class="icon"><i class="uil uil-linkedin-alt"></i></div>
        <div class="icon"><i class="uil uil-behance-alt"></i></div>
        <div class="icon"><i class="uil uil-github-alt"></i></div>
      </div>
      <div class="bottom-footer">
        <p>Copyright &copy; <a href="#home" style="text-decoration: none;">CodeCreators</a> - All rights reserved 2025</p>
           </div>
      </footer>
   </div>
  
   <script src="https://cdnjs.cloudflare.com/ajax/libs/typed.js/2.1.0/typed.umd.js"></script>
   <script src="https://cdnjs.cloudflare.com/ajax/libs/scrollReveal.js/4.0.9/scrollreveal.min.js"></script>
   <script src="script.js"></script>
</body>
</html>
