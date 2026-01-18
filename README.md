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
    <h1>
     Hello World!</h1>
    <p>This website is hosted on GitHub Pages.</p>
  </div>

  <div id="about" class="section" style="display:none;">
    <h2>About Me</h2>
    <p>
<img src="![sukrumereyphoto](https://github.com/user-attachments/assets/b1983d80-2bcd-4296-a9f7-a9b7c46ad86c)" alt="Şükrü Merey" width="200">
Şükrü Merey is currently  an Associate Professor in the Department of Petroleum and Natural Gas Engineering, Batman University, Batman-Turkey. He got BSc., MSc., and Ph.D. degrees from the Department of Petroleum and Natural Gas Engineering, Middle East Technical University, Ankara-Turkey in 2009, 2013, and 2017, respectively. In 2010 (3 months), he worked as a petroleum and natural gas engineer at the General Directorate of Petroleum Affairs of Turkey in Ankara. Then, he worked as a well-completion engineer at Turkish Petroleum Corporation (Adiyaman, Turkey) for more than 1 year between 2010 and 2011. Between 2011 and 2017, he worked as a research assistant in the Department of Petroleum and Natural Gas Engineering, Middle East Technical University, Ankara-Turkey. Between 2018 and 2020, he worked as an Asst.Prof.Dr. at the Department of Petroleum and Natural Gas Engineering, Batman University, Batman, Turkey. Dr. Merey also worked as a visiting scientist at USGS Central Energy Resources Science Center, Lakewood-Colorado (2022-2023) and Associated Researcher at Colorado School of Mines, Department of Geophysics, Golden, CO, USA (2022-2024). His current research topics include gas (methane) hydrates, well completion, well stimulation, reservoir simulation, machine learning in petroleum and natural gas engineering applications, adsorption, CO2 sequestration, underground gas storage, geothermal, reservoir geomechanics, shale gas reservoirs, hydrogen, and coalbed methane.
Please see www.sukrumerey.com for more info!
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
