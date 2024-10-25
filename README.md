# imomotimi
My assigment project
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Onepage Website</title>
    <link rel="stylesheet" href="asset/css/style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <link id="themeStyle" rel="stylesheet" href="asset/css/light.css">

</head>

<body>
    <header class="section1">
        <div id="main">
            <img src="../OnePageWebsite/asset/images/logo.png" alt="culture" width="80px" class="logo">
            <nav>
                <ul class="lists">
                    <li><a href="#intro">intro</a></li>
                    <li><a href="#countdown">countdown</a></li>
                    <li><a href="#note">notes</a></li>
                    <li><a href="#location">location</a></li>
                    <li><a href="#contact">contact</a></li>
                </ul>
            </nav>

              <!-- Theme Toggle Switch -->
              <div class="toggleswitch">
                <i class="fa-solid fa-moon" id="toggleIcon"></i>
                <button onclick="toggleTheme()" id="themeToggleBtn">
                    <i class="fa-solid fa-toggle-on" id="toggle"></i>
                </button>
                <i class="fa-solid fa-sun"></i>
            </div>
            
        <!-- </div> -->
           <!-- <div class="toggleswitch">
            <i class="fa-solid fa-moon moon"></i>
            <button onclick="switchToDark()" ondblclick="switchToLight()">
                <i class="fa-solid fa-toggle-on toggle-on" id="toggle"></i>
            </button>
            <i class ="fa-solid fa-sun sun"></i> -->
    <!-- <i class="fa-solid fa-toggle-off" id="moonIcon" onclick="switchToDark()"></i>
    <i class="fa-solid fa-sun" id="sunIcon" ondblclick="switchToLight()"></i> -->
<!-- </div> -->

            <button class="call-us-btn"><i class="fa fa-phone-volume"></i> Call Us</button>
            <!-- <button class="button1">Call Us</button> -->


            <i class="fa-solid fa-bars fa-2xl" id="bar"></i>
        </div>
        
    <h5 id="greeting">Welcome!</h5> <!-- This is where the greeting will be displayed -->
        <p class="first-text" id="intro"><i>imomotimi foundation presents</i></p>
        <h1 class="second-text">imomotimi ijaw</h1>
        <h1 class="third-text">dance contest 2024</h1>
        <!-- Download Entry Form Button -->
<!-- <button class="button2" onclick="openPopup()">Download Entry Form <i class="fa-solid fa-download fa" style="padding-left: 5px;"></i></button> -->

<!-- Pop-up Form
<div id="popupForm" class="popup-form">
    <div class="popup-content">
        <span class="close" onclick="closePopup()">&times;</span>
        <h2>Download Entry Form</h2>
        <p>Please fill out the form below to receive the entry form.</p>
        <form id="entryForm">
            <div class="form-group">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
            </div>
            <div class="form-group">
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
            </div>
            <button type="submit" class="submit-btn">Submit</button>
        </form>
    </div>
</div> -->

<!-- Download Entry Form Button --> 
<button class="button2" onclick="openPopup()">Download Entry Form <i class="fa-solid fa-download fa" style="padding-left: 5px;"></i></button>

<!-- Pop-up Form -->
<div id="popupForm" class="popup-form">
    <div class="popup-content">
        <span class="close" onclick="closePopup()">&times;</span>
        <h2>Download Entry Form</h2>
        <p>Please fill out the form below to receive the entry form.</p>
        <form id="entryForm">
            <div class="form-group">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
            </div>
            <div class="form-group">
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
            </div>
            <button type="submit" class="submit-btn">Submit</button>
        </form>
    </div>
</div>


                
        <p class="last-p">All duly filled out forms and the entry fees should be brought along to the audition</p>
        <a href="#">
            <i class="fa fa-computer-mouse" id="coffee"></i></a>
        <img id="topWhite" src="asset/images/shape-top-white-80.png" class="img2" alt="wave">

    </header>
    <main>
        <section class="section2" id="countdown">
            <div class="countdown">
                <h1 class="section2-h1">Countdown to Audition</h1>
                <div class="time-container">
                    <div class="time-box">
                        <span class="number" id="days">29</span>
                        <hr style="width: 27px;">
                        <p class="label">Days</p>
                    </div>
                    <div class="separator">:</div>
                    <div class="time-box">
                        <span class="number" id="hours">02</span>
                        <hr style="width: 27px;">
                        <p class="label">Hours</p>
                    </div>
                    <div class="separator">:</div>
                    <div class="time-box">
                        <span class="number" id="minutes">08</span>
                        <hr style="width: 27px;">
                        <p class="label">Minutes</p>
                    </div>
                    <div class="separator">:</div>
                    <div class="time-box">
                        <span class="number" id="seconds">06</span>
                        <hr style="width: 27px;">
                        <p class="label">Seconds</p>
                    </div>
                </div>
            </div>

            <!-- <div id="countdown">
                <span id="days">0</span> Days 
                <span id="hours">0</span> Hours 
                <span id="minutes">0</span> Minutes 
                <span id="seconds">0</span> Seconds
            </div> -->
            <img id="topGrey" src="asset/images/shape-top-grey-80.png" class="img3" alt="wave">
        </section>
        <section class="section3">
            <div class="important-things" id="note">
                <h1 style="font-size: 42px;">
                    Important things <br>to note...
                </h1>
            </div>
            <div class="Pricing">
                <i class="fa-solid fa-money-bill-wave fa-2xl" style="color: #8B0000;"></i>
                <h3 style="font-size: 25px;">Pricing</h3>
                <p class="pricing-p" style="opacity: 0.5;">Audition forms are available for <br>₦1,000 for single
                    contestants,<br> and ₦1,500 for a group
                    of five.</p>
            </div>
            <div class="prizes">
                <i class="fa-solid fa-trophy fa-2xl" style="color: #8B0000"></i>
                <h3 style="font-size: 25px;">Prizes</h3>
                <p class="p-content" style="opacity: 0.5;"><strong>1st Prize:</strong> <strong>₦</strong>2,000,000</p>
                <p class="p-content" style="opacity: 0.5;"><strong>2nd Prize:</strong> <strong>₦</strong>1,000,000</p>
                <p class="p-content" style="opacity: 0.5;"><strong>3rd Prize:</strong> <strong>₦</strong>500,000</p>
            </div>
        </section>
        <section class="iframe" id="location">
            <iframe
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d15900.206238978464!2d6.310665551482393!3d4.931030920719006!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x106a055be1dcce59%3A0xa6c5b6a97ac6c1a!2sNitro%20Studios!5e0!3m2!1sen!2sng!4v1727526895070!5m2!1sen!2sng"
                width="100%" height="550" style="border:0;" allowfullscreen="" loading="lazy"
                referrerpolicy="no-referrer-when-downgrade"></iframe>

           
            <img id="topGreyBottom" src="asset/images/shape-top-grey-80.png" class="img-4" alt="wave">
        </section>
        <section id="greySection">
            <div class="info" id="contact">
                <div class="main-info">
                    <h3>For More Information:</h3>
                    <p><strong>Hotlines:</strong> 07035973706 | 08108112759</p><br>
                    <p><strong>Email:</strong> info@ijawdancecontest.ng</p><br>
                    <p><strong>Audition Location:</strong> Nitro Studio,<br> Tamara Hall, Otiotio Road, Yenagoa,<br>
                        Bayelsa State.</p>
                </div>
                <div class="contact-section">
                    <form class="form">
                        <div class="form1">
                            <div class="border">
                                <i class="fa-regular fa-user" style="opacity: 50%;"></i>
                                <input type="text" name="name" placeholder="Name">
                            </div>

                            <div class="border">
                                <i class="fa-regular fa-envelope" style="opacity: 50%;"></i>

                                <input type="email" name="email" placeholder="Email Address">
                            </div>
                        </div>

                        <div class="form2">
                            <div class="border">

                                <i class="fa-solid fa-phone-volume" style="opacity: 50%;"></i>
                                <input type="tel" name="phone" placeholder="Phone">
                            </div>
                            <div class="border">
                                <i class="fa-solid fa-circle-info" style="opacity: 50%"></i>
                                <input type="text" name="subject" placeholder="Subject">
                            </div>
                        </div>

                        <div class="comment">
                            <div class="border">
                                <i class="fa-solid fa-pencil" style="opacity: 50%;"></i>
                                <textarea name="message"
                                    placeholder="How can we help you? Feel free to get in touch!"></textarea>
                            </div>
                        </div>

                        <button class="button3" type="submit">Get in Touch</button>
                    </form>
                </div>
            </div>
        </section>

    </main>
    <footer>
        <div class="footer">
            <p>We Are Social</p>
            <div class="icons">
                <a href="#" class="social-icons">
                    <i class="fa-brands fa-facebook fa"></i>
                </a>
                <a href="#" class="social-icons">
                    <i class="fa-brands fa-twitter fa"></i>
                </a>
                <a href="#" class="social-icons">
                    <i class="fa-brands fa-instagram fa"></i>
                </a>
                <a href="#" class="social-icons">
                    <i class="fa-brands fa-youtube fa"></i>
                </a>
            </div>
             <hr id="footerHr">
                <div>
                    <p class="footer-p">© 2024 Imomotimi Foundation. All Rights Reserved. | Designed by: <a href="#">swiftBrawn</a>
                    </p>
                    <div class="footer-line"> 
                </div>
        </div>
    </footer>
    <a href="#" id="scrollTopBtn" title="Go to top">
        <i class="fas fa-arrow-up"></i>
      </a>
    <script src="asset/js/script.js"></script>
</body>

</html>





