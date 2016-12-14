# DankMemes.github.io
Website
<!DOCTYPE html>
<html>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="http://www.w3schools.com/lib/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body,h1,h2,h3,h4,h5,h6 {font-family: "Lato", sans-serif;}
body, html {
    height: 100%;
    color: #777;
    line-height: 1.8;
}

/* Create a Parallax Effect */
.bgimg-1, .bgimg-2, .bgimg-3 {
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

/* First image (Logo. Full height) */
.bgimg-1 {
    background-image: url("http://doge2048.com/meta/doge-600.png");
    min-height: 100%;
}

/* Second image (MEMES) */
.bgimg-2 {
    background-image: url("http://doge2048.com/meta/doge-600.png");
    min-height: 400px;
}


.w3-wide {letter-spacing: 10px;}
.w3-hover-opacity {cursor: pointer;}

/* Turn off parallax scrolling for tablets and phones */
@media only screen and (max-device-width: 1024px) {
    .bgimg-1, .bgimg-2, .bgimg-3 {
        background-attachment: scroll;
    }
}
</style>
<body>

<!-- Navbar (sit on top) -->
<div class="w3-top">
  <ul class="w3-navbar" id="myNavbar">
    <li class="w3-hide-medium w3-hide-large w3-opennav w3-right">
      <a class="w3-hover-black" href="javascript:void(0);" onclick="toggleFunction()" title="Toggle Navigation Menu">
        <i class="fa fa-bars"></i>
      </a>
    </li>
    <li class="w3-left-align"><a href="#home">HOME</a></li>
    <li class="w3-hide-small"><a href="#about"><i class="fa fa-user"></i> ABOUT</a></li>
    <li class="w3-hide-small"><a href="#portfolio"><i class="fa fa-th"></i> PORTFOLIO</a></li>
    <li class="w3-hide-small"><a href="#contact"><i class="fa fa-envelope"></i> CONTACT</a></li>
    <li class="w3-hide-small w3-right">
      <a href="#" class="w3-hover-red">
        <i class="fa fa-search"></i>
      </a>
    </li>
  </ul>

  <!-- Navbar on small screens -->
  <div id="navDemo" class="w3-hide w3-hide-large w3-hide-medium">
    <ul class="w3-navbar w3-left-align w3-white">
      <li><a href="#about" onclick="toggleFunction()">ABOUT</a></li>
      <li><a href="#portfolio" onclick="toggleFunction()">PORTFOLIO</a></li>
      <li><a href="#contact" onclick="toggleFunction()">CONTACT</a></li>
      <li><a href="#">SEARCH</a></li>
    </ul>
  </div>
</div>

<!-- First Parallax Image with Logo Text -->
<div class="bgimg-1 w3-display-container w3-opacity-min" id="home">
  <div class="w3-display-middle" style="white-space:nowrap;">
    <span class="w3-center w3-padding-xlarge w3-black w3-xlarge w3-wide w3-animate-opacity">MY <span class="w3-hide-small">MEME</span> COLLECTION</span>
  </div>
</div>

<!-- Container (About Section) -->
<div class="w3-content w3-container w3-padding-64" id="about">
  <h3 class="w3-center">ABOUT ME</h3>
  <p class="w3-center"><em>I love Memes</em></p>
  <p>Here's a Small Collection of the Dankest Of Memes</p>
  <div class="w3-row">
    <div class="w3-col m6 w3-center w3-padding-large">
      <p><b><i class="fa fa-user w3-margin-right"></i>My Name</b></p><br>
      <img src="/w3images/avatar_hat.jpg" class="w3-round w3-image w3-opacity w3-hover-opacity-off" alt="Photo of Me" width="500" height="333">
    </div>

    <!-- Hide this text on small devices -->
    <div class="w3-col m6 w3-hide-small w3-padding-large">
      <p>Welcome to my website. I am Gabriel Carruth </p>
    </div>
  </div>
  <p class="w3-large w3-center w3-padding-16">Im really good at:</p>
  <p class="w3-wide"><i class="fa fa-camera"></i>Web Design</p>
  <div class="w3-progress-container">
    <div class="w3-progressbar" style="width:5%"></div>
  </div>
  <p class="w3-wide"><i class="fa fa-laptop"></i>Computer Science</p>
  <div class="w3-progress-container">
    <div class="w3-progressbar" style="width:2%"></div>
  </div>
  <p class="w3-wide"><i class="fa fa-photo"></i>Dank Memes</p>
  <div class="w3-progress-container">
    <div class="w3-progressbar" style="width:425%"></div>
  </div>
</div>



<!-- Second Parallax Image with Portfolio Text -->
<div class="bgimg-2 w3-display-container w3-opacity-min">
  <div class="w3-display-middle">
    <span class="w3-xxlarge w3-text-light-grey w3-wide">MEME</span>
  </div>
</div>

<!-- Container (Portfolio Section) -->
<div class="w3-content w3-container w3-padding-64" id="portfolio">
  <h3 class="w3-center">MEMES</h3>
  <p class="w3-center"><em>Here are some of my favorite Dank Memes.

  <!-- Responsive Grid. Four columns on tablets, laptops and desktops. Will stack on mobile devices/small screens (100% width) -->
  <div class="w3-row-padding w3-center">
    <div class="w3-col m3">
      <img src="http://pixel.nymag.com/imgs/daily/selectall/2016/07/27/harambe_meme_001.nocrop.w536.h2147483647.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Harambe">
    </div>

    <div class="w3-col m3">
      <img src="https://pbs.twimg.com/media/CM8kfR3VAAADTlY.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Atleast 12">
    </div>

    <div class="w3-col m3">
      <img src="https://s-media-cache-ak0.pinimg.com/564x/1f/0c/3d/1f0c3ddd9ba2f0bb8ec21eec5c583f04.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="funerals">
    </div>

    <div class="w3-col m3">
      <img src="http://www.relatably.com/m/img/best-memes-ever-tumblr/wat-lady.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Wat">
    </div>
  </div>

  <div class="w3-row-padding w3-center w3-section">
    <div class="w3-col m3">
      <img src="http://i.dailymail.co.uk/i/pix/2016/11/03/13/3A06817800000578-3901486-image-a-5_1478178076212.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="World Series">
    </div>

    <div class="w3-col m3">
      <img src="https://62e528761d0685343e1c-f3d1b99a743ffa4142d9d7f1978d9686.ssl.cf2.rackcdn.com/files/38926/width926/5cwx89t4-1389586191.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Memes">
    </div>

    <div class="w3-col m3">
      <img src="http://i2.kym-cdn.com/photos/images/facebook/000/581/722/7bc.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Doge">
    </div>

    <div class="w3-col m3">
      <img src="http://static5.businessinsider.com/image/511d104a69bedd1f7c000012/grumpy-cat-definitely-did-not-make-100-million.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Doge Again">
    </div>
  </div>
</div>



<!-- Third Parallax Image with Portfolio Text -->
<div class="bgimg-3 w3-display-container w3-opacity-min">
  <div class="w3-display-middle">
     <span class="w3-xxlarge w3-text-light-grey w3-wide">CONTACT</span>
  </div>
</div>

<!-- Container (Contact Section) -->
<div class="w3-content w3-container w3-padding-64" id="contact">
  <h3 class="w3-center">Contact Me At</h3>
  <p class="w3-center"><em>gcarruth@buffalo.edu</em></p>

       
        <button class="w3-btn w3-black w3-right w3-padding w3-section" type="submit">
          <i class="fa fa-paper-plane"></i> SEND MESSAGE
        </button>
      </form>
    </div>
  </div>
</div>

<!-- Footer -->
<footer class="w3-center w3-black w3-padding-64 w3-opacity w3-hover-opacity-off">
  <a href="#home" class="w3-btn w3-padding w3-light-grey w3-hover-grey"><i class="fa fa-arrow-up w3-margin-right"></i>To the top</a>
  <div class="w3-xlarge w3-section">
    
    <i class="fa fa-instagram w3-hover-text-purple"></i>   
    <i class="fa fa-twitter w3-hover-text-light-blue"></i>
    <i class="fa fa-linkedin w3-hover-text-indigo"></i>
  </div>
  
</footer>
 





</script>

</body>
</html>
