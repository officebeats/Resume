<head>
  <title>Ernesto Rodriguez - Portfolio</title>
  <style>
    .grid-container {
      display: grid;
      grid-template-columns: repeat(4, 1fr); /* Set 4 equal columns */
      gap: 20px;
      margin-bottom: 40px; /* Added spacing below each job section */
    }

    .grid-item img {
      max-width: 100%; /* Full width of the grid item */
      height: auto;
      cursor: pointer;
      transition: transform 0.3s ease-in-out;
    }

    .grid-item img:hover {
      transform: scale(1.05);
    }

    /* Lightbox overlay */
    .lightbox {
      display: none;
      position: fixed;
      z-index: 999;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-color: rgba(0, 0, 0, 0.8);
      justify-content: center;
      align-items: center;
    }

    .lightbox img {
      max-width: 90%;
      max-height: 90%;
    }

    .lightbox:target {
      display: flex;
    }

    /* Close button */
    .close {
      position: absolute;
      top: 10px;
      right: 20px;
      color: white;
      font-size: 30px;
      font-weight: bold;
      text-decoration: none;
    }
  </style>
</head>

<body>

  <div align="center">
    <h1>Ernesto Rodriguez</h1>
    <p>
      <strong>Innovative Product Management Leader with 10+ years in launching & scaling software & hardware products.</strong><br>
      Expert in user-centered design, agile methodologies, & data-driven strategy.<br>
      Startup hustle with a strategic execution.
    </p>
  </div>

  <hr>

  <h2>Experience</h2>

  <h3>Route | Head Of Product <span style="float: right;">Mar 2024 - Oct 2024</span><br> Field Services 🛠️</h3>

  <div class="grid-container">
    <div class="grid-item">
      <ul>
        <li>Spearheaded product vision & strategy, driving MRR growth as a key member of the leadership team.</li>
        <li>Defined and managed amplitude analytics & unified backend systems across 3 products to enhance user analysis.</li>
        <li>Managed and staffed a diverse team of 10 technologists including product managers, engineers & designers.</li>
        <li>Evaluated & integrated external vendor solutions for enhanced product offerings.</li>
        <li>Directly contributed to securing a $250k investment by Morgan Stanley.</li>
      </ul>
    </div>
    <div class="grid-item">
      <a href="#img1"><img src="images/Route_Marketplace_Profile_Pins_and_Cards.png"></a>
      <a href="#img2"><img src="images/Proposal_Tool_new.png"></a>
      <a href="#img3"><img src="images/Route_Marketplace_Hover State_Pins.png"></a>
      <a href="#img4"><img src="images/Route_Marketplace_Profile_Pins_and_Cards_expanded.png"></a>
    </div>
  </div>

  <div id="img1" class="lightbox">
    <a href="#" class="close">&times;</a>
    <img src="images/Route_Marketplace_Profile_Pins_and_Cards.png">
  </div>

  <div id="img2" class="lightbox">
    <a href="#" class="close">&times;</a>
    <img src="images/Proposal_Tool_new.png">
  </div>

  <div id="img3" class="lightbox">
    <a href="#" class="close">&times;</a>
    <img src="images/Route_Marketplace_Hover State_Pins.png">
  </div>

  <div id="img4" class="lightbox">
    <a href="#" class="close">&times;</a>
    <img src="images/Route_Marketplace_Profile_Pins_and_Cards_expanded.png">
  </div>

  <br><br>

  <h3>Boston Consulting Group | Senior Product Manager <span style="float: right;">Apr 2022 - Mar 2024</span><br> Healthcare 🏥 / Energy ⚡</h3>

  <div class="grid-container">
    <div class="grid-item">
      <a href="#img5"><img src="images/BCG-product-image-1.png"></a>
      <a href="#img6"><img src="images/BCG-product-image-2.png"></a>
      <a href="#img7"><img src="images/BCG-product-image-3.png"></a>
      <a href="#img8"><img src="images/BCG-product-image-4.png"></a>
    </div>
    <div class="grid-item">
      <ul>
        <li>Executed digital transformation for an energy client, boosting efficiency by 50% with self-serve portal launch.</li>
        <li>Managed 2 backend teams on a healthcare digital transformation product, achieving 30% customer satisfaction improvement & 40% cost reduction in six months.</li>
        <li>Unified multiple patient portals into FHIR data store, establishing product requirements & coordinating timelines across six technical platform teams.</li>
      </ul>
    </div>
  </div>

  <div id="img5" class="lightbox">
    <a href="#" class="close">&times;</a>
    <img src="images/BCG-product-image-1.png">
  </div>

  <div id="img6" class="lightbox">
    <a href="#" class="close">&times;</a>
    <img src="images/BCG-product-image-2.png">
  </div>

  <div id="img7" class="lightbox">
    <a href="#" class="close">&times;</a>
    <img src="images/BCG-product-image-3.png">
  </div>

  <div id="img8" class="lightbox">
    <a href="#" class="close">&times;</a>
    <img src="images/BCG-product-image-4.png">
  </div>

  <br><br>

  <h3>Fetch Rewards | Senior Product Lead <span style="float: right;">Apr 2021 - Apr 2022</span><br> Consumer 🛍️ / Retail 🛒 / Mobile 📱</h3>

  <div class="grid-container">
    <div class="grid-item">
      <ul>
        <li>Led the development & successful launch of Social & Play features on the mobile app, driving 18 million MAU & achieving a top 15 ranking in the App Store.</li>
        <li>Increased user engagement by over 10% by designing & implementing a new social feature for connecting with friends & learning how to optimize product usage.</li>
        <li>Developed new game mechanics such as daily prizes & achievements & a competitive leaderboard improving daily user retention by 25%.</li>
      </ul>
    </div>
    <div class="grid-item">
      <a href="#img9"><img src="images/Fetch-Rewards-product-image-1.png"></a>
      <a href="#img10"><img src="images/Fetch-Rewards-product-image-2.png"></a>
      <a href="#img11"><img src="images/Fetch-Rewards-product-image-3.png"></a>
      <a href="#img12"><img src="images/Fetch-Rewards-product-image-4.png"></a>
    </div>
  </div>

  <div id="img9" class="lightbox">
    <a href="#" class="close">&times;</a>
    <img src="images/Fetch-Rewards-product-image-1.png">
  </div>

  <div id="img10" class="lightbox">
    <a href="#" class="close">&times;</a>
    <img src="images/Fetch-Rewards-product-image-2.png">
  </div>

  <div id="img11" class="lightbox">
    <a href="#" class="close">&times;</a>
    <img src="images/Fetch-Rewards-product-image-3.png">
  </div>

  <div id="img12" class="lightbox">
    <a href="#" class="close">&times;</a>
    <img src="images/Fetch-Rewards-product-image-4.png">
  </div>

  <br><br>

  <h3>Level Ex | Senior Product Manager <span style="float: right;">Apr 2020 - Apr 2021</span><br> Healthcare 🏥 / Gaming 🎮</h3>

  <div class="grid-container">
    <div class="grid-item">
      <a href="#img13"><img src="images/Level-Ex-product-image-1.png"></a>
      <a href="#img14"><img src="images/Level-Ex-product-image-2.png"></a>
      <a href="#img15"><img src="images/Level-Ex-product-image-3.png"></a>
      <a href="#img16"><img src="images/Level-Ex-product-image-4.png"></a>
    </div>
    <div class="grid-item">
      <ul>
        <li>Initiated agile product development as the inaugural full-time product manager, expediting the discovery-to-development cycle by 300%.</li>
        <li>Led the introduction & release of Level Ex's cloud gaming product to reignite sales revenue after a two-year break.</li>
        <li>Provided hands-on guidance & strategic project involvement to mentor & advance two healthcare analysts to Associate Product Manager positions.</li>
      </ul>
    </div>
  </div>

  <div id="img13" class="lightbox">
    <a href="#" class="close">&times;</a>
    <img src="images/Level-Ex-product-image-1.png">
  </div>

  <div id="img14" class="lightbox">
    <a href="#" class="close">&times;</a>
    <img src="images/Level-Ex-product-image-2.png">
  </div>

  <div id="img15" class="lightbox">
    <a href="#" class="close">&times;</a>
    <img src="images/Level-Ex-product-image-3.png">
  </div>

  <div id="img16" class="lightbox">
    <a href="#" class="close">&times;</a>
    <img src="images/Level-Ex-product-image-4.png">
  </div>

  <br><br>

  <h3>CoolerX | Senior Product Owner <span style="float: right;">Jan 2019 - Mar 2020</span><br> Retail 🛒 / IOT 🌐</h3>

  <div class="grid-container">
    <div class="grid-item">
      <ul>
        <li>Successfully initiated & managed a 1-year pilot program for 75 retail stores, resulting in the expansion of contracts to 2,500 stores with Walgreens & two other retailers ahead of schedule by two months.</li>
        <li>Led the redesign of the flagship product & IoT web app, leading to a substantial revenue boost & generating 38.1 million impressions in December 2019.</li>
        <li>Introduced agile product development processes as the initial full-time product hire, improving team efficiency & productivity significantly.</li>
      </ul>
    </div>
    <div class="grid-item">
      <a href="#img17"><img src="images/CoolerX-product-image-1.png"></a>
      <a href="#img18"><img src="images/CoolerX-product-image-2.png"></a>
      <a href="#img19"><img src="images/CoolerX-product-image-3.png"></a>
      <a href="#img20"><img src="images/CoolerX-product-image-4.png"></a>
    </div>
  </div>

  <div id="img17" class="lightbox">
    <a href="#" class="close">&times;</a>
    <img src="images/CoolerX-product-image-1.png">
  </div>

  <div id="img18" class="lightbox">
    <a href="#" class="close">&times;</a>
    <img src="images/CoolerX-product-image-2.png">
  </div>

  <div id="img19" class="lightbox">
    <a href="#" class="close">&times;</a>
    <img src="images/CoolerX-product-image-3.png">
  </div>

  <div id="img20" class="lightbox">
    <a href="#" class="close">&times;</a>
    <img src="images/CoolerX-product-image-4.png">
  </div>

  <br><br>

  <h3>Outcome Health | Technical Product Manager <span style="float: right;">Apr 2013 - Oct 2017</span><br> Healthcare 🏥 / Touchscreens 📱</h3>

  <div class="grid-container">
    <div class="grid-item">
      <a href="#img21"><img src="images/Outcome-Health-product-image-1.png"></a>
      <a href="#img22"><img src="images/Outcome-Health-product-image-2.png"></a>
      <a href="#img23"><img src="images/Outcome-Health-product-image-3.png"></a>
      <a href="#img24"><img src="images/Outcome-Health-product-image-4.png"></a>
    </div>
    <div class="grid-item">
      <ul>
        <li>Led strategy & delivery for two touchscreen products, achieving 100% growth in user retention, revenue, and business expansion annually, with two products accounting for 60% of total company revenue.</li>
        <li>Facilitated seamless transition from offshore to in-house development teams, resulting in improved product quality & team synergy.</li>
      </ul>
    </div>
  </div>

  <div id="img21" class="lightbox">
    <a href="#" class="close">&times;</a>
    <img src="images/Outcome-Health-product-image-1.png">
  </div>

  <div id="img22" class="lightbox">
    <a href="#" class="close">&times;</a>
    <img src="images/Outcome-Health-product-image-2.png">
  </div>

  <div id="img23" class="lightbox">
    <a href="#" class="close">&times;</a>
    <img src="images/Outcome-Health-product-image-3.png">
  </div>

  <div id="img24" class="lightbox">
    <a href="#" class="close">&times;</a>
    <img src="images/Outcome-Health-product-image-4.png">
  </div>

</body>
