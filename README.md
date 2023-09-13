# Registration-Form
<!DOCTYPE html>
<html lang="en">
  <head>
    <link rel="stylesheet" href="./styile.css" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Responsive Registration Form</title>
  </head>
  <body>
    <div class="container">
      <h1 class="form-title">Registration</h1>
      <form action="#">
        <div class="main-user-info">
          <div class="user-input-box">
            <label for="fullName">Full Name</label>
            <input
              type="text"
              id="fullName"
              name="fullName"
              placeholder="Enter Full Name"
            />
          </div>
          <div class="user-input-box">
            <label for="username">Enter username</label>
            <input
              type="text"
              id="username"
              name="username"
              placeholder="Enter username"
            />
          </div>
          <div class="user-input-box">
            <label for="Email">Enter Email</label>
            <input
              type="text"
              id="Email"
              name="Email"
              placeholder="Enter Email"
            />
          </div>
          <div class="user-input-box">
            <label for="phonenumber">Enter Phone Number</label>
            <input
              type="text"
              id="phonenumber"
              name="phonenumber"
              placeholder="Enter phonenumber"
            />
          </div>
          <div class="user-input-box">
            <label for="Password">Password</label>
            <input
              type="password"
              id="Password"
              name="Password"
              placeholder="Enter Password"
            />
          </div>
          <div class="user-input-box">
            <label for="ConfirmPassword">Confirm Password</label>
            <input
              type="password"
              id="ConfirmPassword"
              name="ConfirmPassword"
              placeholder="Confirm Password"
            />
          </div>
        </div>
        <div class="gender-details-box">
          <span class="gender-title">Gender</span>
          <div class="gender-catefory">
            <input type="radio" name="gender" id="male" />
            <label for="male">Male</label>
            <input type="radio" name="gender" id="female" />
            <label for="female">Female</label>
            <input type="radio" name="gender" id="other" />
            <label for="other">other</label>
          </div>
        </div>
        <div class="form-submit-button">
          <input type="submit" value="Register" />
        </div>
      </form>
    </div>
  </body>
</html>
