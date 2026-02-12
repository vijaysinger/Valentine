<!DOCTYPE html>
<html>
<head>
  <title>Be My Valentine? 💖</title>
  <style>
    body {
      margin: 0;
      overflow: hidden;
      background: linear-gradient(to bottom, #ffe6f0, #ffcce6);
      font-family: Arial, sans-serif;
      text-align: center;
    }

    h1 {
      margin-top: 100px;
      color: #ff3399;
      font-size: 32px;
    }

    button {
      padding: 12px 25px;
      font-size: 18px;
      margin: 10px;
      border: none;
      border-radius: 12px;
      cursor: pointer;
      transition: 0.3s;
    }

    #yesBtn {
      background-color: #ff66b2;
      color: white;
    }

    #yesBtn:hover {
      background-color: #ff3385;
    }

    #noBtn {
      background-color: #999;
      color: white;
    }

    img {
      margin-top: 20px;
      width: 280px;
      border-radius: 15px;
    }

    #response {
      margin-top: 20px;
    }

    /* Floating hearts */
    .heart {
      position: absolute;
      color: pink;
      font-size: 20px;
      animation: float 6s linear infinite;
    }

    @keyframes float {
      0% {
        transform: translateY(100vh) scale(1);
        opacity: 1;
      }
      100% {
        transform: translateY(-10vh) scale(1.5);
