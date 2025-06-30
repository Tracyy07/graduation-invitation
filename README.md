<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Graduation Invitation</title>
  <link href="https://fonts.googleapis.com/css?family=Great+Vibes|Montserrat:400,700&display=swap" rel="stylesheet">
  <style>
    body {
      background: #fffbe6;
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
      border: 2px solid #e1c06d;
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
      background: #fffbe6;
      border: 2px dotted #e1c06d;
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
      color: #c9ac32;
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
      color: #a6892d;
      margin: 0
