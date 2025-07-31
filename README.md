<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Welcome to Dragonfly Daycare</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      margin: 0;
      padding: 0;
      background-color: #CCDBFB;
      color: #333;
    }

    header {
      background-color: #f8b195;
      color: white;
      padding: 20px;
      text-align: center;
    }

    main {
      padding: 20px;
      max-width: 800px;
      margin: 0 auto;
    }

    .collapsible {
      background-color: #f67280;
      color: white;
      cursor: pointer;
      padding: 14px 20px;
      border: none;
      text-align: left;
      font-size: 18px;
      border-radius: 8px;
      width: 100%;
      outline: none;
      margin-bottom: 10px;
    }

    .collapsible:hover {
      background-color: #e5596a;
    }

    .content {
      overflow: hidden;
      max-height: 0;
      transition: max-height 0.4s ease-out;
      background: #fff0f3;
      padding: 0 20px;
      border-left: 3px solid #f8b195;
      margin-bottom: 20px;
      border-radius: 6px;
    }

    .content p, .content ul {
      margin: 16px 0;
    }

    .section {
      margin: 30px 0;
    }

    footer {
      text-align: center;
      background-color: #f8b195;
      color: white;
      padding: 10px;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Welcome to Dragonfly Daycare</h1>
  </header>

  <main>
    <button class="collapsible">Click to Read About Me</button>
    <div class="content">
      <p>Hi! I’m Cal — a warm, reliable, and passionate babysitter and domestic helper based locally. I’m 21 years old with over four years of hands-on babysitting experience, plus two years working at a local daycare. I care for children from newborns through to 13 years old, and I absolutely love what I do.</p>

      <p>My passion for childcare started at home, looking after my two younger brothers. They sparked my love for supporting children’s growth and development — a passion I now back with formal study as I complete my Certificate IV in Special Needs Education Support at TAFE (due to finish in late 2025).</p>

      <p>I offer a wide range of services including:</p>
      <ul>
        <li>Babysitting (including overnights & weekends)</li>
        <li>House cleaning and tidying</li>
        <li>House sitting and pet sitting (with two years’ dog-sitting experience)</li>
        <li>Running errands for busy families</li>
        <li>Fun excursions with the kids</li>
        <li>Arts and crafts (I always bring supplies when I can!)</li>
      </ul>

      <p><strong>Certifications & Equipment:</strong></p>
      <ul>
        <li>Working With Children Check</li>
        <li>Police clearance</li>
        <li>Full First Aid certification</li>
        <li>Driver’s licence and car seat</li>
        <li>Strong references available on request</li>
      </ul>

      <p><strong>Rates:</strong></p>
      <ul>
        <li>Babysitting: $35/hr (or $40/hr for two families or more)</li>
        <li>Overnights: Rate for awake hours + 1 hour for house reset, then $70/night</li>
        <li>Cleaning/Tidying: $40/hr</li>
        <li>House sitting: $20/day</li>
        <li>Pet sitting: $50/day</li>
        <li>Errands: Based on distance</li>
      </ul>

      <p>If you’re looking for someone genuine, dependable, and kid-approved — I’d love to hear from you.</p>

      <p>Warmly,<br><strong>Cal</strong></p>
    </div>

    <div class="section">
      <h2>About Me</h2>
      <p>I provide warm, reliable, and loving childcare and babysitting services. With years of experience and a passion for helping little ones thrive, I bring calm, comfort, and fun into every home I visit.</p>
    </div>

    <img src="https://github.com/user-attachments/assets/dba6b573-d38a-469a-be2a-2e44a8819f1e" width="502" height="295" alt="side one">
    <img src="https://github.com/user-attachments/assets/668b1b3f-cc90-4c99-bfdb-e46dd45d06d5" width="502" height="295" alt="side two">

    <div class="section">
      <h2>Services</h2>
      <ul>
        <li>Casual babysitting (day or night)</li>
        <li>Regular weekly care</li>
        <li>Last-minute care when you're in a pinch</li>
        <li>Bedtime stories and playtime guaranteed 🧸</li>
      </ul>
    </div>

    <div class="section paypal">
      💗 PayPal support coming soon for easy payments.
    </div>
  </main>

  <footer>
    <p>© 2025 Cal’s Babysitting & Domestic Help</p>
  </footer>

  <script>
    const coll = document.querySelector(".collapsible");
    const content = document.querySelector(".content");

    coll.addEventListener("click", function () {
      this.classList.toggle("active");
      content.style.maxHeight = content.style.maxHeight ? null : content.scrollHeight + "px";
    });
  </script>

</body>
</html>

