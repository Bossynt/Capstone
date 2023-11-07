# Capstone
Making a website in which would teach student about math
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>MUIDS Press | Home</title>
    <link rel="icon" type="image/x-icon" href="imgs/favicon.ico" />

    <!-- fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Maitree:wght@300;500&family=Thasadith&display=swap"
      rel="stylesheet"
    />

    <!-- linking to onload_head.js -->
    <script src="js/onload_head.js"></script>
    <script src="js/sticky_head.js"></script>

    <!-- linking to sticky header -->
    <link rel="stylesheet" href="css/stick_header.css" />

    <body onload="onload_head()" onscroll="check_sticky()">
      <!-- linking to the main body -->
      <link rel="stylesheet" href="css/main.css" />

      <header>
        <div class="navbar">
          <img src="imgs/logo.png" id="logo_nav" />
          <div id="name">MUIDS Journalism Club</div>
          <nav>
            <ul>
              <li><a href="index.html">HOME</a></li>
              <li><a href="regulations.html">REGULATIONS</a></li>
              <li><a href="regulations.html">MEMBERS</a></li>
              <li><a href="about.html">ABOUT</a></li>
            </ul>
            <button onclick="location.href = 'discover.html'">DISCOVER</button>

            <!-- hamburger menu -->
          </nav>

          <!-- menu script -->
          <script src="js/menu.js"></script>
          <button id="menu" onclick="menu_onclick()">
            <img src="imgs/menu.png" id="menu_img" />
          </button>
        </div>

        <!-- linking to navbar -->
        <link rel="stylesheet" href="css/header.css" />
        <link rel="stylesheet" href="css/_menu.css" />
      </header>

      <!-- sidebar -->
      <div class="sidebar">
        <div class="side_con">
          <ul>
            <li><a href="index.html">HOME</a></li>
            <li><a href="regulations.html">REGULATIONS</a></li>
            <li><a href="members.html">MEMBERS</a></li>
            <li><a href="about.html">ABOUT</a></li>
            <li><a href="discover.html">DISCOVER</a></li>
          </ul>
        </div>
      </div>

      <!-- main article 
      <div class="roll1">
        <img src="imgs/roll1/pic1.jpg" id="picture_roll" />
      </div> -->

      <!-- linking 
      <div class="text1">
        <div id="title1">About MUIDS Press</div>
        <div id="subtitle1">
          <a>Learn more ></a>
        </div>
      </div> -->

      <!-- linking to main article -->
      <script src="js/camera_roll.js"></script>
      <link rel="stylesheet" href="css/picroll.css" />
      <link rel="stylesheet" href="css/_picroll.css" />

      <!-- buttons scripts -->
      <script src="js/camera_roll.js"></script>

      <!-- buttons 
      <div class="roll_buttons">
        <button id="arr-left">
          <img src="imgs/arr-left.svg" onclick="roll_left(this)" />
        </button>
        <button id="arr-right">
          <img src="imgs/arr-right.svg" onclick="roll_right(this)" />
        </button>
      </div> -->

      <!-- linking to buttons -->
      <link rel="stylesheet" href="css/buttons.css" />

      <!-- introduction -->
      <div class="intro">
        <div class="art_title">About Us
	 </div>
        <p>
         Founded by a MUIDS student on July 7th 2023, with support from his former 
	 classmates in section 1004, many of whom share similar interests in the field of journalism. 
	 MUIDS Press was created as a main media corporation under Mahidol University International Demonstration School, 
	 with two main clubs integrated into one category of Press. 
	 The organization held many responsibilities when it came to giving detailed and valuable information 
	 regarding the school events and the promotion of students literature or research works through the usage of 
	 publication in the Press official website or school broadcasting service.
        </p>
      </div>

      <!-- linking to intro area-->
      <link rel="stylesheet" href="css/intro.css" />
	    
      <!-- link to news boxes -->
      <link rel="stylesheet" href="css/news_boxes.css" />
      <link rel="stylesheet" href="css/_news_boxes.css" />

	     <!-- Our Objectives -->
      <div class="meet_title2">
        <p>Our Objective </p>
      </div>
      <div class="meet">
        <div class="meet_content">
          <p>
           We strive to not only become MUIDS main media but also to function as any other Press in the academia with regulations 
	   implemented as a precaution to our school reputation. 
	   The organization recognizes the talents of those with literary skills and the determination to explore the world of journalism, literature, academics, and research. 
	   We offer students the opportunity to have their works recognized officially by the school with the ensurement of maximum credibility.
	   Our club activities are not limited to only school areas as we also provide students with events regarding community service, outdoor journalism activities, and their unbiased and non-controversial opinions regarding philosophies.

          </p>
          <img src="imgs/roll1/pic4.jpg" />  
        </div>
      </div>

	    <!-- Structure -->
      <div class="meet_title3">
        <p>Affiliation</p>
      </div>
      <div class="meet">
        <div class="meet_content">
          <p>
          The Press Club, Newspaper Club, Broadcasting Club, and Magazine Club will work together to form a united Press Board with each president and vice-president of 
	  each club holding executive power for miscellaneous and immediate tasks to expedite any decisions that could prolong unnecessarily. 
	  In other scenarios, the power shall remain in the hands of the council where decisions will be made once a consensus is reached within it.
          </p>
          <img src="imgs/roll1/pic5.jpg" /> 
        </div>
      </div>
	    
      <!-- linking to meet our team -->
      <link rel="stylesheet" href="css/meet_our_team.css" />
      <link rel="stylesheet" href="css/_meet_our_team.css" />

      <!-- linking to all.css -->
      <link rel="stylesheet" href="css_about/all.css" />

      <!-- footer -->
      <footer>
        <div class="end_strip"></div>
        <div class="footer">
          <div class="left">
            <ul id="bottom_inline_list">
              <li><button><img src="imgs/gmail.svg"></button></li>
              <li><button><img src="imgs/instagram.svg"></button></li>
            </ul>
            <div class="bottom_list">
              <ul>
                <li><a>Home</a></li>
                <li><a>Regulations</a></li>
                <li><a>Members</a></li>
                <li><a>About</a></li>
              </ul>
            </div>
            <div class="basic_info">
              <p>
                MUIDS Press Club <br />
                Mahidol University International Demonstration School <br />
                Nakhon Pathom, Thailand
              </p>
            </div>
            <div class="copyright">
              <p>
                © 2023 MUIDS Press Club
              </p>
            </div>
          </div>
          <div class="mid">
            <div class="end_logo">
                <img src="imgs/logo.png">
            </div>
          </div>
          <div class="right">
            <div id="affiliation">
              Affiliation
            </div>
            <div id="muids_address">
              Mahidol University International Demonstration School <br />
              +66 (0) 2-408-8555 Mahidol University, 999 Phutthamonthon Sai 4 Rd, Salaya, Phutthamonthon District, Nakhon Pathom 73170
            </div>
            <div id="bottom_button_holder">
              <button>
                <img src="imgs/muids_logo.png" id="muids_logo_bottom">
              </button>
            </div>
          </div>
        </div>
      </footer>

      <!-- linking to footer -->
      <link rel="stylesheet" href="css/footer.css" />
      <link rel="stylesheet" href="css/_footer.css"/>
    </body>
  </head>
</html>
