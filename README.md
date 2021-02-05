<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="utf-8">
  <meta content="width=device-width, initial-scale=1.0" name="viewport">
  <title>Allure Corporation</title>
  <meta content="" name="description">
  <meta content="" name="keywords">

  <!-- Favicons -->
  <link href="assets/img/favicon.png" rel="icon">
  <link href="assets/img/apple-touch-icon.png" rel="apple-touch-icon">

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css?family=Open+Sans:300,300i,400,400i,600,600i,700,700i|Raleway:300,300i,400,400i,600,600i,700,700i" rel="stylesheet">

  <!-- Vendor CSS Files -->
  <link href="assets/vendor/bootstrap/css/bootstrap.min.css" rel="stylesheet">
  <link href="assets/vendor/icofont/icofont.min.css" rel="stylesheet">

  <!--  Main CSS File -->
  <link href="assets/css/style.css" rel="stylesheet">


</head>

<body>

  <!-- ======= Header ======= -->
  <header id="header" class="d-flex align-items-center">
    <div class="container d-flex flex-column align-items-center">

      <h1>Allure Corporation</h1>
      <h2>We're working hard to get Start and we'll ready to launch after 2022/1/1.
      </h2>
      <div class="countdown d-flex justify-content-center" data-count="2022/1/1">
        <div>
          <h3>%D</h3>
          <h4>Days</h4>
        </div>
        <div>
          <h3>%H</h3>
          <h4>Hours</h4>
        </div>
        <div>
          <h3>%M</h3>
          <h4>Minutes</h4>
        </div>
        <div>
          <h3>%S</h3>
          <h4>Seconds</h4>
        </div>
      </div>

      <div class="subscribe">
        <h4>Subscribe now to get the latest updates!</h4>
        <form action="javascript:sendmail()" method="post" role="form" class="">
          <div class="subscribe-form">
            <input type="text" name="email" id="email">
            <input type="submit" value="Subscribe" onclick="sendmail();">
          </div>
          <div class="mt-2">
            <div class="loading">Loading</div>
            <div class="error-message"></div>
            <div class="sent-message">Your notification request was sent. Thank you!</div>
          </div>
        </form>
      </div>

      <div class="social-links text-center">
        <a href="#" class="twitter"><i class="icofont-twitter"></i></a>
        <a href="#" class="facebook"><i class="icofont-facebook"></i></a>
        <a href="https://www.instagram.com/allure.corporation/" class="instagram"><i class="icofont-instagram"></i></a>
        <a href="mailto:allurecorporation007@gmail.com" class="google-plus"><i class="icofont-google-plus"></i></a>
        <a href="index.html" class="linkedin"><i class="icofont-globe"></i></a>
      </div>

    </div>
  </header><!-- End #header -->


  <!-- ======= Footer ======= -->
  <footer id="footer">
    <div class="container">
      <div class="copyright">
        &copy; Copyright <strong><span>Allure Corporation </span></strong>. All Rights Reserved
      </div>
      <div class="credits">
        Designed by <a href="https://atharv.netlify.app">Atharv Gangarde</a>
      </div>
    </div>
  </footer><!-- End #footer -->

  <a href="#" class="back-to-top"><i class="icofont-simple-up"></i></a>

    <!-- All the links in the footer should remain intact. -->
    <!-- Developed By Atharv and team With Allure Corporation -->
  <!-- Vendor JS Files -->
  <script src="assets/vendor/jquery/jquery.min.js"></script>
  <script src="assets/vendor/bootstrap/js/bootstrap.bundle.min.js"></script>
  <script src="assets/vendor/jquery.easing/jquery.easing.min.js"></script>
  <script src="assets/vendor/php-email-form/validate.js"></script>
  <script src="assets/vendor/jquery-countdown/jquery.countdown.min.js"></script>

  <!--  Main JS File -->
  <script src="assets/js/main.js"></script>
  <!-- Contact Js Codes -->


  	<script
  	  src="https://code.jquery.com/jquery-2.2.4.min.js"
  	  integrity="sha256-BbhdlvQf/xTY9gja0Dq3HiwQF8LaCRTXxZKRutelT44="
  	  crossorigin="anonymous"></script>
  	<script src="https://smtpjs.com/v3/smtp.js"></script>

  <script type="text/javascript">

       function sendmail(){

  			var email = $('#email').val();

  			// var body = $('#body').val();

        var Body='Email: '+email;
  			//console.log(name, phone, email, message);

  			Email.send({
          		SecureToken:"fbf31702-bb7f-4a4e-9c1c-4ccf17ee777f",
  				To: 'allurecorporation007@gmail.com',
  				From: "allure@gmail.com",
  				Subject: "New message "+name,
  				Body: Body
  			}).then(
  				message =>{
  					//console.log (message);
  					if(message=='OK'){
  					alert('Your mail has been send.\n You have been registerd :) \n Have a Good Day');
  					}
  					else{
  						console.error (message);
  						alert('There is error at sending message. ')

  					}

  				}
  			);
  		}
      </script>

  </body>

</html>
