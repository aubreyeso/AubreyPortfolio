<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8" />
    <title>Portfolio Website</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://kit.fontawesome.com/b5a9d02ced.js" crossorigin="anonymous"></script>
</head>
<body>
    

<div id="header">
    <div class="container">
        <nav>
            <img src="myportfolio.web/images/logo.webp" class="logo">
<ul id="sidemenu">
<li><a href="#header">Home</a></li>
<li><a href="#About">About</a></li>
<li><a href="#Services">Services</a></li>
<li><a href="#Portfolio">Portfolio</a></li>
<li><a href="#Contact">Contact</a></li>
<i class="fas fa-times" onclick="closemenu()"></i>
</ul>
<i class="fas fa-bars" onclick="openmenu()"></i>
        </nav>
         <div class="header-text">
  <p>Network Designer and IT Technician</p>
        <h1>Hi I'm <span>Aubrey</span><br> Jozela from South Africa</h1>
    </div>
</div>
<!--------About-------->
<div id="About">
    <div class="container">
        <div class="row">
            <div class="about-col-1">
                <img src="myportfolio.web/images/aubrey.jpg">
            </div>
            <div class="about-col-2">
                <h1 class="sub-title">About Me</h1>
                <p>
                    I am Aubrey Eso Jozela, currently a student at Cape Peninsula University of Technology diong my final year in ICT Diploma, and also obtaining an NQF level 5 certificate in IT System Support at Masifunde Training and Development at Woodstock.
                </p>
                <div class="tab-titles">
                <p class="tab-links active-link" onclick="opentab('skills')">Skills</p>
                 <p class="tab-links" onclick="opentab('experience')">Experience</p>
                  <p class="tab-links" onclick="opentab('education')">Education</p>
                </div>
                <div class="tab-contents active-tab" id="skills">
                    <ul>
                        <li><span>Network Designer</span><br>IT Technician</li>
                        <li><span>HTML</span><br>Building Web</li>
                        <li><span>Packet Tracer</span><br>Designing Network Topology</li>
                    </ul>
                </div>
                <div class="tab-contents" id="experience">
                    <ul>
                        <li><span>2023-2024</span><br>IT System Support at Masifunde Training and Development</li>
                        <li><span>2023-2024</span><br>Satellite Installer Technician subbing at Bua Afrika and Sentec</li>
                        <li><span>2024-2024</span><br>Project in IoT Smart Home Automation at CPUT</li>
                    </ul>
                </div>
            </div>
            <div class="tab-contents" id="education">
                    <ul>
                        <li><span>2016</span><br>Matric at Colana S.S.S</li>
                        <li><span>2018</span><br>The Higher Certiicate in ICT at Cape Peninsula University of Technology(CPUT)</li>
                        <li><span>2021-current</span><br>The Diploma in ICT at Cape Peninsula University of Technology(CPUT)</li>
                    </ul>
                </div>
        </div>
    </div>
</div>
<!-----------services------------>

<div id="services">
    <div class="container">
      <h1 class="sub-title">My Services</h1>  
      <div class="services-list">
         <div>
            <i class="fa-brands fa-sketch"></i>
            <h2>Network Design</h2>
            <p>Utilised test equipment such as signal meters to verify system perfomance during installation or repairs</p>
            <a href="#">learn more</a>
         </div>
         <div>
            <i class="fa-solid fa-code"></i>
            <h2>Web Design</h2>
            <p>Using HTML, CSS, VSCODE, and Java script</p>
            <a href="#">learn more</a>
         </div>
         <div>
            <i class="fa-solid fa-gear"></i>
            <h2>Network Configuration</h2>
            <p>Managing a network and its devices by applying the right set of policies, controls, and configurations.</p>
            <a href="#">learn more</a>
         </div>
      </div>
    </div>
</div>




<!--------Portfolio--------->
<div id="portfolio">
<div class="container">
    <h1 class="sub-title">My Work</h1>
    <div class="work-list">
        <div class="work">
            <img src="myportfolio.web/images/IoT tools.jpg">
            <div class="layer">
                <h3>IoT equipments</h3>
                <p>hardwares that connect wirelessly to the internet or a local network hub</p>
                <a href="#">learn more</a>
            </div>

        </div>
         <div class="work">
            <img src="myportfolio.web/images/sensor.jpg">
            <div class="layer">
                <h3>Distance sensor</h3>
                <p>hardwares that connect wirelessly to the internet or a local network hub</p>
                <a href="#">learn more</a>
            </div>

        </div>
         <div class="work">
            <img src="myportfolio.web/images/sensor2.jpg">

<div class="layer">
                <h3>UDS</h3>
                <p>electronic devices that calculate the target’s distance by emission of ultrasonic sound waves and convert those waves into electrical signals.</p>
                <a href="#">learn more</a>
            </div>
        </div>
         <div class="work">
            <img src="myportfolio.web/images/tool.jpg">
            <div class="layer">
                <h3>PIR sensor</h3>
                <p>Here, the pyroelectric sensor is capable of detecting different infrared radiation levels.</p>
                <a href="#">learn more</a>
            </div>

        </div>
    </div>
    <a href="#" class="btn">See More</a>
</div>
</div>
<!---------contact-------->
<div id="contact">
    <div class="container">
        <div class="row">
            <div class="contact-left">
                <h1 class="sub-title">Contact Me</h1>
                <p><i class="fa-solid fa-paper-plane"></i>aubreyeso96@gmail.com</p>
                <p><i class="fa-solid fa-phone"></i>0734062960</p>
                <div class="social-icons">
                    <a href="https://web.facebook.com/"><i class="fa-brands fa-facebook"></i></a>
                    <a href=""><i class="fa-brands fa-twitter-square"></i></a>
                    <a href=""><i class="fa-brands fa-instagram"></i></a>
                    <a href="https://web.whatsapp.com/"><i class="fa-brands fa-whatsapp"></i></a>
                    <a href="www.linkedin.com/in/
aubrey-eso-b43b63182
"><i class="fa-brands fa-linkedin"></i></a>
                </div>
                <a href="myportfolio.web/images/CV of Aubrey .pdf" download class="btn btn2">Download CV</a>

                <div class="contact-right">
                    <form>
                        <input type="text" name="Name" placeholder="Your Name" required>
                        <input type="email" name="Email" placeholder="Your Emial" required>
                        <textarea name="Message" rows="6" placeholder="Your Message"></textarea>
                        <button type="submit" class="btn btn2">Submit</button>
                    </form>
                </div>
            </div>
        </div>
    </div>
    <div class="copyright">
        <p>Copyright @ Aubrey E Jozela. Made with<i class="fa-solid fa-heart"></i> VsCode</p>
    </div>
</div>




<script>



    
var tablinks = document.getElementsByClassName("tab-links");
var tabcontents = document.getElementsByClassName("tab-contents");

function opentab(tabname){
    for(tablink of tablinks){
        tablink.classList.remove("active-link");
    }
    for(tabcontent of tabcontents){
        tabcontent.classList.remove("active-tab");
    }
    event.currentTarget.classList.add("active-link");
    document.getElementById(tabname).classList.add("active-tab");
}
</script>

<script>

var sidemenu = document.getElementById("sidemenu");

function openmenu(){
    sidemenu.style.right = "0";
}
function closemenu(){
    sidemenu.style.right = "-200px";
}


</script>

</body>
</html>
