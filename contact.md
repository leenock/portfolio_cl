
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
	<meta http-equiv="x-ua-compatible" content="ie=edge">

	<title>Winnie Kingori</title>

	<!-- Font Awesome -->
	<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.0/css/all.css">
	<!-- Bootstrap core CSS -->
	<link href="css/bootstrap.min.css" rel="stylesheet">
	<!-- Material Design Bootstrap -->
	<link href="css/mdb.min.css" rel="stylesheet">
	<!-- Your custom styles (optional) -->
	<link href="css/style.css" rel="stylesheet">

    <style>
        html,
        body,
        header,
        .jarallax {
          height: 100%;
        }

        @media (min-width: 560px) and (max-width: 740px) {
          html,
          body,
          header,
          .jarallax {
            height: 600px;
          }
        }
    </style>

</head>
<body class="developer">

    <!--Navigation & Intro-->
    <header>

        <!-- Navbar -->
        <nav class="navbar navbar-expand-lg navbar-dark fixed-top scrolling-navbar">
            <div class="container">
                <a class="navbar-brand" href="#">Winnie</a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarTogglerDemo02" aria-controls="navbarTogglerDemo02" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarTogglerDemo02">
                    <ul class="navbar-nav mr-auto smooth-scroll">
                        <li class="nav-item">
                            <a class="nav-link" href="#home">Home <span class="sr-only">(current)</span></a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="index.html#about" data-offset="100">About</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="index.html#skills" data-offset="100">skills</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="index.html#works" data-offset="100">projects</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="index.html#contact" data-offset="100">Contact</a>
                        </li>
                    </ul>
                    <!-- Social Icon  -->
                    <ul class="navbar-nav nav-flex-icons">
                        <li class="nav-item">
                            <a class="nav-link"><i class="fab fa-facebook-f light-green-text-2"></i></a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link"><i class="fab fa-twitter light-green-text-2"></i></a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link"><i class="fab fa-instagram light-green-text-2"></i></a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>

        <!-- Intro Section -->
        <div id="home" class="view jarallax" data-jarallax='{"speed": 0.2}' style="background-image: url('img/background_images/winnie.jpg'); background-repeat: no-repeat; background-size: cover; background-position: center center;">
            <div class="mask rgba-white-strong">
                <div class="container h-100 d-flex justify-content-center align-items-center">
                    <div class="row smooth-scroll">
                        <div class="col-md-12 pt-3">
                            <div class="white-text text-center pt-5">
                                <h1 class="display-2 mb-4 dark-grey-text wow fadeIn">I am <strong>Winnie KIngori</strong></h1>
                                <h5 class="text-uppercase font-weight-bold wow fadeIn" data-wow-delay="0.4s"><mark>I'm an Android Developer!</mark></h5>
                                <a href="#about" class="btn btn-floating btn-large wow fadeIn" data-wow-delay="0.4s" data-offset="100"><i class="fas fa-angle-down" aria-hidden="true"></i></a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

    </header>
    <!--/Navigation & Intro-->

   <!--Main layout-->
<main>


        <!-- Contact form -->
        <div id="contact" class="container">
            <section class="section contact-section mt-4 mb-5">
                <!--Section heading-->
                <h2 class="text-center text-uppercase my-5 pt-5 wow fadeIn" data-wow-delay="0.2s">Contact <strong>me</strong></h2>
                <!--Section sescription-->
                <p class="text-center w-responsive mx-auto mb-5 pb-4 wow fadeIn" data-wow-delay="0.2s">Get Intouch with me</p>
                <div class="row wow fadeIn" data-wow-delay="0.4s">

                    <!--First column-->
                    <div class="col-md-8 mb-5">
                        <form>
    <div class="row">
      <div class="col-md-6">
        <div class="form-group">
          <label for="first">First Name</label>
          <input type="text" class="form-control" placeholder="" id="first">
        </div>
      </div>
      <!--  col-md-6   -->

      <div class="col-md-6">
        <div class="form-group">
          <label for="last">Last Name</label>
          <input type="text" class="form-control" placeholder="" id="last">
        </div>
      </div>
      <!--  col-md-6   -->
    </div>

    <div class="row">
      <div class="col-md-6">
        <div class="form-group">
          <label for="company">Company</label>
          <input type="text" class="form-control" placeholder="" id="company">
        </div>

      </div>
      <!--  col-md-6   -->

      <div class="col-md-6">
        <div class="form-group">
          <label for="phone">Phone Number</label>
          <input type="tel" class="form-control" id="phone" placeholder="phone">
        </div>
      </div>
      <!--  col-md-6   -->
    </div>
    <!--  row   -->

    <div class="row">
      <div class="col-md-6">
        <div class="form-group">
          <label for="email">Email address</label>
          <input type="email" class="form-control" id="email" placeholder="email">
        </div>
      </div>
      <!--  col-md-6   -->

      <div class="col-md-6">
        <div class="form-group">
          <label for="url">Your Website <small>Please include http://</small></label>
          <input type="url" class="form-control" id="url" placeholder="url">
        </div>
      </div>
      <!--  col-md-6   -->
    </div>
    <!--  row   -->

    <label for="contact-preference">When is the best time of day to reach you?</label>
    <div class="radio">
      <label>
        <input type="radio" name="contact-preference" id="contact-preference" value="am" checked>Morning
      </label>
    </div>
    <div class="radio">
      <label>
        <input type="radio" name="contact-preference" id="contact-preference" value="pm" checked>Evening
      </label>
    </div>

    <label for="newsletter">Would you like to recieve my email newsletter?</label>
    <div class="checkbox">

      <label>
        <input type="checkbox" value="Sure!" id="newsletter"> Sure!
      </label>
    </div> 
<div class="text-center text-md-left mt-4"> <a class="btn btn-primary">Send</a> </div>

  </form>
                    </div>
                    <!--.First column-->

                    <!--Second column-->
                    <div class="col-md-4">
                        <ul class="contact-icons list-unstyled text-center">
                            <li><i class="fas fa-map-marker-alt fa-2x"></i>
                                <p>Nairobi, KENYA</p>
                            </li>
                            <li><i class="fas fa-phone fa-2x"></i>
                                <p>+ 254 718 291 873</p>
                            </li>
                            <li><i class="fas fa-envelope fa-2x"></i>
                                <p>kingoriwinnie3@gmail.com</p>
                            </li>
                        </ul>
                    </div>
                    <!--.Second column-->
                </div>

            </section>
            <!--/Section: Contact v.2-->

        </div>

<div class="container">
            <div class="flex-center">
                <ul class="list-unstyled">
                    <li><h5 class="h5-responsive wow fadeIn" data-wow-delay="0.2s">© Copyright, 2020, Winnie Kingori</h5></li>
                </ul>
            </div>
        </div>

</main>

<!-- jQuery library -->
    <script type="text/javascript" src="js/jquery-3.3.1.min.js"></script>

    <!-- Bootstrap Popper JS  tooltips -->
    <script type="text/javascript" src="js/popper.min.js"></script>

    <!-- Bootstrap core JavaScript -->
    <script type="text/javascript" src="js/bootstrap.min.js"></script>
    <!-- MDB core JavaScript -->
    <script type="text/javascript" src="js/mdb.min.js"></script>

    <script>
        // initialize scrollspy
        $('body').scrollspy({
            target: '.dotted-scrollspy'
        });

        /* WOW.js init */
        new WOW().init();

    </script>
  </body>
  </html>
