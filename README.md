<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Selamat Ulang Tahun, Aping!</title>
  <style>
    body {
      background-color: #fff8f0;
      font-family: 'Segoe UI', sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      overflow: hidden;
      position: relative;
    }
    .container {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      text-align: center;
    }
    .slide {
      display: inline-block;
      opacity: 0;
      animation: slideIn 1s forwards;
      font-size: 2em;
      color: #ff5c8d;
      margin: 10px;
    }
    .slide:nth-child(odd) {
      animation-delay: 0.5s;
    }
    .slide:nth-child(even) {
      animation-delay: 1s;
    }
    @keyframes slideIn {
      0% {
        transform: translateY(50px);
        opacity: 0;
      }
      100% {
        transform: translateY(0);
        opacity: 1;
      }
    }
    .fireworks {
      position: absolute;
      top: 10%;
      left: 50%;
      transform: translateX(-50%);
      width: 100%;
      height: 100%;
      background: url('https://cdn.pixabay.com/photo/2017/12/31/19/44/fireworks-3054799_960_720.jpg') no-repeat center center;
      background-size: cover;
      opacity: 0.5;
      animation: fireworksAnimation 5s infinite;
    }
    @keyframes fireworksAnimation {
      0% {
        opacity: 0.5;
      }
      50% {
        opacity: 1;
      }
      100% {
        opacity: 0.5;
      }
    }
  </style>
</head>
<body>
  <div class="fireworks"></div>
  <div class="container">
    <div class="slide">Hai</div>
    <div class="slide">Ping,</div>
    <div class="slide">tahu</div>
    <div class="slide">nggak?</div>
    <div class="slide">Hari</div>
    <div class="slide">ini</div>
    <div class="slide">bukan</div>
    <div class="slide">cuma</div>
    <div class="slide">kamu</div>
    <div class="slide">yang</div>
    <div class="slide">bahagia…</div>
    <div class="slide">Tapi</div>
    <div class="slide">kalender</div>
    <div class="slide">juga,</div>
    <div class="slide">karena</div>
    <div class="slide">bisa</div>
    <div class="slide">nulis</div>
    <div class="slide">tanggal</div>
    <div class="slide">ulang</div>
    <div class="slide">tahun</div>
    <div class="slide">orang</div>
    <div class="slide">paling</div>
    <div class="slide">spesial.</div>
    <div class="slide">Aku</div>
    <div class="slide">doain</div>
    <div class="slide">kamu</div>
    <div class="slide">sehat</div>
    <div class="slide">terus,</div>
    <div class="slide">makin</div>
    <div class="slide">kece,</div>
    <div class="slide">makin</div>
    <div class="slide">banyak</div>
    <div class="slide">alasan</div>
    <div class="slide">buat</div>
    <div class="slide">bahagia,</div>
    <div class="slide">makin-makin</div>
    <div class="slide">deh</div>
    <div class="slide">pokoknya.</div>
    <div class="slide">Dan</div>
    <div class="slide">yang</div>
    <div class="slide">penting:</div>
    <div class="slide">makin</div>
    <div class="slide">sayang</div>
    <div class="slide">sama</div>
    <div class="slide">diri</div>
    <div class="slide">sendiri…</div>
    <div class="slide">(*Eh</div>
    <div class="slide">tapi…</div>
    <div class="slide">kalau</div>
    <div class="slide">mau</div>
    <div class="slide">sayang</div>
    <div class="slide">sama</div>
    <div class="slide">aku</div>
    <div class="slide">juga</div>
    <div class="slide">si</div>
    <div class="slide">boleh</div>
    <div class="slide">banget</div>
    <div class="slide">sih</div>
    <div class="slide">hehe)</div>
    <div class="slide">eh</div>
    <div class="slide">maksudnya</div>
    <div class="slide">sayang</div>
    <div class="slide">sama</div>
    <div class="slide">keluarga…</div>
    <div class="slide">keluarga!</div>
    <div class="slide">jangan</div>
    <div class="slide">mikir</div>
    <div class="slide">yang</div>
    <div class="slide">aneh-aneh</div>
    <div class="slide">ya,</div>
    <div class="slide">Ping)</div>
  </div>
</body>
</html>
