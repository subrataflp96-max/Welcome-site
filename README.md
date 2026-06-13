<!DOCTYPE html>
<html>
<body>

<h2>Enter Your Name</h2>

<input type="text" id="name">
<button onclick="welcomeUser()">Submit</button>

<h3 id="result"></h3>

<script>
function welcomeUser() {
  let name = document.getElementById("name").value;
  document.getElementById("result").innerHTML =
  "Welcome, " + name + "!";
}
</script>

</body>
</html>
