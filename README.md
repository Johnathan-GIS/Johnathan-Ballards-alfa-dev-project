# Johnathan-Ballards-alfa-dev-project
In this project it is my first project it is a basic project but I am expanding and adding new code to the code provided 
I added a table, python code selection and a image
all about Garfield
index.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Garfeild - Home</title>
  <link rel="stylesheet" href="assets/css/style.css">
</head>
<body bgcolor="Orange">

  <center>
    <h1>Garfield</h1>
    <p>The #1 streaming site for one lazy orange cat.</p>
    <p> Garfield has two big movies and two big TV series and several other smaller movies and series. 
    Garfield was first created in 1978.</p>
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
 
  <table>
    <!--Garfield Show Top 10 Characters-->
   <tr>
    <th>Name</th>
    <th>CreatureType</th>
    <th>Importance</th>
    </tr>
    <tr>
    <th>Garfield</th>
    <th>Cat</th>
      <th>1</th>
    </tr>
    <tr>
    <th>Odie</th>
      <th>dog</th>
      <th>2</th>
      <tr>
        <th>Jon Arbuckle</th>
        <th>Human</th>
        <th>3</th>
      </tr>
    <tr>
<th>Nermal</th>
      <th>cat</th>
      <th>4</th>
    </tr>
    <tr>
      <th>Arlene</th>
      <th>cat</th>
      <th>5</th>
    </tr>
    <tr>
      <th>Dr.Liz</th>
      <th>human</th>
      <th>6</th>
    </tr>  
    <tr>
      <th>Drusilla</th>
      <th>human</th>
      <th>7</th>
    </tr>
    <tr>
      <th>Minerva</th>
      <th>human</th>
      <th>8</th>
    </tr>
    <tr>
      <th>Squeak</th>
      <th>Mouse</th>
      <th>9</th>
    </tr>
    <tr>
      <th>Aunt Ivy</th>
      <th>human</th>
      <th>10</th>
    </tr>
  </table> 

<img src"https://www.bing.com/images/search?view=detailV2&ccid=ah4dDM32&id=C10DD096C0A70E84E38CB54056566192D169D457&thid=OIP.ah4dDM32m7ZZ776OyDoFFAHaEK&mediaurl=https%3A%2F%2Fi.ytimg.com%2Fvi%2FA5nQiMY7Hgg%2Fmaxresdefault.jpg&cdnurl=https%3A%2F%2Fth.bing.com%2Fth%2Fid%2FR.6a1e1d0ccdf69bb659efbe8ec83a0514%3Frik%3DV9Rp0ZJhVlZAtQ%26pid%3DImgRaw%26r%3D0&exph=720&expw=1280&q=garfield+and+friends+&FORM=IRPRST&ck=A11B33833067AF5AB7512B4A7C40779F&selectedIndex=16&itb=0&cw=1721&ch=853&mode=overlay">




  <hr>

  <footer>
    <center>
      <p>
       <a href="https://github.com/Johnathan-GIS" target="_blank">My GitHub Profile</a> 
        |
        <a href="https://github.com/your-username" target="_blank">My GitHub Profile</a>
        |
        <a href="https://github.com/Johnathan-GIS/Johnathan-Ballards-alfa-dev-project/edit/main/README.md"> target="_blank">Ballard's Code</a>
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
  background-color: yellow;
  font-family: Comic Sans MS, cursive, sans-serif;
}

h1 {
  font-size: 48px;
}

table {
  background-color: grey;
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

// Additional Garfield Characters
alert('Other Garfield Characters!');
var characters = [
'Dr.Liz',
'Minerva',
'Squeak',
'Aunt Ivy',
'Dr. Wipple',
]
 

// picks a random character line from the array and logs it
<Garflix is live/>
function greetRandomCharacter() {
  var pick = characters[Math.floor(Math.random() * characters.length)];
  console.log('Your daily Garfield character is ' + pick);
  return pick;
}
// list of items
Primary list = ['Garfield', 'Odie', 'Jon', 'Nermal', 'Arlene']
selected_item_1 = random.choice(Primary_list)
Secondary list = ['Dr. Liz', 'Minerva', 'Squeak', 'Aunt Ivy', 'Dr. Wipple]
// random selection
selected_item_2 = random.choice(Secondary_list)
print(selected_item_1 and selected_item_2)

// defensive: only run once the DOM is actually ready
document.addEventListener('DOMContentLoaded', function () {
  console.log('Garflix loaded! Try calling greetRandomCharacter() in the console.');
  greetRandomCharacter();
});

document.addEventListener('DOMContentLoaded', function () {
  console.log('Other Garfeild Characters! Try calling greetRandomCharacter() in the console.');
  greetRandomCharacter();
  
