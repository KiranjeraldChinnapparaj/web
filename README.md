<!DOCTYPE html>

<html lang="en" xmlns="http://www.w3.org/1999/xhtml">
<head>
    <meta charset="utf-8" />
    <title></title>
    <link rel="stylesheet" type="text/css" href="webpagestyle.css" />
          <style>
              * {
                  margin: 0px;
                  padding: 0px;
                  box-sizing: border-box;
              }

              body {
                  background-image: url('file:///C:/Users/Lenovo/Downloads/pexels-fwstudio-129731.jpg');
                  backface-visibility: hidden;
                  background-attachment: fixed;
                  background-size: cover;
                  background-position: 50% 50%;
                  margin: 0;
              }

              .header {
                  text-align: center;
                  letter-spacing: 3px;
                  color: white;
                  background-color: gray;
                  padding: 20px;
              }

              .topnav {
                  overflow: hidden;
                  background-color: beige;
              }

                  .topnav a {
                      float: left;
                      text-align: center;
                      letter-spacing: 2px;
                      color: blue;
                      width: 350px;
                      height: 70px;
                      padding: 20px 30px 15px 10px;
                      backface-visibility: hidden;
                      justify-content: center;
                      align-items: center;
                      font-size: 25px;
                  }

                      .topnav a:hover {
                          color: black;
                          background-color: #ddd;
                      }

              .box {
                  width: 100%;
                  height: 500%;
                  backface-visibility: hidden;
                  image-rendering: pixelated;
                  position: relative;
              }

                  .box h2 {
                      justify-content: center;
                      align-items: center;
                  }

              h2 {
                  text-align: center;
                  position: relative;
              }

              img {
                  height: 70vh;
                  width: 100%;
                  backface-visibility: hidden;
                  background-size: cover;
                  background-repeat: no-repeat;
                  background-position: center;
                  position: relative;
                  z-index: -1;
                  display: flex;
                  justify-content: center;
                  align-items: center;
              }

              .centered {
                  position: absolute;
                  top: 50%;
                  left: 50%;
                  transform: translate(-50%, -50%);
                  color: aliceblue;
                  font-family: sans-serif;
                  font-size: 40px;
                  letter-spacing: 2px;
              }
          </style>
</head>
<body>
    <div class="header">
        <h1> UPSKILLING PLATFORM </h1>
    </div>
    <div class="topnav">
        <a href="file:///C:/Users/Lenovo/Desktop/Webpage%20project/.vs/Webpage%20project/homepage.html">HOME</a>
        <a href="file:///C:/Users/Lenovo/Desktop/Webpage%20project/.vs/Webpage%20project/about.html">RESOURCES</a>
        <a href="">ABOUT</a>
        <a href=" file:///C:/Users/Lenovo/Desktop/Webpage%20project/.vs/Webpage%20project/Applicationform.html">CONTACT</a>
    </div>
    <div class="box">
        <img src="file:///C:/Users/Lenovo/Downloads/pexels-bess-hamiti-36487.jpg" />
        <h2 class="centered"> LEARN EVERYTHING UNTIL YOU DIE</h2>
    </div>

</body>
</html>
