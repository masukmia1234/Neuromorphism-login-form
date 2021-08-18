# Neuromorphism-login-form
Neumorphism is a modern design that is currently in great demand. It is much more beautiful and attractive than the general design. The color of the background and the color of the background of the content are completely the same. However, in this case, some color effect is created using css programming code to shape the login form. Like the normal login form, it has everything like input email ID and password, login button, and profile image.
at first use  Bootstrap cdn
logo design
index.html:

<!doctype html>
<html lang="en">

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="description" content="">
  <meta name="author" content="Mark Otto, Jacob Thornton, and Bootstrap contributors">
  <meta name="generator" content="Hugo 0.72.0">
  <title>  Login Form</title>

  <link rel="canonical" href="https://v5.getbootstrap.com/docs/5.0/examples/dashboard/">

  <link rel="stylesheet" type="text/css" href="css/login.css">

  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/5.0.0-alpha1/css/bootstrap.min.css"
    integrity="sha384-r4NyP46KrjDleawBgD5tp8Y7UzmLA05oM1iAEQ17CSuDqnUK2+k9luXQOfXJCJ4I" crossorigin="anonymous">
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js"
    integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo"
    crossorigin="anonymous"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/5.0.0-alpha1/js/bootstrap.min.js"
    integrity="sha384-oesi62hOLfzrys4LxRF63OJCXdXDipiYWBnvTl9Y9/TRlw5xlKIEHpNyvvDShgf/"
    crossorigin="anonymous"></script>

</head>
  
#==================Body satrt==========================
<body>


<h2>Welcome to Login Page</h2>
#============================================contact form here========================
<div class="box">
    <div class="logo"> <img src="images/masuk.png" alt=""> </div>

  <form action="#" method="post">
    <label for="username">Username</label></br>
    <input type="text" name="uname" id="uname" placeholder="Enter Username" class="input-box">
    </br></br>
    <label for="username">Password</label></br>
    <input type="password" name="uname" id="uname" placeholder="Enter Password" class="input-box"></br>
    <div class="forget">
      <label class="checkbox-label">
      <input type="checkbox">
      <span class="checkbox-custom "></span>
      <span class="label-text">Remember me</span>
      </label>
      <span class="fg">
      <a href="#"> Forget password?</a>
      </span>
    </div>
    <button type="submit" class="btn">Sign In</button>
  </form>
  <span class="option">or sign in with</span>
  <div class="social">
    <div class="box-radius">
      <img src="images/fb.png" alt="">
    </div>
    <div class="box-radius">
      <img src="images/google.png" alt="">
    </div>
    <div class="box-radius">
      <img src="images/linkedin.png" alt="">
    </div>
    <div class="box-radius">
      <img src="images/twitter.png" alt="">
    </div>
  </div>
      #================links================
    <div class="text-center fs-6"><a href="https://masukmia.com">developed by Masuk Mia</a> 


</div>


</div>
#=========================js file===================

  <script src="/docs/5.0/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-DBjhmceckmzwrnMMrjI7BvG2FmRuxQVaTfFYHgfnrdfqMhxKt445b7j3KBQLolRl"
    crossorigin="anonymous"></script>

  <script src="https://cdnjs.cloudflare.com/ajax/libs/feather-icons/4.24.1/feather.min.js"
    integrity="sha384-EbSscX4STvYAC/DxHse8z5gEDaNiKAIGW+EpfzYTfQrgIlHywXXrM9SUIZ0BlyfF"
    crossorigin="anonymous"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/2.9.3/Chart.min.js"
    integrity="sha384-i+dHPTzZw7YVZOx9lbH5l6lP74sLRtMtwN2XjVqjf3uAGAREAF4LMIUDTWEVs4LI"
    crossorigin="anonymous"></script>
  #====================design==================
  developer By Masuk Mia
</body>

</html>

