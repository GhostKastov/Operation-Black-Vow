<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <title>دعوة SDF الخاصة</title>
  <style>
    body {
      margin: 0;
      background-color: black;
      color: #ffd700;
      font-family: 'Courier New', monospace;
      text-align: center;
      position: relative;
      overflow: hidden;
    }

    .background {
      position: absolute;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background: url('PUT_YOUR_IMAGE_URL_HERE') no-repeat center;
      background-size: contain;
      opacity: 0.1;
      z-index: 0;
    }

    .content {
      position: relative;
      z-index: 1;
      padding: 50px 20px;
    }

    h1 {
      font-size: 2.5em;
      margin-bottom: 30px;
      color: #ff0000;
    }

    .invite-text {
      font-size: 1.2em;
      line-height: 2;
      max-width: 800px;
      margin: 0 auto 40px;
    }

    .button {
      font-size: 1.2em;
      padding: 15px 30px;
      margin: 10px;
      border: 2px solid #ffd700;
      background-color: transparent;
      color: #ffd700;
      cursor: pointer;
      transition: 0.3s;
    }

    .button:hover {
      background-color: #ffd700;
      color: black;
    }

    #discord-link {
      display: none;
      margin-top: 20px;
      font-size: 1.1em;
    }

    .hidden {
      display: none;
    }
  </style>
</head>
<body>

<div class="background"></div>

<div class="content">
  <img src="PUT_YOUR_IMAGE_URL_HERE" alt="SDF Logo" style="max-width: 200px; margin-bottom: 30px;">
  <h1>⚠️ دعوة سرية للغاية ⚠️</h1>
  <p class="invite-text">
    تم اختيارك بعناية للانضمام إلى فرقة الردع الخاصة <strong>SDF</strong>.<br>
    هذا القرار ليس قابلاً للتفاوض.<br>
    أمامك خياران فقط. فكر بحكمة، القرار مصيري.<br>
  </p>

  <button class="button" onclick="accept()">أقبل الانضمام</button>
  <button class="button" onclick="reject()">أرفض</button>

  <div id="discord-link">
    رابط الدخول إلى السيرفر:<br>
    <a href="https://discord.gg/Kr7D6nfD" target="_blank">https://discord.gg/Kr7D6nfD</a><br>
    لديك 20 ثانية قبل إغلاق هذه الصفحة تلقائيًا.
  </div>
</div>

<script>
  function accept() {
    document.getElementById('discord-link').style.display = 'block';
    setTimeout(() => {
      window.close();
    }, 20000);
  }

  function reject() {
    window.location.href = "about:blank";
  }
</script>

</body>
</html>
