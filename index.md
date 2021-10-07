<!-- Index -->
<!-- Ajustments to get a 10.0 hope to be correct -->
<!DOCTYPE html>
<html lang="en-US">
  <head>
    <!-- Adding the title to display on the Browser -->
    <title>WDD 130 | Dry Oar Boating </title>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <link rel="stylesheet" href="/styles.css" />
  </head>

  <body>
    <!-- Step 06 - Header content -->
    <header>
      <div class="logo-box"><!-- logo will go here -->
        <img src="https://cdn.glitch.com/a02fca50-591e-45a0-ab01-de7081583d84%2Fexcitingexpedition.jpg?v=1632413286399" alt="Dry Oar boating logo">
      </div>
      <!-- Step 07 - Finish the Menu -->
      <nav>
        <ul>
          <li><a href="index.html">Home</a></li>
          <li><a href="lakes.html">Lakes</a></li>
          <li><a href="moments.html">Moments</a></li>
          <li><a href="aboutme.html">About Me</a></li>
        </ul>
      </nav>

    </header>
    <main>
      <!-- Step 08 - Add a Banner => Add a wide banner image. -->
      <div class="banner-box">
        <!-- Image bellow the links -->
        <img src="https://byui-cit.github.io/wdd130/resources/images/salmon-kayak-banner1.jpg" alt="Nature">        
      </div>
      <!-- Step 04 - wireframe mention to have 2 <div> 1 for  banner-box and other for home-grid -->
        <!--  Lets add unique classes to each of those divs that describe what will be inside them. For example for the banner lets add class="banner-box" and for the rest of the content add class="home-grid" (this name will make more sense later). -->

        <!-- Step 09 - Add the Main content => Start right below the banner in the wireframe and read left to right top to bottom to add the content. All of these elements will go inside of the home-grid div. -->

      <div class="home-grid">
        
          <!-- First part of the wireframe -->
          <h2 class="home-headline-1">We run rivers to relas</h2>
          <p class="home-paragraph-1">We believe that there is nothing like a river trip for relaxing. That is why we subscribe to the dry oar philosophy of boating. Keeping your oars dry for us means taking time to look around and notice the beauty that surrounds the rivers we love.</p>
          <!-- Image on the right side -->
          <img class="home-right-img" src="https://byui-cit.github.io/wdd130/resources/images/deso-boats.jpg" alt="Peaceful evening shot of a river">
        
      
        
          <!-- Second part of the wirefram -->
          <h2 class="home-headline-2">We run whitewater for the rush</h2>
          <p class="home-paragraph-2">That doesn't mean we don't also like rapids. Opposites in all things after all. We believe that that tenseness that comes when you are looking down the tongue of a big string of waves makes you appreciate the calm beautiful water that always follows even more.</p>
          <!-- Image on the left side -->
          <img class="home-left-img" src="https://byui-cit.github.io/wdd130/resources/images/deercreek-portrait.jpg" alt="Nature">
        
      
       <!-- Step 10 - Finishing up the main content -->
       <!-- Let's use a <section> element for this. Add a <section> with a class of home-paragraph-3 inside and at the bottom of the .home-grid element, then add a headline and paragraph inside of that element like we did above. -->
        <section class="home-paragraph-3">
          <!-- Third part of the wirefram -->
          <h2>Come run with us</h2>
          <p>We invite you to come relax with us on one of the amazing rivers we visit. Check out our trips and let us know which one best suits you. We're waiting to hear from you!</p>
        </section>     
      </div>

      
    </main>
    <footer>
      <!-- Test => Copyright © 2021 - Dry Oar - Daniel Penha - WDD 130-16 -->
      
      <!-- Footer Copyright -->
      <p>&copy; 2021 Dry Oar - Daniel Penha - WDD 130-16 </p>
      <!-- Images on the right side -->
      <img src="https://placeimg.com/50/50/nature" alt="Nature">
      <img src="https://placeimg.com/50/50/nature" alt="Nature">
      <img src="https://placeimg.com/50/50/nature" alt="Nature">

      <!-- Site map -->
      <ul>
        <li>
          <a href="index.html">Home</a> |
          <a href="lakes.html">Lakes</a> |
          <a href="moments.html">Moments</a> |
          <a href="aboutme.html">About Me</a>
        </li>
      </ul>
    </footer>
  </body>
</html>
