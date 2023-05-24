# Sliding-Login-Registration-Form
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Sliding Login & Registration Form</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <header>
      <h2 class="title">Sliding Login & Registration Form</h2>
    </header>

    <!-- Container div-->
    <div class="container">
      <!-- upper button section-->
      <div class="slider"></div>
      <div class="btn">
        <button class="login">Login</button>
        <button class="signup">Signup</button>
      </div>

      <!-- Form section-->
      <div class="form-section">
        <!-- Login Form-->
        <div class="login-box">
          <input
            type="email"
            class="email ele"
            placeholder="youremai@gmail.com"
          />
          <input type="password" class="password ele" placeholder="password" />
          <button class="clkbtn">Login</button>
        </div>

        <!-- Signup Form-->
        <div class="signup-box">
          <input type="text" class="name ele" placeholder="Enter your name" />
          <input
            type="email"
            class="email ele"
            placeholder="youremai@gmail.com"
          />
          <input type="password" class="password ele" placeholder="password" />
          <input
            type="password"
            class="password ele"
            placeholder="Confirm password"
          />
          <button class="clkbtn">Signup</button>
        </div>
      </div>
      <script src="main.js"></script>
    </div>
  </body>
</html>
