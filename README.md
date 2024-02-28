<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title></title>
  <style>
    body {
      display: flex;
      background-color: #1f1f1f; /* Hintergrundfarbe für Dark Mode */
      color: #ffffff; /* Textfarbe für Dark Mode */
    }
    #frame-container {
      display: flex;
      flex-direction: column;
    }
    #frame-container iframe {
      border: 0px solid #ccc;
      background-color: #1f1f1f; /* Hintergrundfarbe für Dark Mode in den Iframes */
      margin-bottom: 10px;
    }
    #third-frame {
      margin-left: 10px;
    }
  </style>
</head>
<body>

<h1 style="color: #ffffff;"></h1>

<div id="frame-container">
  <iframe src="https://data.koeln-wetter.app/php2/Pegelvorhersage.png" width="1300" height="370" frameborder="0"scrolling="no"></iframe>
  <iframe src="https://www.pegelonline.wsv.de/charts/OnlineVisualisierungGanglinie?pegeluuid=a6ee8177-107b-47dd-bcfd-30960ccc6e9c&parameter=WASSERTEMPERATUR%20ROHDATEN&dauer=350&imgLinien=2&imgBreite=1100&imgHoehe=250&pegelkennwerte=NNW,HHW,MNW,MW,MHW,GLW,HSW,NSW,RNW,ZS_I,ZS_II,M_I,M_II,M_III,TuGLW,NW,HSW2,GOK_NN,MP_NN&schriftPegelname=11&schriftAchse=11&anzeigeUeberschrift=false&anzeigeDatenquelle=false&schriftLetzterWert=15&textUnten=&gesetzlicheZeit=true&anzeigeUnterschrift=false" width="1200" height="300" frameborder="0"scrolling="no"></iframe>
  <iframe src="https://data.koeln-wetter.app/PegelKoeln_Aktuell_PWA.php" width="1300" height="370" frameborder="0"scrolling="no"></iframe>
  
</div>

<iframe id="third-frame" src="https://data.koeln-wetter.app/VorhersageS_10d.php" width="600" height="1500" frameborder="0"></iframe>

</body>
</html>

