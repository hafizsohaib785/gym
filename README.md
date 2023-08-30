<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Smart insides Landpage</title>
    <link rel="stylesheet" href="css/style.Css" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Archivo+Black&family=Black+Ops+One&display=swap"
      rel="stylesheet"
    />
    <style>
      body {
        font-family: "Archivo Black", sans-serif;
        font-family: "Black Ops One", cursive;
        color: aliceblue;
        margin: 0%;
        padding: 0%;
      }
      section {
        background-color: black;
        background-blend-mode: overlay;
        overflow: hidden;
        pointer-events: none;
      }
      .left {
        display: block;
        position: absolute;
        left: 23px;
        top: 20px;
      }
      .left img {
        width: 91px;
        filter: invert(100%);
        margin: -14px 5px;
        align-items: left;
      }
      .left text {
        text-align: center;
        align-items: left;
      }
      .right {
        position: absolute;
        right: 23px;
        top: 31px;
        display: inline-block;
      }
      .Btn {
        margin: 8px 16px;
        color: goldenrod;
        background-color: whitesmoke;
        padding: 1px 20px;
        border: 2px solid white;
        border-radius: 20px;
      }
      .Btn:hover {
        background-color: black;
        color: gold;
        cursor: pointer;
        font-weight: bold;
      }
      .mid {
        margin: 20px auto;
        width: 500px;
      }
      .navbar {
        display: inline-block;
        margin: 19px -46px;
      }
      .navbar li {
        display: inline-block;
      }
      .navbar li a {
        color: white;
        text-decoration: none;
        padding: 34px 23px;
        font-size: 18px;
        position: relative;
        top: -1082px;
        right: 13px;
      }
      .navbar li a:hover {
        font-weight: bold;
        font-family: Arial, Helvetica, sans-serif;
        color: goldenrod;
        background-color: none;
      }
      .container {
        border: 2px solid white;
        margin: 110px 220px;
        padding: 6px;
        border-radius: 28px;
        position: relative;
        top: -1154px;
        color: black;
        left: -213px;
      }
      .formgroup input {
        font-family: Impact, Haettenschweiler, "Arial Narrow Bold", sans-serif;
        text-align: center;
        display: block;
        width: 508px;
        padding: 1px;
        border: 2px solid black;
        margin: 11px auto;
        font-size: 25px;
        border-radius: 8px;
        cursor: pointer;
      }
      h1 {
        text-align: center;
        font-weight: bolder;
        color: orange;
      }
      h1:hover {
        color: black;
        cursor: pointer;
      }
      .container button {
        display: block;
        margin: 20px auto;
        background-color: black;
        color: white;
        font-size: 15px;
      }
      .container button:hover {
        background-color: black;
        color: gold;
        cursor: pointer;
        font-weight: bold;
        font-size: 15px;
        font-family: Arial, Helvetica, sans-serif;
      }
    </style>
  </head>
  <body>
    <section id="vid-par">
      <video
        class="My video"
        autoplay
        loop
        muted
        src="production_id_4367572 (1080p).mp4"
      >
        <source type="video/mp4" />
      </video>
    </section>
    <header class="header">
      <!-- left to logo -->
      <div class="left">
        <img
          src="04012019-25-removebg-preview.png"
          alt="Sohaib Fitness Center"
        />
        <div class="text">Sohaib Fitness</div>
      </div>
      <!-- mid to navbar -->
      <div class="mid">
        <ul class="navbar">
          <li><a href="#">Home</a></li>
          <li><a href="#">Workout</a></li>
          <li><a href="#">About us</a></li>
          <li><a href="#">Contact Us</a></li>
        </ul>
        <!-- right to button -->
        <div class="right">
          <button class="Btn">Login</button>
        </div>
      </div>
      <div class="container">
        <h1>Join Now Sohaib Fitness Center</h1>
        <form
          action="https://www.titanfitnesscamp.com/programs/?gclid=Cj0KCQjw0bunBhD9ARIsAAZl0E0We898k7xx6qDKeGuDQ2pxXleEZDjFVDYa03uXIdfs8yE9AHWhfz4aAj8UEALw_wcB"
        >
          <div class="formgroup">
            <input type="text" name="Full Name" placeholder="Enter Your Name" />
          </div>
          <div class="formgroup">
            <input type="text" name="Full Name" placeholder="Enter Your Age" />
          </div>
          <div class="formgroup">
            <input
              type="text"
              name="Full Name"
              placeholder="Enter Your Gender"
            />
          </div>
          <div class="formgroup">
            <input
              type="text"
              name="Full Name"
              placeholder="Enter Your Locality"
            />

            <input type="email" name="email" placeholder="Enter Your Email" />
          </div>
          <button class="btn">Submit Now</button>
        </form>
      </div>
    </header>
  </body>
</html>
