<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <!-- displays site properly based on user's device -->

  <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">

  <!-- jQuery -->
  <script src="js/jQuery3.5.1.js"></script>
  <script src="js/jquery-ui.min.js"></script>

  <!-- FontAwesome JS -->
  <script src='js/all.js'></script>

  <!-- Bootstrap CSS AND JS -->
  <link rel="stylesheet" href="css/bootstrap.css">
  <script src="js/bootstrap.min.js"></script>

  <!-- Custom CSS -->
  <link rel="stylesheet" href="css/easybank.css">
  <title>Frontend Mentor | Easybank landing page</title>
</head>

<body>
  <header class='py-3'>
    <div class="wrapper">
      <div class="logo">
        <img src="images/logo.svg">
      </div>
      <nav>
        <ul>
          <li class="nav-item-me"><a href="" class="nav-link-me active">Home</a></li>
          <li class="nav-item-me"><a href="" class="nav-link-me">About</a></li>
          <li class="nav-item-me"><a href="" class="nav-link-me">Contact</a></li>
          <li class="nav-item-me"><a href="" class="nav-link-me">Blog</a></li>
          <li class="nav-item-me"><a href="" class="nav-link-me">Careers</a></li>
        </ul>
      </nav>
      <button class='btn btn-grad inheader badge-pill'>Request Invite</button>
      <div class="toggle">
        <img src="images/icon-hamburger.svg" class='img-responsive img-fluid' alt="" id=hamburger>
        <img src="images/icon-close.svg" class='img-responsive img-fluid' alt="" id=close>
      </div>
    </div>
  </header>
  <div class='overlay' id=overlay></div>
  <div class="wrapper">
    <div class="section1">
      <div class="row">
        <div class="col-12 col-md-6 cols">
          <div class="first-col">
            <h1 class=display-4>Next generation digital banking</h1>
            <p>Take your financial life online. Your Easybank account will be a one-stop-shop
              for spending, saving, budgeting, investing, and much more.</p>
            <button class='btn btn-grad badge-pill'>Request Invite</button>
          </div>
        </div>
        <div class="col-12 col-md-6 cols hi">
          <img src="images/bg-intro-desktop.svg" class=images alt="" id=bg>
          <img src="images/image-mockups.png" class=images alt="" id=mockup>
        </div>
      </div>
    </div>
  </div>

  <div class="section2 my-5">
    <div class="wrapper py-5 my-5 text-center text-md-left">
      <div class="whychooseus mb-5">
        <h1 class=mb-4>Why choose Easybank?</h1>
        <p>We leverage Open Banking to turn your bank account into your financial hub. Control
          your finances like never before.</p>
      </div>
      <div class="allservices row">
        <div class="services mb-3 col-sm-6 col-md-3">
          <img src="images/icon-online.svg" alt="" class='mb-4'>
          <h5 class='mb-3'>Online Banking</h5>
          <p>Our modern web and mobile applications allow you to keep track of your finances
            wherever you are in the world.</p>
        </div>
        <div class="services mb-3 col-sm-6 col-md-3">
          <img src="images/icon-budgeting.svg" alt="" class='mb-4'>
          <h5 class='mb-3'>Simple Budgeting</h5>
          <p>See exactly where your money goes each month. Receive notifications when you’re
            close to hitting your limits.</p>
        </div>
        <div class="services mb-3 col-sm-6 col-md-3">
          <img src="images/icon-onboarding.svg" alt="" class='mb-4'>
          <h5 class='mb-3'>Fast Onboarding</h5>
          <p>We don’t do branches. Open your account in minutes online and start taking control
            of your finances right away.</p>
        </div>
        <div class="services mb-3 col-sm-6 col-md-3 pr-0">
          <img src="images/icon-api.svg" alt="" class='mb-4'>
          <h5 class='mb-3'>Open API</h5>
          <p>Manage your savings, investments, pension, and much more from one account. Tracking
            your money has never been easier.</p>
        </div>
      </div>
    </div>
  </div>
  <div class="latest-articles section3">
    <div class="wrapper">
      <h1>Latest Articles</h1>
      <div class="row">
        <div class="col-12 col-sm-6 col-md-3">
          <div class="ourcard">
            <div class="cardimage">
              <img src="images/image-currency.jpg" class='img-fluid'>
            </div>
            <div class="cardtext">
              <small>By Claire Robinson</small>
              <h6><b>Receive money in any currency with no fees</b></h6>
              <p>The world is getting smaller and we’re becoming more mobile. So why should you be
                forced to only receive money in a single …</p>
            </div>
          </div>
        </div>
        <div class="col-12 col-sm-6 col-md-3">
          <div class="ourcard">
            <div class="cardimage">
              <img src="images/image-restaurant.jpg" class='img-fluid'>
            </div>
            <div class="cardtext">
              <small>By Wilson Hutton</small>
              <h6><b>Treat yourself without worrying about money</b></h6>
              <p>The world is getting smaller and we’re becoming more mobile. So why should you be
                forced to only receive money in a single …</p>
            </div>
          </div>
        </div>
        <div class="col-12 col-sm-6 col-md-3">
          <div class="ourcard">
            <div class="cardimage">
              <img src="images/image-plane.jpg" class='img-fluid'>
            </div>
            <div class="cardtext">
              <small>By Wilson Hutton</small>
              <h6><b>Receive money in any currency with no fees</b></h6>
              <p>Our simple budgeting feature allows you to separate out your spending and set
                realistic limits each month. That means you …</p>
            </div>
          </div>
        </div>
        <div class="col-12 col-sm-6 col-md-3">
          <div class="ourcard">
            <div class="cardimage">
              <img src="images/image-confetti.jpg" class='img-fluid'>
            </div>
            <div class="cardtext">
              <small>By Claire Robinson</small>
              <h6><b>Our invite-only Beta accounts are now live!</b></h6>
              <p>After a lot of hard work by the whole team, we’re excited to launch our closed beta.
                It’s easy to request an invite through the site ...</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="finalsection section4 p-5">
    <div class="wrapper">
      <div class="row">
        <div class="col-12 col-md-3 socialxlogo">
          <img src="images/logo.svg" class = logofooter>
          <div class="socials">
            <img src="images/icon-facebook.svg" alt="">
            <img src="images/icon-youtube.svg" alt="">
            <img src="images/icon-twitter.svg" alt="">
            <img src="images/icon-pinterest.svg" alt="">
            <img src="images/icon-youtube.svg" alt="">
          </div>
        </div>
        <div class="col-12 col-md-3 links">
          <ul>
            <li>About Us</li>
            <li>Contact</li>
            <li>Blog</li>
          </ul>
        </div>
        <div class="col-12 col-md-3 links">
          <ul>
            <li>Careers</li>
            <li>Support</li>
            <li>Privacy Policy</li>
          </ul>
        </div>
        <div class="col-12 col-md-3 easybank">
          <button class='btn btn-grad badge-pill'>Request Invite</button>
          <p>© Easybank. All Rights Reserved</p>
        </div>
      </div>
    </div>
  </div>
  <div class="attribution">
    Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>.
    Coded by <a href="#">Lena Jeremiah</a>.
  </div>
  <script src="js/easybank.js"></script>
  <script src="js/smoothscroll.js"></script>
</body>

</html>
