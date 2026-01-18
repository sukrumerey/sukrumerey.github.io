<html>
<head>
  <title>My GitHub Website</title>
</head>
<body>

  <!-- TOP MENU -->
  <div>
    <button onclick="showSection('home')">Home</button>
    <button onclick="showSection('about')">About Me</button>
    <button onclick="showSection('contact')">Contact</button>
  </div>

  <hr>

  <!-- SECTIONS -->
  <div id="home" class="section">

    <!-- PHOTO -->
    <img src="photo.jpg" alt="Şükrü Merey" width="200">

    <h1>Hello World!</h1>
    <p>This website is hosted on GitHub Pages.</p>
  </div>

  <div id="about" class="section" style="display:none;">
    <h2>About Me</h2>
    <p>
      Şükrü Merey is currently an Associate Professor...
    </p>
  </div>

  <div id="contact" class="section" style="display:none;">
    <h2>Contact</h2>
    <p>Email: sukrumerey@gmail.com</p>
  </div>

  <script>
    function showSection(sectionId) {
      let sections = document.getElementsByClassName("section");
      for (let i = 0; i < sections.length; i++) {
        sections[i].style.display = "none";
      }
      document.getElementById(sectionId).style.display = "block";
    }
  </script>

</body>
</html>
