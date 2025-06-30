<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Graduation Invitation</title>
  <link href="https://fonts.googleapis.com/css?family=Great+Vibes|Montserrat:400,700&display=swap" rel="stylesheet">
  <style>
    body {
      background: #fdf6e3;
      font-family: 'Montserrat', Arial, sans-serif;
      margin: 0;
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
    }
    .invitation-card {
      background: #fff;
      border-radius: 18px;
      box-shadow: 0 6px 32px #c9ac3299, 0 0px 0px #ccc;
      border: 2px solid #efd38d;
      padding: 48px 44px 36px;
      max-width: 410px;
      text-align: center;
      position: relative;
    }
    .invitation-card::before, .invitation-card::after {
      content: '';
      position: absolute;
      width: 80px;
      height: 80px;
      border-radius: 50%;
      background: #fdf6e3;
      border: 2px dotted #efd38d;
      top: -40px;
      left: -40px;
      z-index: 0;
    }
    .invitation-card::after {
      top: auto;
      left: auto;
      bottom: -40px;
      right: -40px;
    }
    .title {
      font-family: 'Great Vibes', cursive;
      color: #b89b2b;
      font-size: 2.3em;
      margin-bottom: 0.4em;
      font-weight: normal;
    }
    .subtitle {
      font-size: 1.1em;
      color: #444;
      margin-bottom: 1.7em;
      letter-spacing: 1px;
    }
    .graduate-name {
      font-family: 'Great Vibes', cursive;
      font-size: 2em;
      color: #947a24;
      margin: 0.2em 0 0.5em 0;
    }
    .details {
      color: #856404;
      font-size: 1em;
      margin-bottom: 1.5em;
    }
    .divider {
      width: 60px;
      border: 0;
      border-top: 2px solid #efd38d;
      margin: 1.2em auto 1.7em auto;
    }
    .rsvp {
      font-size: 0.99em;
      color: #8a6d1d;
      margin-top: 1.1em;
      letter-spacing: 0.2px;
    }
    @media (max-width: 480px) {
      .invitation-card {
        padding: 24px 8px;
        max-width: 97vw;
      }
    }
  </style>
</head>
<body>
  <div class="invitation-card">
    <div class="title">A Special Day to Remember</div>
    <div class="subtitle">With great joy and pride, I invite you to celebrate my graduation</div>
    <div class="graduate-name">Tracy Johnson</div>
    <hr class="divider"/>
    <div class="details">
      <b>Date:</b> July 15, 2025<br>
      <b>Time:</b> 3:00 PM<br>
      <b>Venue:</b> Star Hall, City University<br>
    </div>
    <div>
      Your presence would mean so much to me as I mark this important milestone. Let’s make memories together!
    </div>
    <div class="rsvp">
      Kindly RSVP: <a href="mailto:tracy@email.com">tracy@email.com</a>
    </div>
  </div>
</body>
</html>
