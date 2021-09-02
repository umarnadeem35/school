<html lang="en">
  <head>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
<script>
$(document).ready(function(){
  // Add smooth scrolling to all links
  $("a").on('click', function(event) {

    // Make sure this.hash has a value before overriding default behavior
    if (this.hash !== "") {
      // Prevent default anchor click behavior
      event.preventDefault();

      // Store hash
      var hash = this.hash;

      // Using jQuery's animate() method to add smooth page scroll
      // The optional number (800) specifies the number of milliseconds it takes to scroll to the specified area
      $('html, body').animate({
        scrollTop: $(hash).offset().top
      }, 800, function(){

        // Add hash (#) to URL when done scrolling (default click behavior)
        window.location.hash = hash;
      });
    } // End if
  });
});
</script>
    <meta http-equiv="content-type" content="text/html; charset=utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta name="description" content="">
    <meta name="author" content="">
    <title>Programmer's World</title>
    <!-- Font Awesome icons (free version)-->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.13.0/js/all.min.js"
crossorigin="anonymous"></script>
    <!-- Core theme CSS (includes Bootstrap)-->
    <link href="css/styles1.css" rel="stylesheet">
    <!-- Fonts CSS-->
    <link rel="stylesheet" href="css/heading.css">
    <link rel="stylesheet" href="css/body.css">
    <link rel="shortcut icon" href="https://img.icons8.com/color/48/000000/globe--v1.png">
  </head>
  <body id="page-top">
    <nav class="navbar navbar-expand-lg bg-secondary fixed-top" id="mainNav">
      <div class="container"><a class="navbar-brand js-scroll-trigger" href="#page-top">Programmer's
          World</a> <button class="navbar-toggler navbar-toggler-right font-weight-bold bg-primary text-white rounded"
          type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive"
          aria-expanded="false" aria-label="Toggle navigation">Menu <i class="fas fa-bars"></i></button>
        <div class="collapse navbar-collapse" id="navbarResponsive">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item mx-0 mx-lg-1"> <br>
            </li>
            <li class="nav-item mx-0 mx-lg-1"><a class="nav-link py-3 px-0 px-lg-3 rounded js-scroll-trigger"
                href="#about">ABOUT</a> </li>
            <li class="nav-item mx-0 mx-lg-1"><a class="nav-link py-3 px-0 px-lg-3 rounded js-scroll-trigger"
                href="#contact">Contact Us</a> </li>
          </ul>
        </div>
      </div>
    </nav>
    <header class="masthead bg-primary text-white text-center">
      <div class="container d-flex align-items-center flex-column">
        <!-- Masthead Avatar Image--><img class="masthead-avatar mb-5" src="assets/img/skatter-programmer_still_2x.png"
          alt="">
        <!-- Masthead Heading-->
        <h1 class="masthead-heading mb-0">Welcome to Programmer's World!</h1>
        <!-- Icon Divider-->
        <div class="divider-custom divider-light">
          <div class="divider-custom-line"></div>
          <div class="divider-custom-icon"><i class="fas fa-star"></i></div>
          <div class="divider-custom-line"></div>
        </div>
        <!-- Masthead Subheading-->
        <p class="pre-wrap masthead-subheading font-weight-light mb-0"> </p>
      </div>
    </header>
    <section class="page-section portfolio" id="portfolio">
      <div class="container">
        <!-- Portfolio Section Heading-->
        <div class="text-center">
          <h2 class="page-section-heading text-secondary mb-0 d-inline-block"></h2>
        </div>
        <!-- Icon Divider-->
        <div class="divider-custom">
          <div class="divider-custom-line"></div>
          <div class="divider-custom-icon"><i class="fas fa-star"></i></div>
          <div class="divider-custom-line"></div>
        </div>
        <!-- Portfolio Grid Items-->
        <div class="row justify-content-center">
          <!-- Portfolio Items-->
          <div class="col-md-6 col-lg-4 mb-5">
            <div class="portfolio-item mx-auto" data-toggle="modal" data-target="#portfolioModal0">
              <div class="portfolio-item-caption d-flex align-items-center justify-content-center h-100 w-100">
                <div class="portfolio-item-caption-content text-center text-white"><i
                    class="fas fa-plus fa-3x"></i></div>
              </div>
              <img src="https://img.icons8.com/ios-filled/300/000000/laptop-coding.png">
            </div>
          </div>
          <div class="col-md-6 col-lg-4 mb-5">
            <div class="portfolio-item mx-auto" data-toggle="modal" data-target="#portfolioModal1">
              <div class="portfolio-item-caption d-flex align-items-center justify-content-center h-100 w-100">
                <div class="portfolio-item-caption-content text-center text-white"><i
                    class="fas fa-plus fa-3x"></i></div>
              </div>
              <img class="img-fluid" src="https://img.icons8.com/fluency/300/000000/create.png">
            </div>
          </div>
          <div class="col-md-6 col-lg-4 mb-5">
            <div class="portfolio-item mx-auto" data-toggle="modal" data-target="#portfolioModal2">
              <div class="portfolio-item-caption d-flex align-items-center justify-content-center h-100 w-100">
                <div class="portfolio-item-caption-content text-center text-white"><i
                    class="fas fa-plus fa-3x"></i></div>
              </div>
              <img class="img-fluid" src="https://img.icons8.com/dusk/300/000000/woman-at-computer.png">
            </div>
          </div>
          <div class="col-md-6 col-lg-4 mb-5">
            <div class="portfolio-item mx-auto" data-toggle="modal" data-target="#portfolioModal4">
              <div class="portfolio-item-caption d-flex align-items-center justify-content-center h-100 w-100">
                <div class="portfolio-item-caption-content text-center text-white"><i
                    class="fas fa-plus fa-3x"></i></div>
              </div>
            </div>
          </div>
          <div class="col-md-6 col-lg-4 mb-5">
            <div class="portfolio-item mx-auto" data-toggle="modal" data-target="#portfolioModal5"><br>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Portfolio Modal-->
    <div class="portfolio-modal modal fade" id="portfolioModal0" tabindex="-1" role="dialog"
      aria-labelledby="#portfolioModal0Label" aria-hidden="true">
      <div class="modal-dialog modal-xl" role="document">
        <div class="modal-content"> <button class="close" type="button" data-dismiss="modal"
            aria-label="Close"><span aria-hidden="true"><i class="fas fa-times"></i></span></button>
          <div class="modal-body text-center">
            <div class="container">
              <div class="row justify-content-center">
                <div class="col-lg-8">
                  <!-- Portfolio Modal - Title-->
                  <h2 class="portfolio-modal-title text-secondary mb-0">Programming
                    Languages</h2>
                  <!-- Icon Divider-->
                  <div class="divider-custom">
                    <div class="divider-custom-line"></div>
                    <div class="divider-custom-icon"><i class="fas fa-star"></i></div>
                    <div class="divider-custom-line"></div>
                  </div>
                  <!-- Portfolio Modal - Image--><img class="img-fluid rounded mb-5"
                    src="https://img.icons8.com/ios-filled/300/000000/laptop-coding.png">
                  <!-- Portfolio Modal - Text-->
                  <p class="mb-5">This button will take you to Programming
                    Languages</p>
                  <a class="btn btn-primary btn-lg px-4 me-sm-3" href="programming-languages.html">Lets
                    Go! </a> </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="portfolio-modal modal fade" id="portfolioModal1" tabindex="-1" role="dialog"
      aria-labelledby="#portfolioModal1Label" aria-hidden="true">
      <div class="modal-dialog modal-xl" role="document">
        <div class="modal-content"> <button class="close" type="button" data-dismiss="modal"
            aria-label="Close"><span aria-hidden="true"><i class="fas fa-times"></i></span></button>
          <div class="modal-body text-center">
            <div class="container">
              <div class="row justify-content-center">
                <div class="col-lg-8">
                  <!-- Portfolio Modal - Title-->
                  <h2 class="portfolio-modal-title text-secondary mb-0">How to
                    make an HTML website </h2>
                  <!-- Icon Divider-->
                  <div class="divider-custom">
                    <div class="divider-custom-line"></div>
                    <div class="divider-custom-icon"><i class="fas fa-star"></i></div>
                    <div class="divider-custom-line"></div>
                  </div>
                  <!-- Portfolio Modal - Image--><img class="img-fluid rounded mb-5"
                    src="https://img.icons8.com/fluency/240/000000/create.png">
                  <!-- Portfolio Modal - Text-->
                  <p class="mb-5">This button will make you learn "making a
                    website".</p>
                  <a class="btn btn-primary btn-lg px-4 me-sm-3" href="Making a website.html">Learn!
                    </a> </div> </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="portfolio-modal modal fade" id="portfolioModal2" tabindex="-1" role="dialog"
      aria-labelledby="#portfolioModal2Label" aria-hidden="true">
      <div class="modal-dialog modal-xl" role="document">
        <div class="modal-content"> <button class="close" type="button" data-dismiss="modal"
            aria-label="Close"><span aria-hidden="true"><i class="fas fa-times"></i></span></button>
          <div class="modal-body text-center">
            <div class="container">
              <div class="row justify-content-center">
                <div class="col-lg-8">
                  <!-- Portfolio Modal - Title-->
                  <h2 class="portfolio-modal-title text-secondary mb-0">What you
                    can create with different programming languages </h2>
                  <!-- Icon Divider-->
                  <div class="divider-custom">
                    <div class="divider-custom-line"></div>
                    <div class="divider-custom-icon"><i class="fas fa-star"></i></div>
                    <div class="divider-custom-line"></div>
                  </div>
                  <!-- Portfolio Modal - Image--><img class="img-fluid rounded mb-5"
                    src="https://cdn.dribbble.com/users/1162077/screenshots/4649464/skatter-programmer_still_2x.gif?compress=1&amp;resize=400x300"
                    portfolio="" modal="" -="" text--="">
                  <p class="mb-5">Click on this button to see what can you
                    create with different programming languages</p>
                  <a class="btn btn-primary btn-lg px-4 me-sm-3" href="Creating.html">See!
                    </a> </div> </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="portfolio-modal modal fade" id="portfolioModal3" tabindex="-1" role="dialog"
      aria-labelledby="#portfolioModal3Label" aria-hidden="true">
      <div class="modal-dialog modal-xl" role="document">
        <div class="modal-content"> <button class="close" type="button" data-dismiss="modal"
            aria-label="Close"><span aria-hidden="true"><i class="fas fa-times"></i></span></button>
          <div class="modal-body text-center">
            <div class="container">
              <div class="row justify-content-center">
                <div class="col-lg-8">
                  <!-- Portfolio Modal - Title-->
                  <h2 class="portfolio-modal-title text-secondary mb-0">Find the
                    language you need.</h2>
                  <!-- Icon Divider-->
                  <div class="divider-custom">
                    <div class="divider-custom-line"></div>
                    <div class="divider-custom-icon"><i class="fas fa-star"></i></div>
                    <div class="divider-custom-line"></div>
                  </div>
                  <!-- Portfolio Modal - Image--><img class="img-fluid rounded mb-5"
                    src="https://img.icons8.com/clouds/300/000000/find-email.png">
                  <!-- Portfolio Modal - Text-->
                  <p class="mb-5">Click this button and find what language you
                    like!</p>
                  <a class="btn btn-primary btn-lg px-4 me-sm-3" href="/home/umar/Desktop/Website/t.html">Find!
                    </a> </div> </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <section class="page-section bg-primary text-white mb-0" id="about">
      <div class="container">
        <!-- About Section Heading-->
        <div class="text-center">
          <h2 class="page-section-heading d-inline-block text-white">ABOUT</h2>
        </div>
        <!-- Icon Divider-->
        <h3>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
          A site by Umar Mohammad Nadeem, </h3>
        <h3>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
          studying in 8th grade.</h3>
        <h3>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
          Based on the topic of programming languages... </h3>
        <h3>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
          and Actualize Bootcamp©</h3>
      </div>
    </section>
    <section class="page-section" id="contact">
      <div class="container">
        <!-- Contact Section Heading-->
        <div class="text-center">
          <h2 class="page-section-heading text-secondary d-inline-block mb-0">CONTACT</h2>
        </div>
        <!-- Icon Divider-->
        <div class="divider-custom">
          <div class="divider-custom-line"></div>
          <div class="divider-custom-icon"><i class="fas fa-star"></i></div>
          <div class="divider-custom-line"></div>
        </div>
        <!-- Contact Section Content-->
        <div class="row justify-content-center">
          <div class="col-lg-4">
            <div class="d-flex flex-column align-items-center">
              <div class="icon-contact mb-3"><i class="fas fa-mobile-alt"></i></div>
              <div class="text-muted">Phone</div>
              <a class="primary-color" href="tel:7737665965"><strong>(773)
                  766-5965</strong></a> </div>
          </div>
          <div class="col-lg-4">
            <div class="d-flex flex-column align-items-center">
              <div class="icon-contact mb-3"><i class="far fa-envelope"></i></div>
              <div class="text-muted">Email</div>
              <a class="lead font-weight-bold" href="mailto:hiring@actualize.co">hiring@actualize.co</a>
            </div>
          </div>
        </div>
      </div>
      <!-- Copyright Section--> </section>
    <section class="copyright py-4 text-center text-white">
      <div class="container"><small class="pre-wrap">Copyright © Programmer's World</small></div>
    </section>
    <!-- Scroll to Top Button (Only visible on small and extra-small screen sizes)-->
    <div class="scroll-to-top d-lg-none position-fixed"><a class="js-scroll-trigger d-block text-center text-white rounded"
        href="#page-top"><i class="fa fa-chevron-up"></i></a></div>
    <!-- Bootstrap core JS-->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.bundle.min.js"></script>
    <!-- Third party plugin JS-->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery-easing/1.4.1/jquery.easing.min.js"></script>
    <!-- Contact form JS-->
    <script src="assets/mail/jqBootstrapValidation.js"></script>
    <script src="assets/mail/contact_me.js"></script>
    <!-- Core theme JS-->
    <script src="js/scripts.js"></script>
  </body>
</html>
