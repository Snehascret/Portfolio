# Portfolio
A modern and responsive portfolio website showcasing personal projects, skills, and achievements. Built using [mention technologies like HTML, CSS, JavaScript, React, etc.


<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>

    <!-- box icons -->
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>

    <!-- Custom css -->
    <link rel="stylesheet" href="style.css">

    <!-- Include jQuery -->
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>

    <!-- Include Firebase SDK -->
    <script src="https://www.gstatic.com/firebasejs/8.3.2/firebase-app.js"></script>
    <script src="https://www.gstatic.com/firebasejs/8.3.2/firebase-database.js"></script>


</head>

<body>
    <!-- header Desing -->
    <header class="header">
        <a href="#" class="logo">Portfolio</a>

        <i class='bx bx-menu' id="menu-icon"></i>

        <nav class="navbar">
            <a href="#home" class="active">Home</a>
            <a href="#about">About</a>
            <a href="#services">Services</a>
            <a href="#portfolio">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- home section design -->

    <section class="home" id="home">
        <div class="home-content">
            <h3>Hello, its me</h3>
            <h1>Sneha Gupta</h1>
            <h3>And I'm a <span class="multi-text"></span></h3>
            <p>I can actively engage in policy advocacy by raising awareness about important
                policy issues and advocating for policy changes. I can utilize their knowledge
                and understanding of technical subjects to inform policymakers and the public
                about the potential consequences of specific policies, bridging the gap between
                technology and policy.</p>
            <div class="social-media">
                <a href="#"><i class='bx bxl-facebook'></i></a>
                <a href="https://www.instagram.com/snehagupta570/"><i class='bx bxl-instagram'></i></a>
                <a href="https://www.linkedin.com/in/sneha-gupta-51241723b/"><i class='bx bxl-linkedin'></i></a>
                <a href="https://github.com/Snehascret"><i class='bx bxl-github'></i></a>
            </div>
            <a href="#"
                class="btn">Download CV</a>
        </div>

        <div class="home-img">
            <img style="border-radius:30%;"
                src="img/Snehaimg.jpg">
        </div>
    </section> 

    <!-- About Section -->

    <section class="about" id="about">
        <div class="about-img">
            <img src="#">
        </div>
        <div class="about-content">
            <h class="heading">About <span>Me</span></h>
            <h3>Full Stack Developer!</h3>
            <p>I often possess strong analytical and research skills. I can contribute by
                conducting thorough research on specific policy areas, gathering data, and
                analysing the implications of different policy options. This research can provide
                valuable insights to policymakers, enabling evidence-based decision-making.
                I have a solid foundation in technology and can leverage my skills to contribute
                to policy discussions on emerging issues such as artificial intelligence,
                cybersecurity, block chain, and data privacy. I can provide technical insights,
                assess the impact of technology on policy domains, and help policymakers
                navigate the complexities of these subjects.
                I am often trained in data analysis and visualization techniques. They can assist
                in interpreting complex datasets, identifying trends, and communicating the
                findings effectively through visualizations. This skill set is valuable for
                policymakers who need to understand and communicate data-driven insights
                to a broader audience.</p>
            <a href="resume.html" class="btn"  style="margin-left: 2rem;">Read More</a>
            <a href="gallery.html" class="btn" style="margin-left: 2.5rem; margin-top: 1rem;">Gallery 1</a>
            <a href="gallery2.html" class="btn" style="margin-left: 2.5rem; margin-top: 1rem;">Gallery 2</a>
        </div>
    </section>

    <!-- Services Section -->

    <section class="services" id="services">
        <h2 class="heading">My<span> Skills</span></h2>
        <div class="service-container">
            <div class="service-box">
                <i class='bx bxl-android'></i>
                <h3>Software Development</h3>
                <p>I propose to develop a high-quality Android application that will provide your users with a seamless
                    and engaging experience. The app will be designed to meet your specific requirements, enhance user
                    engagement, and drive business growth. I am committed to delivering a robust, scalable, and visually
                    appealing mobile application tailored to your brand.</p>
                <a href="#" class="btn">Read more</a>
            </div>
            <div class="service-box">
                <i class='bx bxl-apple'></i>
                <h3>Backend Development</h3>
                <p>I propose to develop a high-quality iOS application that will provide your users with a seamless
                    and engaging experience. The app will be designed to meet your specific requirements, enhance user
                    engagement, and drive business growth. I am committed to delivering a robust, scalable, and visually
                    appealing mobile application tailored to your brand.</p>
                <a href="#" class="btn">Read more</a>
            </div>
            <div class="service-box">
                <i class='bx bx-code-alt'></i>
                <h3>Web Development</h3>
                <p>I propose to create a modern, responsive, and user-friendly website for [Client’s Company]. The
                    website will be designed to enhance your online presence, engage visitors, and drive conversions.
                    My team will focus on creating a visually appealing interface coupled with seamless functionality
                    to ensure an exceptional user experience.</p>
                <a href="#" class="btn">Read more</a>
            </div>
            <div class="service-box">
                <i class='bx bx-palette'></i>
                <h3>Rest API's</h3>
                <p>I am a passionate of creative professional specializing in graphic design. With a keen eye for
                    detail and a dedication to delivering exceptional results, I pride ourselves on our ability to
                    transform ideas into impactful visual communication. Creating visually striking brochures, flyers,
                    posters, and banners to promote your products/services.</p>
                <a href="#" class="btn">Read more</a>
            </div>
            <div class="service-box">
                <i class='bx bxl-netlify'></i>
                <h3>Software Testing</h3>
                <p>I understand the critical importance of ensuring the quality, functionality, database, and security
                    of software
                    applications. With my expertise in software testing, I am confident in my ability to deliver
                    comprehensive testing solutions tailored to your unique requirements.</p>
                <a href="sw_testing_service.html" class="btn">Read more</a>
            </div>
            <div class="service-box">
                <i class='bx bxl-squarespace'></i>
                <h3>Remote Support</h3>
                <p>A remote support job involves providing technical assistance and troubleshooting services to
                    customers or clients from a remote location. Remote support professionals, often known as remote
                    support technicians or help desk agents, play a crucial role in resolving technical issues
                    efficiently and ensuring customer satisfaction.</p>
                <a href="remote_service.html" class="btn">Read more</a>
            </div>
            <!-- <div class="service-box">
                <i class='bx bxs-game'></i>
                <h3>Gaming</h3>
                <p>I am RP_Axel, your friendly neighborhood gamer, explorer of virtual worlds, and master of all things
                    pixelated. From the adrenaline-pumping battles of first-person shooters to the immersive
                    storytelling of open-world RPGs, I’ve traversed countless realms, honing my skills, and embracing
                    the true spirit of gaming.</p>
                <a href="game_service.html" class="btn">Read more</a>
            </div> -->
        </div>
    </section>

    <!-- Portfolio Section -->

    <section class="portfolio" id="portfolio">
        <h2 class="heading">Latest <span>Project</span></h2>
        <div class="portfolio-container">
            <div class="portfolio-box">
                <img src="Image/Screenshot 2024-12-16 111448.png"
                    alt="">
                <div class="portfolio-layer">
                    <h4>Personal Portfolio</h4>
                    <p>It's one of the most practical and memorable ways to share my work with press, potential
                        collaborators or employers.</p>
                    <a href="#"><i class='bx bx-link-external'></i></a>
                </div>
            </div>
            <div class="portfolio-box">
                <img src="Image/Screenshot 2024-12-16 111741.png"
                    alt="">
                <div class="portfolio-layer">
                    <h4>Madhyam Staffing Solutions</h4>
                    <p>Madhyam is a software for the job consultancy and placement where we registered the companies and get their requirement regarding vacancy and arrange interview with the eligible candidate and help them to get perfect employee.</p>
                    <a href="https://madhyam.raydent.in/Userlogin"><i class='bx bx-link-external'></i></a>
                </div>
            </div>
            <div class="portfolio-box">
                <img src="Image/Screenshot 2024-12-16 111448.png"
                    alt="">
                <div class="portfolio-layer">
                    <h4>Jewellery Website</h4>
                    <p>Bhoop Narayan Tanaya kumar is the website for jewellery shopping where you can search your product and buy it and also place your order get the product to your door steps.</p>
                    <a href="https://bhoopnarayanjewellers.com/"><i class='bx bx-link-external'></i></a>
                </div>
            </div>
            <div class="portfolio-box">
                <img src="Image/treco.png"
                    alt="">
                <div class="portfolio-layer">
                    <h4>Treco Arabia</h4>
                    <p>This Website allows showcasing your products to the users and also contact with them through contact for further enquiries .</p>
                    <a href="https://trecoarabia.com/"><i class='bx bx-link-external'></i></a>
                </div>
            </div>
            <div class="portfolio-box">
                <img src="Image/Goel.png"
                    alt="">
                <div class="portfolio-layer">
                    <h4>Goel Superspeciality hospital </h4>
                    <p>This website displays facilities the hospital provided and also you can book appointment with the doctor as their timing and requirments.</p>
                    <a href="https://goelsuperspeciality.com/"><i class='bx bx-link-external'></i></a>
                </div>
            </div>
            <div class="portfolio-box">
                <img src="https://firebasestorage.googleapis.com/v0/b/raviprakash-7b08f.appspot.com/o/Project%2Fproject2.jpg?alt=media&token=1497d68b-d1df-4a7d-8a6b-3e3c920df64b"
                    alt="">
                <div class="portfolio-layer">
                    <h4>E-commerce Website</h4>
                    <p>An engaging and user-friendly e-commerce website designed for seamless shopping experiences and secure transactions.</p>
                    <a href="#"><i class='bx bx-link-external'></i></a>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact">
        <form id="contact">
            <h2 class="heading">Contact <span>Me!</span></h2>

            <div class="alert">Message sent successfully!</div>

            <div class="input-box">
                <input type="text" id="name" placeholder="Full Name" required>
                <input type="email" id="email" placeholder="Email" required>
            </div>

            <div class="input-box">
                <input type="tel" id="number" placeholder="Phone Number">
                <input type="text" id="subject" placeholder="Subject">
            </div>

            <div class="input-box">
                <textarea id="message" cols="30" rows="10" placeholder="Your Message"></textarea>
            </div>
            <button type="submit" class="btn">Submit</button>

        </form>
    </section>

    <!-- Footer Design -->

    <footer class="footer">
        <div class="footer-text">
            <p>Copyright &copy; 2024 by Sneha | All Rights Reserved.</p>
        </div>
        <div class="footer-iconTop">
            <a href="#home"><i class='bx bx-up-arrow-alt'></i></a>
        </div>
    </footer>


    <!-- scroll reveal -->
    <script src="https://unpkg.com/scrollreveal"></script>

    <!-- Firebase -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/firebase/7.14.1-0/firebase.js"></script>

    <!-- Typed JS -->
    <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>

    <!-- Custom JS -->
    <script src="script.js"></script>

</body>

</html>
