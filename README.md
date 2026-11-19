**1. Personal webpage (HTML5)**
<!DOCTYPE html>
<html><body>
<h1>My Webpage</h1>
<p>Hi, I am <b>Rahul</b>.</p>
<ul><li>Reading</li><li>Coding</li></ul>
<table border="1">
<tr><th>Degree</th><th>Year</th></tr>
<tr><td>BCA</td><td>2026</td></tr>
</table>
<img src="photo.jpg" width="150"><br>
<audio src="audio.mp3" controls></audio><br>
<video src="video.mp4" width="300" controls></video><br>
<a href="https://google.com">Visit Google</a>
</body></html


**2. Responsive page (CSS3)**
<!DOCTYPE html>
<html><head>
<meta name="viewport" content="width=device-width">
<style>
body{margin:0;font-family:Arial;background:#eee}
h1{background:navy;color:white;text-align:center;padding:20px}
p{width:60%;margin:20px auto;padding:20px;background:white;text-align:justify;font
size:18px}
@media(max-width:600px){p{width:90%}}
</style>
</head><body>
<h1>CSS3 Page</h1>
<p>This page shows colors, backgrounds, margin, padding, text formatting and 
alignment.</p>
</body></html>

**4. JavaScript basics**
<script>
let marks = [85, 72, 90], total = 0;
for (let m of marks) total += m;
let avg = total / marks.length;
document.write("Total: " + total + "<br>Average: " + avg + "<br>");
if (avg >= 80) document.write("Grade A");
else if (avg >= 60) document.write("Grade B");
else document.write("Fail");
</script>

5. DOM manipulation
<!DOCTYPE html>
<html><head>
<meta name="viewport" content="width=device-width">
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" 
rel="stylesheet">
</head><body>
<nav class="navbar navbar-dark bg-dark px-3"><a class="navbar-brand">My Site</a>
</nav>
<div class="container mt-3">
  <div class="alert alert-success">Welcome!</div>
  <div class="card p-3 mb-3"><h5>Card Title</h5><button class="btn btn
primary">Click</button></div>
  <form>
    <input class="form-control mb-2" placeholder="Name">
    <button class="btn btn-success">Submit</button>
  </form>
</div>
</body></html>
<script>
let marks = [85, 72, 90], total = 0;
for (let m of marks) total += m;
let avg = total / marks.length;
document.write("Total: " + total + "<br>Average: " + avg + "<br>");
if (avg >= 80) document.write("Grade A");
else if (avg >= 60) document.write("Grade B");
else document.write("Fail");
</script>
<h1 id="h">Hello Students!</h1>
<img id="img" src="a.jpg" width="150"><br>
<button onclick="change()">Click Me</button>
<script>
function change() {
  document.getElementById("h").innerHTML = "Content Changed!";
  document.body.style.background = "lightblue";
  document.getElementById("img").src = "b.jpg";
}
</script























