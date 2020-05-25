# library-management
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Library Management</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
  <link rel="stylesheet" href="library.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
</head>
<body>

<nav class="navbar navbar-inverse">
  <ul class="nav navbar-nav">
    <li><a href="signupboot.htm">SIGNUP</a></li>
    <li><a href="login1.htm">LOGIN</a></li>
  </ul>
  <p class="navbar-text">HOME</p>
</nav>

<div class="container">
  <h3>Library</h3>
  <p></p>
</div>
<div class="card mb-3" style="max-width: 540px;">
    <div class="row no-gutters">
      <div class="col-md-4">
        <img src="images/head1.jpg" class="card-img" alt="...">
      </div>
      <div class="col-md-8">
        <div class="card-body">
          <h5 class="card-title">Repurpose Content to Reach a Wider Audience</h5>
          <p class="card-text">97thfloor.com</p>
          <p class="card-text"><small class="text-muted">2hours ago . Read More</small></p>
        </div>
      </div>
    </div>
  </div>
  <div class="card mb-3" style="max-width: 540px;">
    <div class="row no-gutters">
      <div class="col-md-4">
        <img src="images/head2.jpg" class="card-img" alt="...">
      </div>
      <div class="col-md-8">
        <div class="card-body">
          <h5 class="card-title">14 Useful Sites for designers</h5>
          <p class="card-text">devgarage.com</p>
          <p class="card-text"><small class="text-muted">Yesterday .Read More</small></p>
        </div>
      </div>
    </div>
  </div>
  <div class="card mb-3" style="max-width: 540px;">
    <div class="row no-gutters">
      <div class="col-md-4">
        <img src="images/head3.jpg" class="card-img" alt="...">
      </div>
      <div class="col-md-8">
        <div class="card-body">
          <h5 class="card-title">Measuring your Link Building with Google Analytics</h5>
          <p class="card-text">searchenginewatch.com</p>
          <p class="card-text"><small class="text-muted">Yesterday .Read More</small></p>
        </div>
      </div>
    </div>
  </div>
  <footer>
    <p>Follow Us</p>
    <p><a href="TwitterFacebookGoogle+">TwitterFacebookGoogle+</a></p>
  </footer>
</body>
</html>
css file
.container {
    border-radius: 5px;
    background-color: #7115db;
    padding: 20px;
}
.navbar-text
{
    text-align: left;
    font-weight: bold;
    color: lightcyan;
}
.navbar navbar-inverse
{
    color: rgb(153, 86, 240);
}
.nav navbar-nav
{
    color: rgb(153, 86, 240);  
}
.card mb-3
{
    font-size: 20pt;
}
.card-body
{
  color: rgb(91, 91, 102); 
  font-size: medium;
  font-weight: bold;
padding: 20pt;
}
    img {
        border: 1px solid rgba(223, 217, 217, 0.747);
        border-radius: 50%;
        padding: 5px;
        width: 100px;
      }

  footer
  {
      background-color: lightgrey;
      font-weight: bold;
      font-size: x-large;
  }

