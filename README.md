<!DOCTYPE html>
<html lang="hi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mohit Patel's Blog</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>🌟 Mohit Patel का ब्लॉग 🌟</h1>
    <p class="lang-hi">जहाँ मिलती है आपको रोचक खबरें, वीडियो और कहानियाँ!</p>
    <p class="lang-en" style="display:none;">Where you find exciting news, videos & stories!</p>
    <button id="dark-toggle">🌙 Dark Mode</button>
    <button id="lang-toggle">🇬🇧 English</button>
  </header>

  <nav>
    <a href="#home">होम</a>
    <a href="#article">लेख</a>
    <a href="#contact">सुझाव / सवाल</a>
  </nav>

  <main>
    <section id="article" class="article">
      <h2>🚀 इंडिया का अगला चंद्रयान मिशन – क्या है ख़ास?</h2>
      <p><strong>दिनांक:</strong> 9 जुलाई 2025</p>
      <img src="images/chandrayaan.jpg" alt="चंद्रयान मिशन">
      <p class="lang-hi">भारत एक बार फिर तैयार है चाँद को छूने के लिए! चंद्रयान-4 मिशन की तैयारी ज़ोरों पर है और इस बार ISRO एक नया इतिहास रचने वाला है। जानिए मिशन की खासियतें, तकनीक और इसका भारत पर क्या असर होगा।</p>
      <p class="lang-en" style="display:none;">India is ready to touch the moon again! Chandrayaan-4 is set to make history. Learn about its mission, technology and its impact.</p>
      <video controls>
        <source href="https://youtu.be/vfq9dfaYDzc?si=kxbuu4d6y5TaQGWF" type="video/mp4">
        आपका ब्राउज़र वीडियो सपोर्ट नहीं करता।
      </video>
      <p>👉 <a href="https://isro.gov.in">और जानकारी ISRO की वेबसाइट पर</a></p>
    </section>

    <section class="article">
      <h2>🍴 दिल्ली की सड़कें और उनका ज़ायका – Street Food Special!</h2>
      <p><strong>दिनांक:</strong> 5 जुलाई 2025</p>
      <img src="images/streetfood.jpg" alt="दिल्ली स्ट्रीट फूड">
      <p class="lang-hi">अगर आप खाने के शौकीन हैं, तो दिल्ली की गली-गली में छुपे ये स्ट्रीट फूड जन्नत से कम नहीं। छोले भटूरे, गोलगप्पे, और परांठे वाली गली की सैर ज़रूर करें!</p>
      <p class="lang-en" style="display:none;">If you're a foodie, Delhi's street food is a paradise! From chole bhature to golgappe, experience the mouthwatering magic in every lane.</p>
      <video controls>
        <source src="videos/streetfood.mp4" type="video/mp4">
        वीडियो देखने में समस्या आ रही है।
      </video>
      <p>👉 <a href="https://www.delhitourism.gov.in">दिल्ली टूरिज्म पर और पढ़ें</a></p>
    </section>

    <section id="contact">
      <h2>💬 अपने सुझाव दें या सवाल पूछें</h2>
      <form action="#" method="post" onsubmit="alert('आपका सुझाव सबमिट हो गया!'); return false;">
        <label for="name">आपका नाम:</label><br>
        <input type="text" id="name" name="name" required><br>
        <label for="message">संदेश / सुझाव:</label><br>
        <textarea id="message" name="message" rows="5" required></textarea><br>
        <button type="submit">सबमिट करें</button>
      </form>
    </section>
  </main>

  <footer>
    <p>© 2025 Mohit Patel | बनाए गए दिल से 🇮🇳</p>
  </footer>
  <script src="script.js"></script>
</body>
</html>
