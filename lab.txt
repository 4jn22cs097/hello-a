Lab program 1

Develop the HTML page named as "Myfirstwebpage.html".
Add the following tags with relevant content.
1. Set the title of the page as "My First Web Page"
2. Within the body use the following tags:
a) Moving text = Basic HTML Tags
b) Different heading tags (h1 to h6)
c) Paragraph
d) Horizontal line
e) Line Break
f) Block Quote
g) Pre tag
h) Different Logical Style (b, u, sub, sup etc.)


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My First Web Page</title>
</head>
<body>
<marquee>Basic HTML tags</marquee>
<hr>
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
<p>Visvesvaraya is regarded in India as one of the foremost civil
engineers whose birthday
is celebrated every year as <br>Engineer's Day in <u>India, Sri Lanka, and Tanzania</u>.
He is also often regarded as <b>the maker of modern Mysore</b>.There is a
quote that says</p>
<blockquote>
Strive for perfection in everything you do. Take the best that exists and make it better. When it
does not exist, design it.
</blockquote>
<p> This was quoted by <i>Sir Henry Royce </i></p>
<pre>Visvesvaraya is regarded in India as one of the foremost civil
engineers whose birthday
is celebrated every year as <br>Engineer's Day in India, Sri Lanka, and Tanzania.
He is also often regarded as <b>the maker of modern Mysore</b>.There is a quote
that says</pre>
<p>This is <sub>subscript</sub> and <sup>superscript</sup></p>
</body> </html>

------------------------------------------------------------------------------------------------------

Lab program 2

Develop the HTMl page named as "Table.html" to display your class time table.
a) Provide the title as Time Table with table header and table footer, rowspan and column span etc.
b) Provide various color options to the cells(Highlight the lab hours
and elective hours with different colors.)
c) provide color options for rows


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Time Table</title>
<style>
body {
font-family: Calibri;
}
table {
width: 100%;
border-collapse: collapse;
}
th, td {
border: 1px solid black;
padding: 8px;
text-align: center;
}
th {
background-color: lightgrey;
}
.lab-hours {
background-color: pink;
}
.elective-hours {
background-color: lightgreen;
}
.lunch {
background-color: yellow;
}
.odd-row {
background-color: lightblue;
}
</style>
</head>
<body>
<table>
<thead>
<tr>
<th colspan="12">Time Table</th>
</tr>
<tr>
<th>Class</th>
<th>Time/Days</th>
<th>8.25-9.20</th>
<th>9.20-10.15</th>
<th>10.15-10.45</th>
<th>10.45-11.40</th>
<th>11.40-12.35</th>
<th>12.35-1.30</th>
<th>1.30-2.30</th>
<th>2.30-3.25</th>
<th>3.25-4.20</th>
<th>4.20-5.15</th>
</tr>
</thead>
<tbody>
<tr>
<th rowspan="9">5<sup>th</sup> Sem C Section</th>
<td>Monday</td>
<td class="lab-hours" colspan="2">WEB LAB-C1</td>
<td class="lunch">B</td>
<td class="lab-hours" colspan="2">WEB LAB-C2</td>
<td></td>
<td class="lunch">L</td>
<td>CN</td>
<td>TOC</td>
<td></td>
</tr>
<tr class="odd-row">
<td>Tuesday</td>
<td>CN</td>
<td>CN</td>
<td class="lunch">R</td>
<td class="elective-hours">AI</td>
<td>CN</td>
<td>SE</td>
<td class="lunch">U</td>
<td colspan="3">ENV</td>
</tr>
<tr>
<td>Wednesday</td>
<td>SE</td>
<td>TOC</td>
<td class="lunch">E</td>
<td>RM</td>
<td>CN</td>
<td>CN</td>
<td class="lunch">N</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="odd-row">
<td>Thursday</td>
<td></td>
<td></td>
<td class="lunch">A</td>
<td class="elective-hours">AI</td>
<td>RM</td>
<td>TOC</td>
<td class="lunch">C</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr>
<td>Friday</td>
<td class="lab-hours" colspan="2">WEB LAB-C3</td>
<td class="lunch">K</td>
<td>CN</td>
<td>RM</td>
<td>SE</td>
<td class="lunch">H</td>
<td class="elective-hours">AI</td>
<td>TOC</td>
<td>SE</td>
</tr>
<tr class="odd-row">
<td>Saturday</td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td colspan="4">-----------</td>
</tr>
</tbody>
<tfoot>
<tr>
<td colspan="12">* Lab hours are highlighted in pink, elective hours in light
green</td>
</tr>
</tfoot>
</table>
</body>
</html>

-----------------------------------------------------------------------------------------------

3.

HTML FILE

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sample Styled Page (No Div)</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<main id="main-content">
<h2>Welcome to Our Styled Page</h2>
<p>This is a paragraph right after an h2. It demonstrates the adjacent
sibling selector.</p>
<h3>Hover over me!</h3>
<hr>
<p lang="en">This paragraph has a lang attribute, demonstrating the
attribute selector.</p>
<div>
<p>Here's a <span class="highlight">highlighted</span> word using the
class selector.</p>
<p>This paragraph is inside div tag, showing the descendant
selector.</p>
</div>
<p>The current date and time: <time datetime="YYYY-MM-DD">14 October
2024, 10:30 IST</time></p>
<p>Notice how the first letter of each paragraph is styled differently.</p>
<img
src="https://jnnce.ac.in/jnndemo/img/jnnce.jpg" alt="A placeholder
image">
<p>Check out this <a href="https://jnnce.ac.in/jnndemo/">link</a></p>
</main>
</body>
</html>

CSS FILE

/* ID Selector */
#main-content {
max-width: 800px;
margin: 0 auto;
padding: 20px;
background-color: coral;
}
h2 {
color: green;
font-family: 'Arial';
border-bottom: 2px dashed purple;
padding-bottom: 10px;
}
/* Adjacent Sibling Selector */
h2 + p {
font-size: 1.1em; /*element metric, generic unit*/
color: blue;
}
/* Element Selector with Pseudo-class */
h3:hover {
color: green;
cursor:pointer;
}
/* Element Selector , 1 opaque*/
hr {
border: 0;
height: 3px;
background-image: linear-gradient(to left, rgba(255, 0, 0, 1), rgba(0, 255, 0,
0.75), rgba(0, 0, 255, 1));
}
/* Element Selector with Attribute */
p[lang] {
font-style: italic;
}
/* Class Selector */
.highlight {
background-color: yellow;
padding: 5px;
}
/* Descendant Selector */
div p{
color:red;
line-height: 1.6;
}
/* Attribute Selector */
time[datetime] {
color: green;
font-weight: bold;
}
/* Pseudo-element Selector */
p::first-letter {
font-size: 1.5em;
font-weight: bold;
color: blue;
}
/* Multiple Selectors */
img, a {
border: 2px solid blue;
padding: 5px;
max-width:100%;
}
/* Child Selector */
p > span {
font-weight: bold;
color: black;
}
/* Pseudo-class Selector for Links */
a:link, a:visited {
color: green;
}
a:hover {
color: red;
}

-------------------------------------------------------------------------------

4.

HTML FILE

<!DOCTYPE html> 
<html lang="en"> 
<head> 
 <meta charset="UTF-8"> 
 <meta name="viewport" content="width=device-width, 
initial-scale=1.0"> 
 <title>Registration Form</title> 
 <style> 
 body { 
 font-family: Arial, sans-serif; 
 background-color: #f0f0f0; 
 margin: 0; 
 padding: 20px; 
 } 
 h1 {
 color: #333; 
 text-align: center; 
 } 
 table { 
 width: 100%; 
 max-width: 600px; 
 margin: 0 auto; 
 background-color: #fff; 
 padding: 20px; 
 border-radius: 8px; 
 box-shadow: 0 0 10px rgba(0,0,0,0.1); 
 } 
 td { 
 padding: 10px; 
 } 
 label { 
 color: #555; 
 font-weight: bold; 
 } 
 input[type="text"], input[type="email"], 
input[type="password"], 
select, textarea { 
 width: 100%; 
 padding: 8px; 
 border: 1px solid #ddd; 
 border-radius: 4px; 
 box-sizing: border-box; 
 font-size: 16px; 
 } 
 input[type="radio"], input[type="checkbox"] { 
 margin-right: 5px; 
 } 
 input[type="submit"] { 
 background-color: #4CAF50; 
 color: white; 
 padding: 10px 20px; 
 border: none; 
 border-radius: 4px; 
 cursor: pointer;
font-size: 18px; 
} 
input[type="submit"]:hover { 
background-color: #45a049; 
} 
.error { 
color: #ff0000; 
font-size: 14px; 
} 
</style> 
</head> 
<body> 
<h1>Registration Form</h1> 
<table> 
<form action="#" method="post"> 
<tr> 
<td><label for="fullname">Full Name:</label></td> 
<td><input type="text" id="fullname" name="fullname" 
required></td>
 </tr> 
 <tr> 
 <td><label for="email">Email:</label></td> 
 <td><input type="email" id="email" name="email" 
required></td> 
 </tr> 
 <tr> 
 <td><label for="password">Password:</label></td> 
 <td><input type="password" id="password" 
name="password" 
required></td> 
 </tr> 
 <tr> 
 <td><label for="confirm_password">Confirm 
Password:</label></td> 
 <td><input type="password" id="confirm_password" 
name="confirm_password" required></td> 
 </tr> 
 <tr> 
 <td><label>Gender:</label></td> 
 <td>
<input type="radio" id="male" name="gender" value="male" 
required> 
 <label for="male">Male</label> 
 <input type="radio" id="female" name="gender" 
value="female" required> 
 <label for="female">Female</label> 
 <input type="radio" id="other" name="gender" 
value="other" 
required> 
 <label for="other">Other</label> 
 </td> 
 </tr> 
 <tr> 
 <td><label for="birthdate">Date of Birth:</label></td> 
 <td><input type="date" id="birthdate" 
name="birthdate" 
required></td> 
 </tr> 
 <tr> 
 <td><label for="country">Country:</label></td> 
 <td> 
 <select id="country" name="country" required> 
 <option value="">Select a country</option> 
 <option value="IN">India</option> 
 <option value="uk">United Kingdom</option> 
 <option value="canada">Canada</option> 
 <option value="australia">Australia</option> 
 <option value="other">Other</option> 
 </select> 
 </td> 
 </tr> 
 <tr> 
 <td><label for="interests">Interests:</label></td> 
 <td> 
 <input type="checkbox" id="sports" 
name="interests[]" 
value="sports"> 
 <label for="sports">Sports</label> 
 <input type="checkbox" id="music" 
name="interests[]" 
value="music"> 
 <label for="music">Music</label> 
 <input type="checkbox" id="reading" 
name="interests[]" 
value="reading"> 
 <label for="reading">Reading</label> 
 <input type="checkbox" id="travel" 
name="interests[]" 
value="travel"> 
 <label for="travel">Travel</label> 
 </td> 
 </tr> 
 <tr> 
 <td><label for="bio">Bio:</label></td> 
 <td><textarea id="bio" name="bio" 
rows="4"></textarea></td> 
 </tr> 
 <tr> 
 <td colspan="2" style="text-align: center;"> 
 <input type="submit" value="Submit"> 
 </td> 
 </tr> 
 </table> 
 </form> 
</body> 
</html>

--------------------------------------------------------------------------------

lab program 5

Develop HTML page named as newspaper.html” having variety of HTML semantic elements
with background colors, text-colors and size for figure,table,aside,section,article, header,footer
etc.,


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>The Daily Chronicle</title>
<style>
body {
font-family:Georgia;
line-height: 1.6;
color: #333;
max-width: 1200px;
margin: 0 auto;
padding: 20px;
background-color: #f4f4f4;
}
header {
background-color: #1a1a1a;
color: #fff;
padding: 20px;
text-align: center;
}
header h1 {
margin: 0;
font-size: 2.5em;
}
nav {
background-color: #333;
color: #fff;
padding: 10px;
}
nav ul {
list-style-type: none;
padding: 0;
margin: 0;
display: flex;
justify-content: center;
}
nav ul li {
margin: 0 10px;
}
nav ul li a {
color: #fff;
text-decoration: none;
}
main {
display: flex;
margin-top: 20px;
}
section {
flex: 2;
margin-right: 20px;
}
article {
background-color: #fff;
padding: 20px;
margin-bottom: 20px;
box-shadow: 0 0 10px rgba(0,0,0,0.1);
}
article h2 {
color: #1a1a1a;
font-size: 1.8em;
}
aside {
flex: 1;
background-color: #e6e6e6;
padding: 20px;
box-shadow: 0 0 10px rgba(0,0,0,0.1);
}
figure {
margin: 0;
text-align: center;
}
figure img {
max-width: 100%;
height: auto;
}
figcaption {
font-style: italic;
color: #666;
font-size: 0.9em;
}
table {
width: 100%;
border-collapse: collapse;
margin-bottom: 20px;
}
th, td {
border: 1px solid #ddd;
padding: 10px;
text-align: left;
}
th {
background-color: #f2f2f2;
}
footer {
background-color: #1a1a1a;
color: #fff;
text-align: center;
padding: 10px;
margin-top: 20px;
}
</style>
</head>
<body>
<header>
<h1>The Daily Chronicle</h1>
</header>
<nav>
<ul>
<li><a href="https://www.ndtvprofit.com/">Profit</a></li>
<li><a
href="https://www.ndtv.com/world#pfrom=home-gadgets_header-globalnav">World</a></li>
<li><a href="https://www.gadgets360.com/#pfrom=ndtv-globalnav">Technology</a></li>
<li><a href="https://sports.ndtv.com/#pfrom=ndtv-globalnav">Sports</a></li>
<li><a
href="https://www.ndtv.com/entertainment#pfrom=sports-header-globalnav">Entertainment</a>
</li>
</ul>
</nav>
<main>
<section>
<article>
<h2>Breaking News: Major Technological Breakthrough</h2>
<p>Scientists have announced a groundbreaking discovery in the field of quantum computing,
potentially revolutionizing the tech industry.</p>
<figure>
<img
src="https://www.cnet.com/a/img/resize/c7cb26e927bebaa784fb55a01e71d7fecb15d2e3/hub/20
19/06/26/3f76e99d-8055-46f3-8f27-558ee276b665/20180405-
ibm-q-quantum-computer-02.jpg?auto=webp&fit=crop&height=675&width=1200" alt="Quantum
Computer">
<figcaption>A state-of-the-art quantum computer at the research facility</figcaption>
</figure>
</article>
<article>
<h2>Local Sports Team Wins Championship</h2>
<p>In a thrilling match, our local team secured victory in the national championship, bringing
pride to our city.</p>
<table>
<tr>
<th>Team</th>
<th>Score</th>
</tr>
<tr>
<td>Local Heroes</td>
<td>3</td>
</tr>
<tr>
<td>Visiting Challengers</td>
<td>2</td>
</tr>
</table>
</article>
</section>
<aside>
<h3>Weather Update</h3>
<p>Expect sunny skies with a high of 75°F (24°C) today.</p>
<h3>Upcoming Events</h3>
<ul>
<li>City Festival - This Weekend</li>
<li>Tech Conference - Next Month</li>
<li>Charity Run - In Two Weeks</li>
</ul>
</aside>
</main>
<footer>
<p>&copy; 2024 The Daily Chronicle. All rights reserved.</p>
</footer>
</body>
</html>

-----------------------------------------------------------------------------------------------

Lab program 6

Apply HTML, CSS and Javascript to design a simple calculator to perform the following
operations sum, product, difference, remainder, quotient, power, square-root and square.


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Simple Calculator</title>
<style>
body {
font-family: Arial, sans-serif;
display: flex;
justify-content: center;
align-items: center;
height: 100vh;
margin: 0;
background-color: #f0f0f0;
}
.calculator {
background-color: #fff;
border-radius: 8px;
box-shadow: 0 0 10px rgba(0,0,0,0.1);
padding: 20px;
width: 300px;
}
#display {
width: 100%;
height: 40px;
font-size: 1.5em;
text-align: right;
margin-bottom: 10px;
padding: 5px;
box-sizing: border-box;
}
.buttons {
display: grid;
grid-template-columns: repeat(4, 1fr);
gap: 10px;
}
button {
padding: 10px;
font-size: 1.2em;
border: none;
background-color: #e0e0e0;
cursor: pointer;
border-radius: 4px;
}
button:hover {
background-color: #d0d0d0;
}
.operator {
background-color: #f0a030;
color: white;
}
.operator:hover {
background-color: #e09020;
}
</style>
</head>
<body>
<div class="calculator">
<input type="text" id="display">
<div class="buttons">
<button onclick="appendToDisplay('7')">7</button>
<button onclick="appendToDisplay('8')">8</button>
<button onclick="appendToDisplay('9')">9</button>
<button class="operator" onclick="setOperation('+')">+</button>
<button onclick="appendToDisplay('4')">4</button>
<button onclick="appendToDisplay('5')">5</button>
<button onclick="appendToDisplay('6')">6</button>
<button class="operator" onclick="setOperation('-')">-</button>
<button onclick="appendToDisplay('1')">1</button>
<button onclick="appendToDisplay('2')">2</button>
<button onclick="appendToDisplay('3')">3</button>
<button class="operator" onclick="setOperation('*')">*</button>
<button onclick="appendToDisplay('0')">0</button>
<button onclick="appendToDisplay('.')">.</button>
<button class="operator" onclick="calculate()">=</button>
<button class="operator" onclick="setOperation('/')">/</button>
<button class="operator" onclick="setOperation('%')">%</button>
<button class="operator" onclick="setOperation('^')">x<sup>y</sup></button>
<button class="operator" onclick="squareRoot()">√</button>
<button class="operator" onclick="square()">x<sup>2</sup></button>
<button onclick="clearDisplay()">C</button>
</div>
</div>
<script>
let display = document.getElementById('display');
let currentValue = '';
let operation = '';
let previousValue = '';
function appendToDisplay(value) {
currentValue += value;
display.value = currentValue;
}
function clearDisplay() {
currentValue = '';
operation = '';
previousValue = '';
display.value = '';
}
function setOperation(op) {
if (currentValue !== '') {
if (previousValue !== '') {
calculate();
}
operation = op;
previousValue = currentValue;
currentValue = '';
}
}
function calculate() {
if (previousValue !== '' && currentValue !== '') {
let result;
const prev = parseFloat(previousValue);
const current = parseFloat(currentValue);
switch(operation) {
case '+':
result = prev + current;
break;
case '-':
result = prev - current;
break;
case '*':
result = prev * current;
break;
case '/':
result = prev / current;
break;
case '%':
result = prev % current;
break;
case '^':
result = Math.pow(prev, current);
break;
}
display.value = result;
}
}
function squareRoot() {
if (currentValue !== '') {
const result = Math.sqrt(parseFloat(currentValue));
display.value = result;
}
}
function square() {
if (currentValue !== '') {
const result = Math.pow(parseFloat(currentValue), 2);
display.value = result;
}
}
</script>
</body>
</html>

--------------------------------------------------------------------------

Lab program 7

Develop Javascript program (with HTML/CSS) for:
a) Converting JSON text to javascript object
b) Convert JSON results into a date
c) Converting from JSON to CSV and CSV to JSON
d) Create hash from string using crypto.createHash() method


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>JSON/CSV Converter and Hash Generator</title>
<style>
body {
font-family: Arial, sans-serif;
line-height: 1.6;
margin: 0;
padding: 20px;
background-color: #f4f4f4;
}
.container {
max-width: 800px;
margin: auto;
background: white;
padding: 20px;
border-radius: 5px;
box-shadow: 0 0 10px rgba(0,0,0,0.1);
}
h1 {
color: #333;
}
textarea {
width: 100%;
height: 100px;
margin-bottom: 10px;
}
button {
background-color: #4CAF50;
color: white;
padding: 10px 15px;
border: none;
border-radius: 4px;
cursor: pointer;
margin-right: 10px;
}
button:hover {
background-color: #45a049;
}
#result {
margin-top: 20px;
padding: 10px;
background-color: #e7e7e7;
border-radius: 4px;
}
</style>
</head>
<body>
<div class="container">
<h1>JSON/CSV Converter and Hash Generator</h1>
<h2>a) Convert JSON to JavaScript Object</h2>
<textarea id="jsonInput" placeholder="Enter data in JSON format"></textarea>
<button onclick="convertJsonToObject()">Convert to JS Object</button>
<h2>b) Convert JSON to Date</h2>
<textarea id="jsonDateInput" placeholder='Enter JSON date'></textarea>
<button onclick="convertJsonToDate()">Convert to Date</button>
<h2>c) Convert JSON to CSV and CSV to JSON</h2>
<textarea id="dataInput" placeholder="Enter JSON or CSV"></textarea>
<button onclick="convertJsonToCsv()">Convert JSON to CSV</button>
<button onclick="convertCsvToJson()">Convert CSV to JSON</button>
<h2>d) Create Hash from String</h2>
<textarea id="hashInput" placeholder="Enter string"></textarea>
<button onclick="generateHash()">Generate Hash</button>
<div id="result"></div>
</div>
<script>
function convertJsonToObject() {
try {
const jsonInput = document.getElementById('jsonInput').value;
const jsObject = JSON.parse(jsonInput);
document.getElementById('result').innerText = 'Converted Object:'+
JSON.stringify(jsObject, null, 2);
} catch (error) {
document.getElementById('result').innerText = 'Error: ' + error.message;
}
}
function convertJsonToDate() {
try {
const jsonInput = document.getElementById('jsonDateInput').value;
const jsObject = JSON.parse(jsonInput);
const date = new Date(jsObject.date);
document.getElementById('result').innerText = 'Converted Date: ' + date.toString();
} catch (error) {
document.getElementById('result').innerText = 'Error: ' + error.message;
}
}
function convertJsonToCsv() {
const jsonInput = document.getElementById('dataInput').value;
try {
const json = JSON.parse(jsonInput);
const csv = jsonToCsv(json);
document.getElementById('result').innerHTML = `<pre>${csv}</pre>`;
} catch (error) {
alert('Invalid JSON format!');
}
}
function jsonToCsv(json) {
const array = Array.isArray(json) ? json : [json];
const header = Object.keys(array[0]);
const rows = array.map(obj =>
header.map(fieldName => JSON.stringify(obj[fieldName] || '')).join(',')
);
return [header.join(','), ...rows].join('\n');
}
function convertCsvToJson() {
const csvInput = document.getElementById('dataInput').value;
try {
const json = csvToJson(csvInput);
console.log(JSON.stringify(json));
document.getElementById('result').innerHTML = `<pre>${JSON.stringify(json, null,
2)}</pre>`;
} catch (error) {
alert('Invalid CSV format!');
}
}
function csvToJson(csv) {
const lines = csv.split('\n');
const headers = lines[0].split(',');
const result = [];
for (let i = 1; i < lines.length; i++) {
const obj = {};
const currentLine = lines[i].split(',');
if (currentLine.length === headers.length) {
for (let j = 0; j < headers.length; j++) {
obj[headers[j]] = currentLine[j].trim();
}
result.push(obj);
}
}
return result;
}
async function generateHash() {
const inputString = document.getElementById('hashInput').value;
const encoder = new TextEncoder();
const data = encoder.encode(inputString);
const hashBuffer = await crypto.subtle.digest('SHA-256', data);
const hashArray = Array.from(new Uint8Array(hashBuffer));
const hexString = hashArray.map(byte => byte.toString(16).padStart(2, '0')).join('');
document.getElementById('result').textContent = hexString;
}
</script>
</body>
</html>

-------------------------------------------------------------------------------------------------------

Lab program 8a.

a) Develop a PHP program (with HTML/CSS) to keep track of the number of visitors visiting
the web page and to display this count of visitors, with relevant headings.


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Visitor Counter</title>
<style>
body {
font-family: Arial, sans-serif;
line-height: 1.6;
margin: 0;
padding: 20px;
background-color: #f4f4f4;
}
.container {
max-width: 600px;
margin: auto;
background: white;
padding: 20px;
border-radius: 5px;
box-shadow: 0 0 10px rgba(0,0,0,0.1);
}
h1 {
color: #333;
text-align: center;
}
.counter {
font-size: 24px;
text-align: center;
margin-top: 20px;
}
</style>
</head>
<body>
<div class="container">
<h1>Welcome to Our Website</h1>
<div class="counter">
<?php
// File that stores the visitor count
$counterFile = 'visitor_count.txt';
// Check if the file exists, if not, create it and set initial count to 0
if (!file_exists($counterFile)) {
file_put_contents($counterFile, '0');
}
// Read the current count from the file
$currentCount = (int)file_get_contents($counterFile);
// Increment the count
$currentCount++;
// Write the new count back to the file
file_put_contents($counterFile, $currentCount);
// Display the current visitor count
echo "Visitor Count: " . $currentCount;
?>
</body>
</html>

-------------------------------------------------------------------------------------

Lab program 8b.

Develop a PHP program (with HTML/CSS) to sort the student records which are stored in the
database using selection sort.


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Student Record Sorter</title>
<style>
body {
font-family: Arial, sans-serif;
line-height: 1.6;
margin: 0;
padding: 20px;
background-color: #f4f4f4;
}
.container {
max-width: 800px;
margin: auto;
background: white;
padding: 20px;
border-radius: 5px;
box-shadow: 0 0 10px rgba(0,0,0,0.1);
}
h1 {
color: #333;
text-align: center;
}
table {
width: 100%;
border-collapse: collapse;
margin-top: 20px;
}
th, td {
padding: 10px;
border: 1px solid #ddd;
text-align: left;
}
th {
background-color: #f2f2f2;
}
</style>
</head>
<body>
<div class="container">
<h1>Student Records</h1>
<?php
// Database connection details
$host = 'localhost';
$dbname = 'students_records';
$username = 'root';
$password = '';
try {
$pdo = new PDO("mysql:host=$host;dbname=$dbname", $username, $password);
$pdo->setAttribute(PDO::ATTR_ERRMODE, PDO::ERRMODE_EXCEPTION);
// Fetch student records
$stmt = $pdo->query("SELECT * FROM students");
$students = $stmt->fetchAll(PDO::FETCH_ASSOC);
echo "Unsorted list";
echo "<table>";
echo "<tr><th>ID</th><th>Name</th><th>CGPA</th></tr>";
foreach ($students as $student) {
echo "<tr>";
echo "<td>" .$student['id']. "</td>";
echo "<td>" .$student['name']. "</td>";
echo "<td>" .$student['cgpa']. "</td>";
echo "</tr>";
}
echo "</table>";
// Selection sort function
function selectionSort(&$arr, $n) {
for ($i = 0; $i < $n - 1; $i++) {
$min_idx = $i;
for ($j = $i + 1; $j < $n; $j++) {
if ($arr[$j]['cgpa'] < $arr[$min_idx]['cgpa']) {
$min_idx = $j;
}
}
if ($min_idx != $i) {
$temp = $arr[$i];
$arr[$i] = $arr[$min_idx];
$arr[$min_idx] = $temp;
}
}
}
// Sort students by GPA
selectionSort($students, count($students));
// Display sorted student records
echo "Sorted list";
echo "<table>";
echo "<tr><th>ID</th><th>Name</th><th>CGPA</th></tr>";
foreach ($students as $student) {
echo "<tr>";
echo "<td>" .$student['id']. "</td>";
echo "<td>" .$student['name']. "</td>";
echo "<td>" .$student['cgpa']. "</td>";
echo "</tr>";
}
echo "</table>";
} catch(PDOException $e) {
echo "Connection failed: " . $e->getMessage();
}
?>
</div>
</body>
</html>

------------------------------------------------------------------------------

Lab program 9

Develop jQuery script (with HTML/CSS) for:
a. Appends the content at the end of the existing paragraph and list.
b. Change the state of the element with CSS style using animate() method
c. Change the color of any div that is animated.


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<style>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>jQuery Append, Animate, and Color Change Demo</title>
body {
font-family: Arial, sans-serif;
line-height: 1.6;
}
.container {
max-width: 800px;
margin:auto;
padding: 20px;
border-radius: 5px;
box-shadow: 0 0 10px rgba(0,0,0,0.1);
}
h1, h2 {
color: #333;
}
.box {
width: 100px;
height: 100px;
background-color: #3498db;
margin: 20px 0;
}
button {
padding: 10px 15px;
background-color: #2ecc71;
color: white;
border: none;
border-radius: 5px;
cursor: pointer;
margin-right: 10px;
}
button:hover {
background-color: #27ae60;
}
</style>
<script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>
</head>
<body>
<div class="container">
<h1>jQuery Demonstration</h1>
<h2> Append Content</h2>
<p id="existingParagraph">This is an existing paragraph. </p>
<ul id="existingList">
<li>Existing item 1</li>
<li>Existing item 2</li>
</ul>
<button id="appendButton">Append Content</button>
<h2> Animate Element</h2>
<div id="animateBox" class="box"></div>
<button id="animateButton">Animate Box</button>
<h2>Change Color of Animated element</h2>
<div id="colorBox" class="box"></div>
<button id="colorAnimateButton">Animate and Change Color</button>
</div>
<script>
$(document).ready(function() {
$("#appendButton").click(function() {
$("#existingParagraph").append("This content is appended.");
$("#existingList").append("<li>Appended item</li>");
});
$("#animateButton").click(function() {
$("#animateBox").animate({
width: "200px",
height: "200px",
}, 1000);
});
$("#colorAnimateButton").click(function() {
$("#colorBox").animate({
width: "200px",
height: "200px"
}, 1000,
function() {
$(this).css("background-color", "red");
});
});
});
</script>
</body>
</html>

-------------------------------------------------------------------------------------------------------

Lab program 10.

Develop a JavaScript program with Ajax (with HTML/CSS) for:
a. Use ajax() method (without Jquery) to add the text content from the text file by sending ajax
request.
b. Use ajax() method (with Jquery) to add the text content from the text file by sending ajax
request.
c. Illustrate the use of getJSON() method in jQuery
d. Illustrate the use of parseJSON() method to display JSON values.


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ajax Demo Program</title>
<script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>
<style>
body {
font-family: Arial, sans-serif;
line-height: 1.6;
margin: 0;
padding: 20px;
background-color: #f4f4f4;
}
.container {
max-width: 800px;
margin: auto;
background: white;
padding: 20px;
border-radius: 5px;
box-shadow: 0 0 10px rgba(0,0,0,0.1);
}
h1 {
color: #333;
}
h2 {
color: #666;
}
button {
background-color: #4CAF50;
border: none;
color: white;
padding: 10px 20px;
text-align: center;
text-decoration: none;
display: inline-block;
font-size: 16px;
margin: 4px 2px;
cursor: pointer;
border-radius: 4px;
}
pre {
background-color: #f8f8f8;
border: 1px solid #ddd;
border-radius: 4px;
padding: 10px;
white-space: pre-wrap;
word-wrap: break-word;
}
</style>
</head>
<body>
<div class="container">
<h1>Ajax Demo Program</h1>
<h2>a. Ajax-like operation without jQuery</h2>
<button onclick="operationWithoutJQuery()">Perform Operation (without jQuery)</button>
<pre id="result-a"></pre>
<h2>b. Ajax-like operation with jQuery</h2>
<button onclick="operationWithJQuery()">Perform Operation (with jQuery)</button>
<pre id="result-b"></pre>
<h2>c. jQuery-like getJSON() method</h2>
<button onclick="getJSONOperation()">Get JSON</button>
<pre id="result-c"></pre>
<h2>d. jQuery parseJSON() method</h2>
<button onclick="parseJSONExample()">Parse JSON</button>
<pre id="result-d"></pre>
</div>
<script>
// Simulated data
const simulatedData = {
text: "This is a sample text from a simulated server response.",
json: {
name: "John Doe",
age: 30,
city: "New York"
}
};
// a. Ajax-like operation without jQuery
function operationWithoutJQuery() {
setTimeout(function() {
document.getElementById("result-a").textContent = simulatedData.text;
}, 500);
}
// b. Ajax-like operation with jQuery
function operationWithJQuery() {
$.Deferred(function(deferred) {
setTimeout(function() {
deferred.resolve(simulatedData.text);
}, 500);
}).done(function(result) {
$("#result-b").text(result);
});
}
// c. jQuery-like getJSON() method
function getJSONOperation() {
$.Deferred(function(deferred) {
setTimeout(function() {
deferred.resolve(simulatedData.json);
}, 500);
}).done(function(result) {
$("#result-c").text(JSON.stringify(result, null, 2));
});
}
// d. jQuery parseJSON() method
function parseJSONExample() {
var jsonString = JSON.stringify(simulatedData.json);
var jsonObject = $.parseJSON(jsonString);
$("#result-d").text(JSON.stringify(jsonObject, null, 2));
}
</script>
</body>
</html>


