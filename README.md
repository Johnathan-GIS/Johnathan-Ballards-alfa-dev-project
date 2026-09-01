# Johnathan-Ballards-alfa-dev-project
In this project it is my first project it is a basic project but I am expanding and adding new code to the code provided 
all about Garfield
index.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Garflix - Home</title>
  <link rel="stylesheet" href="assets/css/style.css">
</head>
<body bgcolor="orange">

  <center>
    <h1>Garflix</h1>
    <p>The #1 streaming site for one lazy orange cat.</p>
  </center>

  <hr>

  <!-- LAYOUT TABLE: puts the 3 sections side-by-side, 90's style -->
  <table border="0" cellpadding="10" cellspacing="0" align="center" width="100%">
    <tr valign="top">

      <!-- SECTION 1: HTML table with info + link -->
      <td align="center">
        <table border="1" cellpadding="5" cellspacing="0" align="center">
          <tr>
            <th colspan="2">Garfield Facts</th>
          </tr>
          <tr>
            <td>Species</td>
            <td>Cat</td>
          </tr>
          <tr>
            <td>Owner</td>
            <td>Jon Arbuckle</td>
          </tr>
          <tr>
            <td>Favorite Food</td>
            <td>Lasagna</td>
          </tr>
          <tr>
            <td>Hates</td>
            <td>Mondays</td>
          </tr>
          <tr>
            <td colspan="2" align="center">
              <a href="https://en.wikipedia.org/wiki/Garfield" target="_blank">Read more on Wikipedia</a>
            </td>
          </tr>
        </table>
      </td>

      <!-- SECTION 2: image, relative path -->
      <td align="center">
        <h2>Garfield (relative path image)</h2>
        <img src="assets/img/garfield.jpg" alt="Garfield" width="300">
      </td>

      <!-- SECTION 3: image, absolute path -->
      <td align="center">
        <h2>Garfield (absolute path image)</h2>
        <img src="/assets/img/garfield-2.jpg" alt="Garfield again" width="300">
      </td>

    </tr>
  </table>

  <hr>

  <footer>
    <center>
      <p>
        <a href="https://github.com/your-username" target="_blank">My GitHub Profile</a>
        |
        <a href="https://github.com/your-username/your-repo" target="_blank">Source Code</a>
      </p>
    </center>
  </footer>
<script src="assets/js/script.js"></script>
</body>
</html>

style.css (not plural)

body {
  background-color: orange;
  font-family: Comic Sans MS, cursive, sans-serif;
}

h1 {
  font-size: 48px;
}

table {
  background-color: white;
}

// old school reminder that JS is hooked up
alert('Garflix is live!'); 

var characters = [
  'Garfield',
  'Odie',
  'Jon',
  'Nermal',
  'Arlene'
];

// picks a random character line from the array and logs it
function greetRandomCharacter() {
  var pick = characters[Math.floor(Math.random() * characters.length)];
  console.log('Your daily Garfield character is ' + pick);
  return pick;
}

// defensive: only run once the DOM is actually ready
document.addEventListener('DOMContentLoaded', function () {
  console.log('Garflix loaded! Try calling greetRandomCharacter() in the console.');
  greetRandomCharacter();
});
  <script src="assets/js/script.js"></script>
</body>
</html>
