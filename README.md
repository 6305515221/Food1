
<!--if you to nabar operations wiyhout using onclick operations we go to href # herer section is not mandetatory-->
<!--if you perform onclick operations no need to use hreaf and section is mendatory-->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous"/>
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
    <script src="https://kit.fontawesome.com/ac42c3b1f7.js" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="pav.css">
</head>
<body>
    <div>
        <nav class="navbar navbar-expand-lg navbar-light bg-primary">
            <div class="container">
                <a class="navbar-brand" href="#" onclick="display('sectionHome-details')">
                    <img src=" https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/vr-logo-img.png" width="50">
                </a>
                <button class="navbar-toggler threebutton " type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                  <span class="navbar-toggler-icon "></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                  <div class="navbar-nav ml-auto">
                    <a class="nav-link active" href="#Home-datails" id="navitem" onclick="display('sectionHome-details')">
                      Home
                      <span class="sr-only">(current)</span>
                    </a>
                    <a class="nav-link heading" href="#sectionAbout-me" id="navitem1" onclick="display('sectionAbout-me')">About me</a>
                    <a class="nav-link heading" href="#sectionSkills" id="navitem2" onclick="display('sectionSkills')">Skills</a>
                    <a class="nav-link heading" href="#sectionProjects" id="navitem3"  onclick="display('sectionProjects')">Projects</a>
                    <a class="nav-link heading" href="#sectionServices" id="navitem4" onclick="display('sectionServices')">Services</a>
                    <a class="nav-link heading" href="#sectionTestimonial" id="navitem5" onclick="display('sectionTestimonial')">Testimonial</a>
                    <a class="nav-link heading" href="#sectionFooter" id="navitem6" onclick="display('sectionFooter')">Contact Details</a>
                    
                  </div>
                </div>
    
            </div>
        </nav>
        <div id="sectionHome-details">
            <div class="backcol d-flex flex-column justify-content-center">
                <div class="container">
                    <div class="row">
                        <div class="col-12 col-md-5 order-1 order-md-2">
                            <div class=" text-center">
                                <img src="C:\Users\pavan\OneDrive\Desktop\RESPONSIVE HTML\protofilo\pavan-modified.png" class="profile-image">
                            </div>
                        </div>
        
                        <div class="col-12 col-md-7 order-1 order-md-1 d-flex flex-column justify-content-center">
                            <div class=" text-center  heading">
                                <h1>Hey, I am Pavan</h1>
                                <p>I am a Python Full Stack Developer</p>
                                <button class="contact-button" onclick="display('sectionFooter')">Contact me</button>
                            </div>
                        </div>
                    </div>
                </div>
    
            </div>
        </div>


        <div id="sectionAbout-me">
            <div class="factsback p-3">
                <div class="container">
                    <div class="row">
                        <div class="col-12 col-md-6 order-1 order-md-2">
                            <h1 class="facts">Facts</h1>
                            <h1 class="about-me">About me</h1>
                            <div class="text-center d-md-none">
                                <img src="D:\IMAGES\pavan.jpg" class="photo-image">
                            </div>
                            <p style="color:white">
                                Detail-oriented and innovative web developer with a passion for crafting responsive and visually appealing websites. Eager 
                                to leverage my skills in HTML, CSS, JavaScript, and front-end frameworks like React.js to create immersive digital 
                                experiences. Committed to staying updated on emerging web technologies and best practices to deliver high-quality, usercentric solutions. Seeking a challenging role where I can contribute my expertise to drive digital innovation and exceed 
                                client expectations
                            </p>
                    
                        </div>

                        <div class="col-12 col-md-6 text-center d-none d-md-block order-1 order-md-1">
                            <img src="D:\IMAGES\pavan.jpg" class="photo-image">
                        </div>
                    </div>
                </div>
            </div>
        </div>


        <div id="sectionSkills">
            <div class="skills-card mt-3">
                <div class="container">
                    <div class="row">
                        <div class="col-12">
                            <h1 class="facts">Skills :</h1>
                        </div>
                        <div class="col-4 col-md-2 shadow mb-3 ">
                            <div class="text-center card-container p-3">
                                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/portfolio-skills-html-img.png"class="w-100">
                                <h1 class="container-heading pt-3">HTML</h1>
                            </div>
                        </div>
    
                        <div class="col-4 col-md-2 shadow mb-3">
                            <div class="text-center card-container p-3">
                                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/portfolio-skills-css-img.png"class="w-100">
                                <h1 class="container-heading pt-3">css</h1>
                            </div>
                        </div>
                        <div class="col-4 col-md-2 shadow mb-3">
                            <div class="text-center card-container p-3">
                                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/portfolio-skills-bootstrap-img.png"class="w-100">
                                <h1 class="container-heading pt-3">Bootstrap</h1>
                            </div>
                        </div>
                        <div class="col-4 col-md-2 shadow mb-3">
                            <div class="text-center card-container p-3">
                                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/portfolio-skills-js-img.png"class="w-100">
                                <h1 class="container-heading pt-3">Javascript</h1>
                            </div>
                        </div>
                        <div class="col-4 col-md-2 shadow mb-3">
                            <div class="text-center card-container p-3">
                                <img src="C:\Users\pavan\OneDrive\Desktop\RESPONSIVE HTML\protofilo\OIP.jpeg"class="w-100">
                                <h1 class="container-heading pt-3">Python</h1>
                            </div>
                        </div>
                        <div class="col-4 col-md-2 shadow mb-3">
                            <div class="text-center card-container p-3">
                                <img src="C:\Users\pavan\OneDrive\Desktop\RESPONSIVE HTML\protofilo\sql-letter-logo-design-on-white-background-sql-creative-circle-letter-logo-concept-sql-letter-design-vector.jpg"class="w-100">
                                <h1 class="container-heading pt-3">Sql</h1>
                            </div>
                        </div>
                        
                    </div>
                </div>
            </div>
        </div>




        <div id="sectionProjects">
            <div class="card-container mt-3">
                <div class="container">
                    <div class="row">
                        <div class="col-12">
                            <h1 class="facts">Portofilo</h1>
                            <h1 class="about-me">Projests i have done</h1>
                        </div>
    
                        <div class="col-12 col-md-6 mb-3">
                            <div class="projexts-container p-3 ">
                                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/foodmunch-banner-bg.png" class="w-100">
                                <p>Web Design</p>
            
                                <h5>Happy Meals</h5>
                                <p>Happy Meals is the best-in-class food ordering page today.with intdractive UI/UX and simple call to actions....</p>
                                <a href="" class="menu-item-link">
                                    View All
                                    <svg width="16px" height="16px" viewBox="0 0 16 16" class="bi bi-arrow-right-short" fill="#d0b200" xmlns="http://www.w3.org/2000/svg">
                                      <path
                                        fill-rule="evenodd"
                                        d="M4 8a.5.5 0 0 1 .5-.5h5.793L8.146 5.354a.5.5 0 1 1 .708-.708l3 3a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708-.708L10.293 8.5H4.5A.5.5 0 0 1 4 8z"
                                      />
                                    </svg>
                                  </a>
                            </div>
                           </div>
            
            
                           <div class="col-12 col-md-6 mb-3">
                            <div class="projexts-container p-3">
                                <img src="C:\Users\pavan\OneDrive\Desktop\RESPONSIVE HTML\protofilo\OIP (1).jpeg" class="w-100">
                                <p>Web Design</p>
            
                                <h5>Podcast</h5>
                                <p>
                                    A podcast is essentially a series of spoken-word audio episodes, often focused on a particular topic or theme, like technology, sports, or storytelling. Think of it as a radio show that you can listen to on-demand, whenever and wherever you want.....
                                </p>
                                <a href="" class="menu-item-link">
                                    View All
                                    <svg width="16px" height="16px" viewBox="0 0 16 16" class="bi bi-arrow-right-short" fill="#d0b200" xmlns="http://www.w3.org/2000/svg">
                                      <path
                                        fill-rule="evenodd"
                                        d="M4 8a.5.5 0 0 1 .5-.5h5.793L8.146 5.354a.5.5 0 1 1 .708-.708l3 3a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708-.708L10.293 8.5H4.5A.5.5 0 0 1 4 8z"
                                      />
                                    </svg>
                                  </a>
                            </div>
                           </div>
            
                    </div>
                    
    
        
                      
                </div>
            </div>
        </div>


        <div id="sectionServices">
            <div class="card-container mt-3">
                <div class="container">
                    <div class="row">
                        <div class="col-12 p-3">
                            <h1 class="facts">Services</h1>
                            <h1 class="service-heading">What i do</h1>

                        </div>

                        <div class="col-12 col-md-6 col-lg-4 mb-3">
                            <div class="projexts-container p-3">
                                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/portfolio-web-design-img.png" class="service-image">
                                <h1 class="service-heading pt-3">Static websites</h1>
                                <p>
                                    A Static Website contains Web pages with
                                    fixed content. Each page is developed using HTML
                                    and CSS and display the same information to every visitor.
                                </p>

                            </div>
                        </div>

                        <div class="col-12 col-md-6 col-lg-4 mb-3">
                            <div class="projexts-container p-3">
                                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/portfolio-web-development-img.png" class="service-image">
                                <h1 class="service-heading pt-3">Responsive Web design</h1>
                                <p>
                                    Responsive Web design is the approach
                                    the suggests that design and development should
                                    respond to the user's behaviour and envinornment based
                                    on screen size, platform and orientation.
                                </p>

                            </div>
                        </div>

                        <div class="col-12 col-md-4 col-lg-4 mb-3">
                            <div class="projexts-container p-3">
                                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/portfolio-customize-img.png" class="service-image">
                                <h1 class="service-heading pt-3">Customisable Layouts</h1>
                                <p>
                                    Customisable sites are templates with set layouts.
                            You may be able to change photos and colors, but your site
                            will look similar to many other sites due to the template. The same goes for...
                                </p>

                            </div>
                        </div>


                    </div>
                </div>
            </div>
        </div>

        <div id="sectionTestimonial">
            <div class="skills-card mt-3">
                <div class="container">
                    <div class="row">
                        <div class="col-12">
                            <h1 class="facts">Testimonal</h1>
                            <h1 class="service-heading">Our Members Says</h1>


                            <div class="col-12 pb-5 shadow card-container text-center">
                                <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
                                    <div class="carousel-inner">
                                        <div class="carousel-item active p-3">
                                            <img src="C:\Users\pavan\OneDrive\Desktop\RESPONSIVE HTML\protofilo\WhatsApp Image 2024-10-08 at 23.33.07_e8f2ee54.jpg" class="cursole-image">
                                            <p class="para-1 p-3">
                                                Pavan is one of the best hard-working developers, and it was a pleasure working with him. Having him on the project certainly made everything run smoother.
                                            </p>
                                            <p class="para-2">
                                                - sudheer, Python Developer
                                            </p>
                                        </div>
                                        <div class="carousel-item p-3">
                                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/portfolio-testimonials-2-img.png" class="cursole-image">
                                            <p class="para-1 p-3">
                                                Pavanis one of the best hard-working developers, and it was a pleasure working with him. Having him on the project certainly made everything run smoother.
                                            </p>
                                            <p class="para-2">
                                                - Gautham, Founder of CocoPay Company
                                            </p>
                                        </div>
                                        <div class="carousel-item p-3">
                                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/portfolio-testimonials-3-img.png" class="cursole-image">
                                            <p class="para-1 p-3">
                                                Pavan is one of the best hard-working developers, and it was a pleasure working with him. Having him on the project certainly made everything run smoother.
                                            </p>
                                            <p class="para-2">
                                                - Gautham, Founder of CocoPay Company
                                            </p>
                                        </div>
                                    </div>
                                    <div class="mt-3 text-right">
                                        <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
                                            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                                            <span class="sr-only">Previous</span>
                                        </a>
                                        <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
                                            <span class="carousel-control-next-icon" aria-hidden="true"></span>
                                            <span class="sr-only">Next</span>
                                        </a>
                                    </div>
                                </div>
                            </div>

                        </div>
                    </div>
                </div>

            </div>
        </div>


        <div id="sectionFooter">
            <div class="background mt-3">
                <div class="container pt-5">
                    <div class="row">
                        <div class="col-12 col-md-3">
                            <div class="d-flex flex-row">
                                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/portfolio-about-me-img.png" class="image" />
                                <div class="ml-3">
                                    <h1 class="head-1">Jenny</h1>
                                    <p class="paraf">Frontend Developer</p>
                                </div>
                            </div>
                        </div>
                        <div class="col-12 col-md-3">
                            <h1 class="head-1 pt-3">Phone No.</h1>
                            <div>
                                <i class="fas fa-phone-alt icon"></i>
                                <span class="paraf ml-2">9876543210</span>
                            </div>
                        </div>
                        <div class="col-12 col-md-3">
                            <h1 class="head-1 pt-3">E-mail</h1>
                            <div>
                                <i class="fas fa-envelope icon"></i>
                                <span class="paraf ml-2">jenny3@gmail.com</span>
                            </div>
                        </div>
                        <div class="col-12 col-md-3">
                            <h1 class="head-1 pt-3">Address</h1>
                            <div>
                                <i class="fas fa-map-marked-alt icon"></i>
                                <span class="paraf ml-2">17 Ayur Vigyan Nagar, New Delhi, India.</span>
                            </div>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-12 back mt-3 pt-2 pb-2 text-center">
                            <i class="fa fa-copyright icon" aria-hidden="true"></i>
                            <span class="paraf">2020 by Jenny Wilson. Created with Bootstrap.</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>



    


    <script
      type="text/javascript"
      src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/js/ccbp-ui-kit.js"
    ></script>
</body>
</html>
