# learn-about-monuments
there are countless monuments around world 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
</head>
<body>

</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Monuments Around the World</title>
  <style>
    /* General Styling */
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #d3d3d3; /* Formal grey background */
      color: #333;
    }
    header {
      background-color: #444;
      color: white;
      text-align: center;
      padding: 20px;
    }
    .section-title {
      width: 100%;
      text-align: center;
      margin-top: 20px;
      padding: 10px;
      background-color: #666;
      color: #fff;
      font-size: 1.2em;
    }
    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      max-width: 100%;
      max-height: calc(100vh - 160px); /* Adjust height dynamically */
      overflow-y: auto; /* Enable scrolling */
      padding: 20px;
      box-sizing: border-box;
    }
    .monument {
      background-color: #fff;
      border-radius: 10px;
      box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
      width: 250px;
      text-align: center;
    }
    .monument img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-bottom: 3px solid #444;
    }
    .monument h3 {
      font-size: 18px;
      margin: 10px 0;
    }
    .monument p {
      font-size: 14px;
      padding: 0 10px 20px;
    }
    footer {
      background-color: #444;
      color: white;
      text-align: center;
      padding: 10px;
    }
    .container::-webkit-scrollbar {
      width: 10px;
    }
    .container::-webkit-scrollbar-thumb {
      background-color: #888;
      border-radius: 5px;
    }
    .container::-webkit-scrollbar-thumb:hover {
      background-color: #555;
    }
    @media (max-width: 768px) {
      .monument {
        width: 90%;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Monuments Around the World</h1>
    <p>Discover famous, lesser-known, and locally loved monuments</p>
  </header>

  <!-- General Monuments Section -->
  <div class="section-title">General Monuments</div>
  <div class="container">
    <!-- 1. Qutub Minar -->
    <div class="monument">
      <img src="https://upload.wikimedia.org/wikipedia/commons/4/4f/Qutub_Minar-Dusk.jpg" alt="Qutub Minar">
      <h3>Qutub Minar</h3>
      <p>India: A 73-meter tall minaret built in the 12th century, famous for its intricate carvings and red sandstone structure.</p>
    </div>
    <!-- 2. Eiffel Tower -->
    <div class="monument">
      <img src="https://upload.wikimedia.org/wikipedia/commons/3/3c/Tour_Eiffel_Wikimedia_Commons.jpg" alt="Eiffel Tower">
      <h3>Eiffel Tower</h3>
      <p>France: One of the world’s most recognizable landmarks, built for the 1889 World’s Fair in Paris.</p>
    </div>
    <!-- 3. Christ the Redeemer -->
    <div class="monument">
      <img src="https://upload.wikimedia.org/wikipedia/commons/1/10/Christ_the_Redeemer.jpg" alt="Christ the Redeemer">
      <h3>Christ the Redeemer</h3>
      <p>Brazil: The iconic statue of Jesus Christ overlooking Rio de Janeiro, symbolizing peace and openness.</p>
    </div>
    <!-- 4. Neuschwanstein Castle -->
    <div class="monument">
      <img src="https://upload.wikimedia.org/wikipedia/commons/a/a9/Neuschwanstein_Castle.jpg" alt="Neuschwanstein Castle">
      <h3>Neuschwanstein Castle</h3>
      <p>Germany: A fairy-tale castle nestled in the Bavarian Alps, and an inspiration for Disney.</p>
    </div>
    <!-- 5. Statue of Liberty -->
    <div class="monument">
      <img src="https://upload.wikimedia.org/wikipedia/commons/a/a1/Statue_of_Liberty.jpg" alt="Statue of Liberty">
      <h3>Statue of Liberty</h3>
      <p>USA: A global symbol of freedom, gifted by France in 1886.</p>
    </div>
    <!-- 6. Colosseum -->
    <div class="monument">
      <img src="https://upload.wikimedia.org/wikipedia/commons/e/e7/Colosseum_in_Rome.jpg" alt="Colosseum">
      <h3>Colosseum</h3>
      <p>Italy: A massive Roman amphitheater that hosted gladiator fights and public spectacles.</p>
    </div>
    <!-- 7. Machu Picchu -->
    <div class="monument">
      <img src="https://upload.wikimedia.org/wikipedia/commons/e/eb/Machu_Picchu.jpg" alt="Machu Picchu">
      <h3>Machu Picchu</h3>
      <p>Peru: A breathtaking Incan citadel built high in the Andes Mountains.</p>
    </div>
    <!-- 8. Stonehenge -->
    <div class="monument">
      <img src="https://upload.wikimedia.org/wikipedia/commons/3/3c/Stonehenge.jpg" alt="Stonehenge">
      <h3>Stonehenge</h3>
      <p>England: A prehistoric stone monument shrouded in mystery, located in Wiltshire.</p>
    </div>
    <!-- 9. Petra -->
    <div class="monument">
      <img src="https://upload.wikimedia.org/wikipedia/commons/3/3d/Petra-Jordan.jpg" alt="Petra">
      <h3>Petra</h3>
      <p>Jordan: Known as the "Rose City," this ancient city features rock-carved buildings and tombs.</p>
    </div>
    <!-- 10. Golden Temple -->
    <div class="monument">
      <img src="https://upload.wikimedia.org/wikipedia/commons/c/cf/Golden_Temple.jpg" alt="Golden Temple">
      <h3>Golden Temple</h3>
      <p>India: A spiritual and architectural marvel located in Amritsar, Punjab.</p>
    </div>
    <!-- 11. Leaning Tower of Pisa -->
    <div class="monument">
      <img src="https://upload.wikimedia.org/wikipedia/commons/9/99/Leaning_Tower_of_Pisa_2013.jpg" alt="Leaning Tower of Pisa">
      <h3>Leaning Tower of Pisa</h3>
      <p>Italy: A unique bell tower known for its tilt and stunning architecture.</p>
    </div>
    <!-- 12. Mount Rushmore -->
    <div class="monument">
      <img src="https://upload.wikimedia.org/wikipedia/commons/5/55/Mount_Rushmore_detail.jpg" alt="Mount Rushmore">
      <h3>Mount Rushmore</h3>
      <p>USA: Features the carved faces of four U.S. presidents in South Dakota.</p>
    </div>
    <!-- 13. Sydney Opera House -->
    <div class="monument">
      <img src="https://upload.wikimedia.org/wikipedia/commons/d/d2/Sydney_Opera_House_-_Dec_2008.jpg" alt="Sydney Opera House">
      <h3>Sydney Opera House</h3>
      <p>Australia: An architectural wonder on Sydney Harbour, featuring a unique shell design.</p>
    </div>
    <!-- 14. Kiyomizu-dera Temple -->
    <div class="monument">
      <img src="https://upload.wikimedia.org/wikipedia/commons/2/2a/Kiyomizu-dera_in_Kyoto.jpg" alt="Kiyomizu-dera Temple">
      <h3>Kiyomizu-dera Temple</h3>
      <p>Japan: A wooden Buddhist temple in Kyoto, renowned for its stunning views and history.</p>
    </div>
    <!-- 15. Angkor Wat -->
    <div class="monument">
      <img src="https://upload.wikimedia.org/wikipedia/commons/3/32/Angkor_Wat_from_the_west_side.jpg" alt="Angkor Wat">
      <h3>Angkor Wat</h3>
      <p>Cambodia: The largest religious structure in the world, originally built as a Hindu temple.</p>
    </div>
    <!-- 16. Forbidden City -->
    <div class="monument">
      <img src="https://upload.wikimedia.org/wikipedia/commons/6/68/Forbidden_city_beijing_summer.jpg" alt="Forbidden City">
      <h3>Forbidden City</h3>
      <p>China: A vast imperial palace complex in Beijing, symbolizing China's rich cultural history.</p>
    </div>
    <!-- 17. Lalibela Churches -->
    <div class="monument">
      <img src="https://upload.wikimedia.org/wikipedia/commons/3/36/Lalibela_Churches.jpg" alt="Lalibela Churches">
      <h3>Lalibela Churches</h3>
      <p>Ethiopia: A group of 11 rock-hewn churches carved into the ground, an engineering marvel.</p>
    </div>
    <!-- 18. Mount Kilimanjaro -->
    <div class="monument">
      <img src="https://upload.wikimedia.org/wikipedia/commons/6/65/Mount_Kilimanjaro_from_the_air.jpg" alt="Mount Kilimanjaro">
      <h3>Mount Kilimanjaro</h3>
      <p>Tanzania: Africa’s tallest mountain, often visited by adventurers and climbers.</p>
    </div>
    <!-- 19. Chichen Itza -->
    <div class="monument">
      <img src="https://upload.wikimedia.org/wikipedia/commons/f/f6/Chichen_Itza_Pyramid.jpg" alt="Chichen Itza">
      <h3>Chichen Itza</h3>
      <p>Mexico: A massive Mayan city featuring the pyramid-like Temple of Kukulcan.</p>
    </div>
    <!-- 20. Kremlin -->
    <div class="monument">
      <img src="https://upload.wikimedia.org/wikipedia/commons/2/20/Moscow-Kremlin-Red_Square-and-Novodevichy-Cemetery.jpg" alt="Kremlin">
      <h3>Kremlin</h3>
      <p>Russia: A fortified complex in Moscow that includes palaces and cathedrals.</p>
    </div>
  </div>

  <!-- Special Monuments Section -->
  <div class="section-title">Special Monuments</div>
  <div class="container">
    <!-- 1. Darvaza Gas Crater -->
    <div class="monument">
      <img src="https://upload.wikimedia.org/wikipedia/commons/a/a7/Darvaza_Crater.jpg" alt="Darvaza Gas Crater">
      <h3>Darvaza Gas Crater</h3>
      <p>Turkmenistan: Nicknamed the "Gate to Hell," this flaming natural gas crater has been burning since the 1970s.</p>
    </div>
    <!-- 2. Las Lajas Sanctuary -->
    <div class="monument">
      <img src="https://upload.wikimedia.org/wikipedia/commons/7/74/Las_Lajas_Sanctuary.jpg" alt="Las Lajas Sanctuary">
      <h3>Las Lajas Sanctuary</h3>
      <p>Colombia: A gothic-style church built inside a canyon, featuring miraculous legends.</p>
    </div>
    <!-- 3. Banaue Rice Terraces -->
    <div class="monument">
      <img src="https://upload.wikimedia.org/wikipedia/commons/e/ea/Banaue_Rice_Terraces.jpg" alt="Banaue Rice Terraces">
      <h3>Banaue Rice Terraces</h3>
      <p>Philippines: Often referred to as the "Eighth Wonder of the World," these terraced fields are over 2,000 years old.</p>
    </div>
    <!-- 4. Tirta Empul Temple -->
    <div class="monument">
      <img src="https://upload.wikimedia.org/wikipedia/commons/a/ae/Tirta_Empul_Temple.jpg" alt="Tirta Empul Temple">
      <h3>Tirta Empul Temple</h3>
      <p>Bali, Indonesia: Known for its sacred water spring and purification rituals.</p>
    </div>
    <!-- 5. Skellig Michael -->
    <div class="monument">
      <img src="https://upload.wikimedia.org/wikipedia/commons/c/cf/Skellig_Michael.jpg" alt="Skellig Michael">
      <h3>Skellig Michael</h3>
      <p>Ireland: A remote island featuring ancient monastic ruins, accessible via challenging climbs.</p>
    </div>
    <!-- 6. Elmina Castle -->
    <div class="monument">
      <img src="https://upload.wikimedia.org/wikipedia/commons/e/e9/Elmina_Castle.jpg" alt="Elmina Castle">
      <h3>Elmina Castle</h3>
      <p>Ghana: A historical fort that played a major role in the transatlantic slave trade.</p>
    </div>
    <!-- 7. Stari Most -->
    <div class="monument">
      <img src="https://upload.wikimedia.org/wikipedia/commons/4/4e/Stari_Most.jpg" alt="Stari Most">
      <h3>Stari Most</h3>
      <p>Bosnia and Herzegovina: A historic Ottoman bridge, symbolizing cultural diversity.</p>
    </div>
    <!-- 8. Pumapunku -->
    <div class="monument">
      <img src="https://upload.wikimedia.org/wikipedia/commons/d/d6/Pumapunku.jpg" alt="Pumapunku">
      <h3>Pumapunku</h3>
      <p>Bolivia: Ancient stone ruins showcasing advanced engineering techniques.</p>
    </div>
    <!-- 9. Chand Baori -->
    <div class="monument">
      <img src="https://upload.wikimedia.org/wikipedia/commons/7/7b/Chand_Baori.jpg" alt="Chand Baori">
      <h3>Chand Baori</h3>
      <p>India: One of the deepest stepwells, featuring over 3,500 symmetrical steps.</p>
    </div>
    <!-- 10. Hallstatt Salt Mines -->
    <div class="monument">
      <img src="https://upload.wikimedia.org/wikipedia/commons/7/72/Hallstatt_Salt_Mines.jpg" alt="Hallstatt Salt Mines">
      <h3>Hallstatt Salt Mines</h3>
      <p>Austria: The oldest salt mines in the world, offering underground tours.</p>
    </div>
  </div>

  <footer>
    <p>© 2025 Monuments Around the World. All rights reserved.</p>
  </footer>
</body>
</html>


