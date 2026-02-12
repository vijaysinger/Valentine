<!DOCTYPE html>
<html>
<head>
  <title>Be My Valentine?</title>
  <style>
    body {
      text-align: center;
      font-family: Arial, sans-serif;
      background-color: #ffe6f0;
      margin-top: 100px;
    }
    h1 {
      color: #ff3366;
    }
    button {
      padding: 12px 25px;
      font-size: 18px;
      margin: 10px;
      border: none;
      border-radius: 10px;
      cursor: pointer;
    }
    #yesBtn {
      background-color: #ff66b2;
      color: white;
    }
    #noBtn {
      background-color: #999;
      color: white;
    }
    img {
      margin-top: 20px;
      width: 300px;
      border-radius: 15px;
    }
  </style>
</head>
<body>

  <h1>Will You Be My Valentine? 💖</h1>

  <button id="yesBtn" onclick="showYes()">Yes 😊</button>
  <button id="noBtn" onclick="showNo()">No 🙈</button>

  <div id="response"></div>

  <script>
    function showYes() {
      document.getElementById("response").innerHTML =
        "<h2>Okayyyy I see you 😌💘</h2><img src='PASTE_YES_GIF_LINK_HERE'>";
    }

    function showNo() {
      document.getElementById("response").innerHTML =
        "<h2>Hmm… I might have to try harder then 😏</h2><img src='PASTE_NO_GIF_LINK_HERE'>";
    }
  </script>

</body>
</html>
