<head>
  <title>My Page</title>
  <style>
  table {
    border-collapse: collapse;
  }
  th {
    padding:5px;
  }
  td {
    border: 1px solid #ddd;
    padding: 5px;
  }
  tr:nth-child(even) {
    background-color: #f2f2f2;
  }
  th {
    padding-top: 12px;
    padding-bottom: 12px;
    text-align: left;
    background-color: #add8e6;
    color: black;
  }
  .block {
  width: 100px;
  /*float: left;*/
    display: inline-block;
    zoom: 1;
  }
  .column {
  float: left;
  height: 200px;
  /*width: 33.33%;*/
  padding: 5px;
  }

  .row::after {
    content: "";
    clear: both;
    display: table;
  }
</style>
</head>
<body>
  <h1>Welcome to my page!</h1>
  <img src="./images/selfie.JPG" width="300px">
  <h3>About me</h3>
  <p>Mahsa (Zara) - Ph.D. in Data Science
Passionate About: Python, Machine Learning, and the Power of Data</p>
  <p>Here is a link to my linkedin: <a href="https://www.linkedin.com/in/zahrakaramimehr/">LinkedIn</a></p>
  <p>I’ve been captivated by technology since the first year of guidance school when I got my hands on my very own PC. This early experience sparked my journey into the world of computers, leading me to pursue a degree in Computer Science at university. My growing interest in statistics and data analysis naturally guided me towards a career in Data Science, where I now blend creativity with analytical precision to unlock insights from data.</p>
  <h3>Hobbies</h3>
  <p>When I'm not immersed in coding or data analysis, I love to stay active. You'll often find me swimming, hiking, biking, or practicing yoga. I also have a strategic side—I'm an avid board game enthusiast, with Backgammon being my favorite. These activities keep my mind sharp and my creativity flowing. </p>
  <h3>Fun Facts</h3>
  <ul class="fun-facts">
    <li> Almost an Animator: I originally wanted to become an animator, but my passion for data won out in the end.</li>
    <li>Name Game: My actual name is Zara, though most people know me as Mahsa.</li>
    <li>First Flight: I never set foot on a plane until I started college.</li>
    <li>Literary Love: I’m a huge fan of the <i>Harry Potter</i>series.</li>
    <li>Teenage Tunes: <i> Backstreet Boys</i> were my absolute favorite band growing up.</li>
  </ul>
  <h2>Social Media</h2>
    I am not really active on social media but in case you want to take a look at them:
  <br/>
  <ul class="socials">
    <li class="social instagram"><b>Instagram: </b><a href="https://www.instagram.com/mah5akmehr">My instagram</a></li>
    <li class="social twitter"><b>Twitter: </b><a href="https://x.com/MKaramimehr">My twitter</a></li>
    <li class="social linkedin"><b>LinkedIn: </b><a href="https://www.linkedin.com/in/zahrakaramimehr/">My linkedIn</a></li>
  </ul>
  <h2>Photos</h2>
  Here are a few photos from a trip to Europe I took 2 years ago:
  <div class="row">
    <div class="column">
      <img src="images/Bologna.jpg" alt="Santuario Madonna di San Luca,Bologna,Italy" style="height:100%">
    </div>
    <div class="column">
      <img src="images/vienna.jpg" alt="The Austrian Parliament,Vienna, Austia" style="height:100%">
    </div>
    <div class="column">
      <img src="images/vapiano.JPG" alt="Vapiano Restaurant" style="height:100%">
    </div>
  </div>
  <div></div>
  <h2> Sport </h2>
  
  <br>
<!--   <table class="world-cup-stats">
  <thead>
      <tr>
          <th class="year" data-sort="">Year</th>
          <th class="team" data-sort="team">Winner</th>
          <th class="team" data-sort="team">Runner-up</th>
          <th class="score" data-sort="score">Final Score</th>
          <th class="location" data-sort="location">Host Country</th>
      </tr>
  </thead>
  <tbody>
      <tr class="team-world-cup">
          <td class="year sorted">2022</td>
          <td class="team">Argentina</td>
          <td class="team">France</td>
          <td class="score">3-3 (4-2 pens)</td>
          <td class="location">Qatar</td>
      </tr>
      <tr class="team-world-cup">
          <td class="year sorted">2018</td>
          <td class="team">France</td>
          <td class="team">Croatia</td>
          <td class="score">4-2</td>
          <td class="location">Russia</td>
      </tr>
      <tr class="team-world-cup">
          <td class="year sorted">2014</td>
          <td class="team">Germany</td>
          <td class="team">Argentina</td>
          <td class="score">1-0</td>
          <td class="location">Brazil</td>
      </tr>
      <tr class="team-world-cup">
          <td class="year sorted">2010</td>
          <td class="team">Spain</td>
          <td class="team">Netherlands</td>
          <td class="score">1-0</td>
          <td class="location">South Africa</td>
      </tr>
      <tr class="team-world-cup">
          <td class="year sorted">2006</td>
          <td class="team">Italy</td>
          <td class="team">France</td>
          <td class="score">1-1 (5-3 pens)</td>
          <td class="location">Germany</td>
      </tr>
  </tbody>
</table> -->
<table border="1">
  <thead>
    <tr>
      <th>Year</th>
      <th>Country</th>
      <th>Event</th>
      <th>Gold</th>
      <th>Silver</th>
      <th>Bronze</th>
      <th>Total Medals</th>
      <th>+/-</th>
      <th></th>
      <th>POST</th>
      <th>GP</th>
      <th>G</th>
      <th>A</th>
      <th>TP</th>
      <th>PIM</th>
      <th>+/-</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>2020</td>
      <td>United States</td>
      <td>Summer Olympics</td>
      <td>39</td>
      <td>41</td>
      <td>33</td>
      <td>113</td>
      <td>+1</td>
      <td></td>
      <td>1st</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>+1</td>
    </tr>
    <tr>
      <td>2016</td>
      <td>United States</td>
      <td>Summer Olympics</td>
      <td>46</td>
      <td>37</td>
      <td>38</td>
      <td>121</td>
      <td>+1</td>
      <td></td>
      <td>1st</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>+1</td>
    </tr>
    <tr>
      <td>2012</td>
      <td>United States</td>
      <td>Summer Olympics</td>
      <td>46</td>
      <td>28</td>
      <td>29</td>
      <td>103</td>
      <td>+1</td>
      <td></td>
      <td>1st</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>+1</td>
    </tr>
    <tr>
      <td>2008</td>
      <td>China</td>
      <td>Summer Olympics</td>
      <td>48</td>
      <td>22</td>
      <td>30</td>
      <td>100</td>
      <td>+1</td>
      <td></td>
      <td>1st</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>+1</td>
    </tr>
    <tr>
      <td>2004</td>
      <td>United States</td>
      <td>Summer Olympics</td>
      <td>36</td>
      <td>39</td>
      <td>26</td>
      <td>101</td>
      <td>+1</td>
      <td></td>
      <td>1st</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>+1</td>
    </tr>
  </tbody>
</table>

  <h2>Mystery Message Challenge!</h2>
  <p>If you scrape the links below grabbing the &lt;p&gt; tag with id="secret-word", you'll discover a secret message :)</p>
  <div width="50%">
  <div class="block" align="left">
    <ul>
      <li><a href="challenge/file_1.html">File 1</a></li>
      <li><a href="challenge/file_2.html">File 2</a></li>
      <li><a href="challenge/file_3.html">File 3</a></li>
      <li><a href="challenge/file_4.html">File 4</a></li>
      <li><a href="challenge/file_5.html">File 5</a></li>
    </ul>
  </div>
  <div class="block" align="center">
    <ul>
      <li><a href="challenge/file_6.html">File 6</a></li>
      <li><a href="challenge/file_7.html">File 7</a></li>
      <li><a href="challenge/file_8.html">File 8</a></li>
      <li><a href="challenge/file_9.html">File 9</a></li>
      <li><a href="challenge/file_10.html">File 10</a></li>
    </ul>
  </div>
  </div>

  
  </body>
