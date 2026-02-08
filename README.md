🚀 Ready to create your very own "Ask Her Out" website? 
Join me in this step-by-step HTML tutorial where we'll design and code a personalized site to help you pop the question! 
From layout to interactive features, I've got you covered. 
No coding experience re<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Important Question 😌</title>
  <style>
    body {
      height: 100vh;
      margin: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #ff9a9e, #fad0c4);
    }

    .card {
      background: white;
      padding: 40px;
      border-radius: 16px;
      text-align: center;
      box-shadow: 0 10px 30px rgba(0,0,0,0.2);
    }

    h1 {
      margin-bottom: 30px;
    }

    button {
      padding: 12px 24px;
      font-size: 18px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      margin: 10px;
    }

    #yes {
      background: #ff4d6d;
      color: white;
    }

    #no {
      background: #ccc;
      position: absolute;
    }
  </style>
</head>
<body>

  <div class="card">
    <h1>Palkin will you be my Valentine? 💘</h1>
    <button id="yes" onclick="yesClicked()">Yes ❤️</button>
    <button id="no">No 💔</button>
  </div>

  <script>
    const noButton = document.getElementById("no");

    noButton.addEventListener("mouseover", moveButton);
    noButton.addEventListener("touchstart", moveButton);

    function moveButton() {
      const x = Math.random() * (window.innerWidth - 100);
      const y = Math.random() * (window.innerHeight - 50);

      noButton.style.left = ${x}px;
      noButton.style.top = ${y}px;
    }

    function yesClicked() {
      document.body.innerHTML = `
        <div style="
          height:100vh;
          display:flex;
          justify-content:center;
          align-items:center;
          font-family:Arial;
          background:linear-gradient(135deg,#ff9a9e,#fad0c4);
        ">
          <h1>YAYYY 😍💖  
          <br>See you on Valentine’s Day 💐</h1>
        </div>
      `;
    }
  </script>

</body>
</html>quired - let's make your proposal unforgettable! 💻💘 #WebDevelopment #HTMLTutorial #LoveInTheCode
