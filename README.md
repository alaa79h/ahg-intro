<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>AHG Intro</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      background-color: #f9f9f9;
      font-family: 'Segoe UI', sans-serif;
    }

    .logo {
      opacity: 0;
      transform: scale(0.8);
      animation: showLogo 1.5s ease-out forwards;
    }

    .slogan {
      margin-top: 20px;
      font-size: 18px;
      color: #333;
      opacity: 0;
      transform: translateY(15px);
      animation: showText 1.5s ease-out forwards;
      animation-delay: 1.6s;
    }

    @keyframes showLogo {
      to {
        opacity: 1;
        transform: scale(1);
      }
    }

    @keyframes showText {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
  </style>
</head>
<body>

  <img class="logo"
       src="https://drive.google.com/uc?export=view&id=1N9C8coJNwRagK9z_d9wyvfUEg-BN_uGW"
       alt="AHG Solutions Logo"
       width="250">
  <div class="slogan">
    Elevating excellence through innovative and tailored solutions.
  </div>

</body>
</html>
