[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-f059dc9a6f8d3a56e377f745f24479a46679e63a5d9fe6f495e02850cd0d8118.svg)](https://classroom.github.com/online_ide?assignment_repo_id=6725536&assignment_repo_type=AssignmentRepo)
# full-projects-starter


## structure

index.html -> html code
css/* -> styling
js/* -> javascript code
js/* -> javascript directory
 <!-- search engine
 <div class="search-container">
          <form action="/action_page.php">
            <input type="text" placeholder="Search.." name="search">
          </form>
        </div>--!>
 /*@media (min-width: 750px) {
    body {
        font-family: Verdana, sans-serif;
        margin: 0
    }

    header {
        background-color: white;
        width: 100%;
    }

    .bar {
        margin-top: 15px;
        margin-left: 5%;
        margin-right: 5%;
        background-color: white;

    }

    .container {
        position: relative;
        text-align: center;
        color: white;
        background-color: rgba(255, 255, 255, 0.4);

    }



    .logo img {
        float: left;
        width: 90px;
        height: auto;
        position: relative;
        transform: translate(10%, -980%);

    }


    .logo2 {

        position: absolute;
        top: 45%;
        left: 50%;
        transform: translate(-50%, -50%);

    }



    .navigation a {

        text-decoration: none;
        border-radius: 30px;
        padding: 15px;
        color: black;
        text-decoration: none;
        font-family: 'inter';
        font-weight: bold;
    }

    .navigation a:hover {
        text-decoration: underline solid black;
    }


    .search-container {
        margin-top: 15px;
    }

    .navigation {
        position: relative;
        transform: translate(0%, -1150%);
        display: flex;
        justify-content: space-around;
        float: right;
        background-color: rgba(255, 255, 255, 0.4);
    }



    a {
        border-radius: 0%;
        text-align: center;
        color: white;
        text-decoration: none;
    }

    .us {
        width: 100%;
        height: 400px;
        position: absolute;
        display: flex;
        justify-content: space-around;
        background-color: white;
        border-top-left-radius: 30px;
        border-top-right-radius: 30px;
        transform: translate(0%, -10%);

    }

    .btn {
        position: relative;
        transform: translate(30%, 0);
    }

    button {
        float: center;
        padding: 15px 25px;
        font-size: 18px;
        cursor: pointer;
        text-align: center;
        text-decoration: none;
        outline: none;
        color: black;
        background-color: white;
        border: 3px solid black;
        border-radius: 15px;
    }

    .us h2,
    button {
        text-align: center;
        color: black;
    }

    .item img {
        width: 500px;
        padding-right: 20px;
        padding-left: 20px;
    }

    .word {
        flex: 1;
        width: 50%;
        color: black;
        font-size: 15px;
        padding: 10px 12px;
        bottom: 8px;
        text-align: left;
        margin-left: 5%;
        margin-top: 10%;
    }

    .slideshow-container {
        width: 50%;
        margin-top: 10%;
    }

    .prev,
    .next {
        padding-left: 33%;
        cursor: pointer;
        top: 50%;
        width: auto;
        color: green;
        font-weight: bold;
        font-size: 18px;
        transition: 0.6s ease;
        border-radius: 0 3px 3px 0;
        user-select: none;
    }

    .next {
        right: 0;
        border-radius: 3px 0 0 3px;
    }


    .fade {
        -webkit-animation-name: fade;
        -webkit-animation-duration: 1.5s;
        animation-name: fade;
        animation-duration: 1.5s;
    }

    @-webkit-keyframes fade {
        from {
            opacity: .4
        }

        to {
            opacity: 1
        }
    }

    @keyframes fade {
        from {
            opacity: .4
        }

        to {
            opacity: 1
        }
    }

    @media only screen and (max-width: 300px) {

        .prev,
        .next,
        .text {
            font-size: 11px
        }
    }

    .upcoming {
        background-color: olive;
        width: 100%;
        height: auto;
        position: absolute;
        display: flex;
        border-top-right-radius: 30px;
        border-top-left-radius: 30px;
        transform: translate(0%, 35%);
    }

    .tegels h2 {
        position: relative;
        transform: translate(20%, -10%);
    }

    .tegels {
        flex: 5;
        display: grid;
        grid-template-columns: auto auto auto;
        padding: 10px;
        margin-top: 10%;

    }



    .t1 {
        margin-top: 15%;
        text-align: center;
        background-color: white;
        width: fit-content;
        height: fit-content;
        border-radius: 30px;
        padding-bottom: 5px;
    }

    .t1 img {
        position: relative;
        transform: translate(0, -20%);
        border-radius: 30px;
        width: fit-content;
    }

    h2 {
        text-align: right;
        color: white;
    }

    .left {
        flex: 1;
        background-color: darkgreen;
        border-top-left-radius: 30px;

    }

    .left p {
        text-align: left;
        color: white;
        margin-left: 8%;
    }
}

@media (max-width: 1800px) {
    body {
        font-family: Verdana, sans-serif;
        margin: 0
    }

    header {
        background-color: white;
        width: 100%;
    }

    .bar {
        margin-top: 15px;
        margin-left: 5%;
        margin-right: 5%;
        background-color: white;

    }

    .container {
        position: relative;
        text-align: center;
        color: white;
        background-color: rgba(255, 255, 255, 0.4);

    }



    .logo img {
        float: left;
        width: 90px;
        height: auto;
        position: relative;
        transform: translate(10%, -980%);

    }


    .logo2 {

        position: absolute;
        top: 45%;
        left: 50%;
        transform: translate(-50%, -50%);

    }



    .navigation a {

        text-decoration: none;
        border-radius: 30px;
        padding: 15px;
        color: black;
        text-decoration: none;
        font-family: 'inter';
        font-weight: bold;
    }

    .navigation a:hover {
        text-decoration: underline solid black;
    }


    .search-container {
        margin-top: 15px;
    }

    .navigation {
        position: relative;
        transform: translate(0%, -1150%);
        display: flex;
        justify-content: space-around;
        float: right;
        background-color: rgba(255, 255, 255, 0.4);
    }



    a {
        border-radius: 0%;
        text-align: center;
        color: white;
        text-decoration: none;
    }

    .us {
        width: 100%;
        height: 400px;
        position: absolute;
        display: flex;
        justify-content: space-around;
        background-color: white;
        border-top-left-radius: 30px;
        border-top-right-radius: 30px;
        transform: translate(0%, -20%);

    }

    .btn {
        position: relative;
        transform: translate(39%, 0);
    }

    button {
        float: center;
        padding: 15px 25px;
        font-size: 18px;
        cursor: pointer;
        text-align: center;
        text-decoration: none;
        outline: none;
        color: black;
        background-color: white;
        border: 3px solid black;
        border-radius: 15px;
    }

    .us h2,
    button {
        text-align: center;
        color: black;
    }

    .item img {
        width: 500px;
        padding-right: 20px;
        padding-left: 20px;
    }

    .word {
        flex: 1;
        width: 50%;
        color: black;
        font-size: 15px;
        padding: 10px 12px;
        bottom: 8px;
        text-align: left;
        margin-left: 5%;
        margin-top: 10%;
    }

    .slideshow-container {
        width: 50%;
        margin-top: 10%;
    }

    .prev,
    .next {
        padding-left: 170px;
        cursor: pointer;
        top: 50%;
        width: auto;
        color: green;
        font-weight: bold;
        font-size: 18px;
        transition: 0.6s ease;
        border-radius: 0 3px 3px 0;
        user-select: none;
    }

    .next {
        right: 0;
        border-radius: 3px 0 0 3px;
    }


    .fade {
        -webkit-animation-name: fade;
        -webkit-animation-duration: 1.5s;
        animation-name: fade;
        animation-duration: 1.5s;
    }

    @-webkit-keyframes fade {
        from {
            opacity: .4
        }

        to {
            opacity: 1
        }
    }

    @keyframes fade {
        from {
            opacity: .4
        }

        to {
            opacity: 1
        }
    }

    @media only screen and (max-width: 300px) {

        .prev,
        .next,
        .text {
            font-size: 11px
        }
    }

    .upcoming {
        background-color: olive;
        width: 100%;
        height: auto;
        position: absolute;
        display: flex;
        border-top-right-radius: 30px;
        border-top-left-radius: 30px;
        transform: translate(0%, 35%);
    }

    .tegels h2 {
        position: relative;
        transform: translate(20%, -10%);
    }

    .tegels {
        flex: 5;
        display: grid;
        grid-template-columns: auto auto auto;
        padding: 10px;
        margin-top: 10%;

    }



    .t1 {
        margin-top: 15%;
        text-align: center;
        background-color: white;
        width: fit-content;
        height: fit-content;
        border-radius: 30px;
        padding: 9px;
    }

    .t1 img {
        position: relative;
        transform: translate(0, -26%);
        border-radius: 30px;
        width: fit-content;
    }

    .left h2 {
        width: 400px;
        transform: translate(160%, 0);
        color: white;
    }

    .left {
        flex: 1;
        background-color: darkgreen;
        border-top-left-radius: 30px;

    }

    .left p {
        text-align: left;
        color: white;
        margin-left: 8%;
    }*/
}
 <header>
    <div class="container">
      <div>
        <img src="images/camping_josee_tuin.jpg">
      </div>
      <div class="logo">
      </div>
      <div class="navigation">

        <a href="index.html">Home</a>
        <a href="programma.html">Programma</a>
        <a href="cj.html">Cantine Josée</a>
        <a href="contact.html">About us</a>
        <a href="faq.html">FAQ</a>
      </div>
      <div class="logo2">
        <H1>Camping Josée</H1>
      </div>
    </div>
    </div>
  </header>
  <div class="content">
    <div class="us">
      <div class="word">
        <H2>Who are we?</H2>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
          enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi
          ut aliquip ex ea commodo consequat. Duis aute irure dolor in
          reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla
          pariatur. Excepteur sint occaecat cupidatat non proident, sunt in
          culpa qui officia deserunt mollit anim id est laborum...
        </p>

      </div>
      <div class="slideshow">

        <div class="item fade">
          <img src="images/1.png">
        </div>

        <div class="item fade">
          <img src="images/1.png">
        </div>

        <div class="item fade">
          <img src="images/1.png">
        </div>

        <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
        <a class="next" onclick="plusSlides(1)">&#10095;</a>

      </div>
      <div class="btn">
        <button>Read More</button>

      </div>
      <script>
        var slideIndex = 1;
        showSlides(slideIndex);

        function plusSlides(n) {
          showSlides(slideIndex += n);
        }

        function currentSlide(n) {
          showSlides(slideIndex = n);
        }

        function showSlides(n) {
          var i;
          var slides = document.getElementsByClassName("item");
          if (n > slides.length) {
            slideIndex = 1
          }
          if (n < 1) {
            slideIndex = slides.length
          }
          for (i = 0; i < slides.length; i++) {
            slides[i].style.display = "none";
          }

          slides[slideIndex - 1].style.display = "flex";
        }
      </script>


    </div>
    <div class="upcoming">
      <div class="left">
        <h2>Our upcoming activities</h2>
        <p>
          Wat <br>
          <br>
          Cursus & Vorming <br>
          Evenement <br>
          Lezing & gesprek <br>
          Podium & Film <br>
          <br>
          Voor wie <br><br>
          0-2,5 jaar <br>
          2,5-6 jaar<br>
          6-12 jaar<br>
          12-18 jaar<br>
          18+<br>
          50+<br><br>
          Families<br><br>
          Wanneer<br><br>
          Volgende 7 <br>
          Dit weekend<br>
          Volgende 30 dagen<br><br>
          Extra's<br><br>

          Gratis<br>
          Online<br>

        </p>
      </div>

      <div class="tegels">

        <div class="t1">
          <img src="images/1.png">
          <div class="t">
            <h4>Nieuwjaars feest</h4>
            <p>
              Voor wie <br>
              0 - 99 jaar

            </p> <br>
            <p>
              Wanneer <br>
              vr 28.01.2022 <br>
              van 18.00 tot 23.00 u.

            </p><br>
            <p>
              Locatie
              Le Thé au Harem <br>
              Leuvensesteenweg 52 <br>
              1210 Sint-Joost-ten-Node <br>
            </p>
            <button>More details</button>

          </div>

        </div>
        <div class="t1">
          <img src="images/1.png">
          <h4>Nieuwjaars feest</h4>
          <p>
            Voor wie <br>
            0 - 99 jaar

          </p> <br>
          <p>
            Wanneer <br>
            vr 28.01.2022 <br>
            van 18.00 tot 23.00 u.

          </p><br>
          <p>
            Locatie
            Le Thé au Harem <br>
            Leuvensesteenweg 52 <br>
            1210 Sint-Joost-ten-Node <br>
          </p>
          <button>More details</button>
        </div>
        <div class="t1">
          <img src="images/1.png">
          <h4>Nieuwjaars feest</h4>
          <p>
            Voor wie <br>
            0 - 99 jaar

          </p> <br>
          <p>
            Wanneer <br>
            vr 28.01.2022 <br>
            van 18.00 tot 23.00 u.

          </p><br>
          <p>
            Locatie
            Le Thé au Harem <br>
            Leuvensesteenweg 52 <br>
            1210 Sint-Joost-ten-Node <br>
          </p>
          <button>More details</button>

        </div>
        <div class="t1">
          <img src="images/1.png">
          <div class="t">
            <h4>Nieuwjaars feest</h4>
            <p>
              Voor wie <br>
              0 - 99 jaar

            </p> <br>
            <p>
              Wanneer <br>
              vr 28.01.2022 <br>
              van 18.00 tot 23.00 u.

            </p><br>
            <p>
              Locatie
              Le Thé au Harem <br>
              Leuvensesteenweg 52 <br>
              1210 Sint-Joost-ten-Node <br>
            </p>
            <button>More details</button>

          </div>

        </div>
        <div class="t1">
          <img src="images/1.png">
          <div class="t">
            <h4>Nieuwjaars feest</h4>
            <p>
              Voor wie <br>
              0 - 99 jaar

            </p> <br>
            <p>
              Wanneer <br>
              vr 28.01.2022 <br>
              van 18.00 tot 23.00 u.

            </p><br>
            <p>
              Locatie
              Le Thé au Harem <br>
              Leuvensesteenweg 52 <br>
              1210 Sint-Joost-ten-Node <br>
            </p>
            <button>More details</button>
          </div>
        </div>
      </div>
    </div>
  </div>
  <footer>

  </footer>