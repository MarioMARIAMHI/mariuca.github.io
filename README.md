# mariuca.github.io
<!DOCTYPE html>
<html lang="ro">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Programul printesicii Mariuca</title>
  <link rel="stylesheet" href="sitewow.css">
  <style>
        @import url('https://fonts.googleapis.com/css2?family=Walt+Disney+Script&display=swap');
        body {
            font-family: 'Walt Disney Script', sans-serif;
        }
        table {
            margin-top: 50px;
        }
        #textContainer {
            margin-top: 50px;
        }
        #imagineContainer {
            display: none;
            margin-top: 20px;
        }
        #orarMeditatii {
            font-size: 18px;
            font-weight: bold;
            margin-top: 20px;
            color: #333;
        }
    </style>
  <script>
        function afiseazaImagine() {
            var container = document.getElementById("imagineContainer");
            container.innerHTML = '<a href="https://drive.google.com/file/d/13edSwOqcl1pjbwpDIs9lMTu3JE9GnZ37/view?usp=sharing" target="_blank"><img src="https://drive.google.com/uc?id=13edSwOqcl1pjbwpDIs9lMTu3JE9GnZ37" alt="Imagine Fericire"></a>';
            container.style.display = "block";
        }
    </script>
</head>
<body>

<header>Programul printesicii Mariuca</header>
<h2>Orar meditatii</h2>
<table>
  <tr>
    <th>Ziua</th>
    <th>Materia</th>
    <th>Ora</th>
  </tr>
  <tr>
    <td>Luni</td>
    <td>Biologie</td>
    <td>15:30</td>
  </tr>
  <tr>
    <td>Marti</td>
    <td>Chimie</td>
    <td>15:30</td>
  </tr>
  <tr>
    <td>Miercuri</td>
    <td>Istorie</td>
    <td>17:00</td>
  </tr>
  <tr>
    <td>Joi</td>
    <td>Biologie</td>
    <td>16:00</td>
  </tr>
  <tr>
    <td>Vineri</td>
    <td>Chimie</td>
    <td>18:00</td>
  </tr>
</table>


<div id="textContainer">
  <p>Dacă te simți tristă și obosită, <br> Apasă pe acest buton să fii fericită.</p>
  <button onclick="afiseazaImagine()">Fă-mă fericită!</button>

</div>

<div id="imagineContainer"></div>

</body>
</html>

