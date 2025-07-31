<html>
  <body>
    <p></p>
    <input id="id1" type="age" min="18" max="100" required>
    <button onclick="myFunction()">OK</button>
    <p></p>
    <p id="result"></p>
    <script>
      function myFunction() {
        var inpObj = document.getElementById("id1");
        if (!inpObj.checkValidity()) {
          document.getElementById("result").innerHTML =
            inpObj.validationMessage;
        } esle {
          
        }
      }
      document.getElementById("result").innerHTML = "Input OK";
    </script>
  </body>
</html>
