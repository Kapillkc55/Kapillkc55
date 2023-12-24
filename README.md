<!DOCTYPE html>
<html>
<head>
   <meta name="viewport" content="width=device-width", initial-scale="1.0">
   <link rel="stylesheet" href="style.css">
   <title>KAPILRAJ</title>
</head>
<body>
   <!-- Header section -->
   <div class="header">
      <nav>
         <a href="#"><img src="" alt="" class="" height="" width=""></a>
         <ul>
            <li><a href="#" onclick="showContent('home')">Home</a></li>
            <li><a href="#" onclick="showContent('about')">About</a></li>
            <li><a href="#" onclick="showContent('service')">Service</a></li><li>
            <li><a href="#" onclick="showContent('project')">PROJECTS</a></li>
            <li><a href="#" onclick="showContent('contact')">CONTACT ME</a></li>
            <li><button type="button"class="button-gfc">Get Free Consultant</button></li>
            <li><button type="button" class="button-cv">DOWNLOAD CV</button></li>
         </ul>
         <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Show Content on Click</title>
    <style>
        /* Hide additional content by default */
        .content {
            display: none;
        }
    </style>
</head>
<body>
    <div id="aboutContent" class="content">
        <h2>About </h2>
        <p>"Passionate developer and designer crafting innovative solutions, fusing technology and aesthetics for a digital world."</p>
    </div>

    <div id="serviceContent" class="content">
        <h2>Service </h2>
        <p>"Versatile software/web developer & graphic designer creating seamless digital experiences with creativity and precision."</p>
    </div>

    <script>
        function showContent(section) {
            // Hide all content elements
            var elements = document.querySelectorAll('.content');
            elements.forEach(function(element) {
                element.style.display = 'none';
            });

            // Show the selected content element
            var selectedContent = document.getElementById(section + 'Content');
            if (selectedContent) {
                selectedContent.style.display = 'block';
            }
        }
    </script>

</body>
</html>

      </nav>
      <!DOCTYPE html>
      <html lang="en">
      <head>
          <meta charset="UTF-8">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>Show Content on Click</title>
          <style>
              /* Hide additional content by default */
              .content {
                  display: none;
              }
          </style>
      </head>
      <body>
      
         
      <!-- Body section -->
      <div class="body">
         <p class="demo1">Welcome to My World of Code!</p>
         <h1>Hello <br> I'm Kapil<span>Raj.</span></h1>
         <p class="demo2">From concept to deployment, I bring ideas<br> to life as a versatile full stack developer...</p>

         <button type="button" class="button-lrn">LEARN MORE</button>
         <button type="button" class="button-hire">HIRE ME</button>
      </div>
      <!-- Image section -->
      <div class="image">
         <img src="image/_MG_2255-removebg-preview.png">
      </div>
   </div>
</body>
</html>

<html>
<head>
   <meta name="viewport" content="width=device-width", initial-scale="1.0">
   <link rel="stylesheet" href="style.css">
   <title>Personal portfolio</title>
   <style>
      /* Reset default browser styles */
      * {
         margin: 0;
         padding: 0;
         font-family:sans-serif;
      }

      /* Styles for header section */
      .header {
         width: 100%;
         height: 100vh;
         background-color: lightblue;
      }

      /* Styles for navigation bar */
      nav {
         display: flex;
         margin: auto;
         width: 90%;
         padding: 20px;
         align-items: center;
         justify-content: space-between;
      }

      nav ul li {
         display: inline-block;
         list-style: none;
         margin: 10px;
      }

      nav ul li a {
         text-decoration: none;
         color: black;
         font-weight: bolder;
      }

      nav ul li a:hover {
         background-color: seagreen;
         border-radius: 2px;
         color: white;
      }

      .button-cv, .button-gfc{
         display: inline-block;
         margin-left: 0%;
         border-radius: 5px;
         transition: background-color 0.5s;
         background: black;
         padding: 10px;
         text-decoration: none;
         font-weight: bold;
         color: white;
         border: none;
         cursor: pointer;
      }

      .button-cv:hover {
         background-color: white;
         color: black;
      }

      .button-gfc{
         background: lightsalmon;
      }

      .button-gfc:hover {
         background-color: white;
         color: black;
      }

      /* Styles for body section */
      .body {
         margin-left: 100px;
         margin-top: 100px;
      }

      .body h1 {
         font-size: 30px;
         color: black;
         margin-bottom: 20px;
      }

      .demo1 {
         color: orange;
         margin-bottom: 30px;
      }
  
      .demo2 {
         color: black;
         line-height: 20px;
      }

      .button-lrn, .button-hire{
         background: lightsalmon;
         padding: 10px 12px;
         text-decoration: none;
         font-weight: bold;
         color: whitesmoke;
         display: inline-block;
         margin: 30px 8px;
         border-radius: 5px;
         transition: background-color 0.3s;
         border: none;
         letter-spacing: 1px;
         cursor: pointer;
      }

      .button-lrn:hover {
         background-color: whitesmoke;
         color: black;
      }

      .button-hire {
         background: black;
      }

      .button-hire:hover {
         background-color: seagreen;
      }

      span {
         color: seagreen;
       }

      /* Styles for image section */
      .image {
         width: 45%;
         height: 100%;
         position: absolute;
         bottom: 0;
         right: 100px;
      }
      .image img {
         height: 70%;
         position:absolute;
         left: 50%;
         bottom: 10%;
         transform: translate(-60%);
      }
   </style>
</head>
<body>
   
