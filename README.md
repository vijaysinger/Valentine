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
        "<h2>Okayyyy I see you 😌💘</h2><img src='https://media1.tenor.com/m/CGQOSjUZ6ggAAAAd/corazon-de-minion-minion.gif![image](https://github.com/user-attachments/assets/c02ec5c1-327e-4513-bdff-a788041ffee9)
'>";
    }

    function showNo() {
      document.getElementById("response").innerHTML =
        "<h2>Hmm… I might have to try harder then 😏</h2><img src='https://media4.giphy.com/media/v1.Y2lkPTZjMDliOTUyNGY3eDQ0dHg5b3V5cTIzNmJhZzZjZHQ4ajMwdTlnMHRjN2ZhcGFjciZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/xM3ptQtRagYCs/giphy.gif";
    }
  </script>

</body>
</html>
