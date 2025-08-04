 Inspirational-Quotes
<html lang="bn">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>অনুপ্রেরণার উক্তি</title>
  <style>
    body {
      font-family: 'SolaimanLipi', sans-serif;
      background: linear-gradient(to right, #e0f2f1, #f3e5f5);
      color: #333;
      margin: 0;
      padding: 0;
      display: flex;
      flex-direction: column;
      align-items: center;
      min-height: 100vh;
    }

    header {
      background-color: #6a1b9a;
      color: #fff;
      padding: 20px 0;
      width: 100%;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2rem;
    }

    .container {
      flex: 1;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      padding: 30px;
      max-width: 800px;
      text-align: center;
    }

    .quote-box {
      background-color: #ffffffee;
      padding: 25px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.15);
      margin-bottom: 20px;
      transition: all 0.3s;
    }

    .quote-text {
      font-size: 1.5rem;
      line-height: 1.6;
      margin-bottom: 10px;
    }

    .author {
      font-size: 1.1rem;
      font-weight: bold;
      color: #6a1b9a;
    }

    .buttons {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 10px;
      margin-top: 20px;
    }

    button {
      background-color: #6a1b9a;
      color: white;
      padding: 10px 16px;
      font-size: 1rem;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      transition: background-color 0.3s;
    }

    button:hover {
      background-color: #4a148c;
    }

    footer {
      margin-top: auto;
      padding: 15px;
      text-align: center;
      background-color: #ede7f6;
      width: 100%;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>প্রেরণাদায়ক বাংলা উক্তি</h1>
  </header>

  <div class="container">
    <div class="quote-box" id="quoteBox">
      <div class="quote-text" id="quoteText">লোড হচ্ছে...</div>
      <div class="author">— শাহরিয়া সবুজ শিশির</div>
    </div>
    
    <div class="buttons">
      <button onclick="newQuote()">নতুন উক্তি</button>
      <button onclick="copyQuote()">কপি</button>
      <button onclick="printQuote()">প্রিন্ট / PDF</button>
      <button onclick="shareQuote()">শেয়ার</button>
    </div>
  </div>

  <footer>
    &copy; ২০২৫ | সম্পূর্ণ কপিরাইট-মুক্ত | উপস্থাপনায়: শাহরিয়া সবুজ শিশির
  </footer>

  <script>
    const quotes = [
      "সফলতা আসে ধৈর্য, পরিশ্রম ও ইতিবাচক মনোভাবের মাধ্যমে।",
      "স্বপ্ন দেখাই যথেষ্ট নয়, সেই স্বপ্নের পেছনে ছুটতে হয়।",
      "ভয়কে জয় করলেই আপনি নিজের আসল শক্তিকে চিনবেন।",
      "প্রতিদিন একটু একটু করে উন্নতি মানেই বড় সাফল্যের দিকে অগ্রসর হওয়া।",
      "পরিস্থিতি যেমনই হোক, নিজের উপর বিশ্বাস রাখুন।",
      "অসফলতা মানে শেখার একটি নতুন সুযোগ।",
      "তোমার পরিশ্রমই তোমার পরিচয় গড়ে তোলে।",
      "যে নিজেকে বদলাতে পারে, সে বিশ্বকে বদলাতে পারে।",
      "আলো আসবেই, যদি তুমি অন্ধকারে পথ চলা থামিয়ে না দাও।",
      "সফলতার গল্পের পেছনে থাকে অসংখ্য ব্যর্থতার ইতিহাস।",
      "সমস্যার মাঝেই লুকিয়ে থাকে নতুন সম্ভাবনা।",
      "আজকের পরিশ্রমই আগামী দিনের আনন্দের মূল।",
      "নিজের লক্ষ্য জানলে পথ খুঁজে নিতে বেশি সময় লাগে না।",
      "প্রতিদিন একটু ভালো হতেই জীবনের মানে বদলে যায়।",
      "তোমার আত্মবিশ্বাসই তোমার সবচেয়ে বড় শক্তি।",
      "কখনো হাল ছেড়ো না, সফলতা শেষ মুহূর্তে এসে ধরা দেয়।",
      "প্রত্যেক নতুন দিন এক নতুন সুযোগ নিয়ে আসে।",
      "শুধু শুরু করো, বাকি পথ আপনাআপনি তৈরি হবে।",
      "বিপদ যত বড়ই হোক, সাহস থাকলে পার হওয়া যায়।",
      "ইচ্ছাশক্তি থাকলে অসম্ভব কিছুই নয়।",
      "জয় তাদেরই হয়, যারা হেরে গিয়েও উঠে দাঁড়ায়।"
    ];

    function newQuote() {
      const index = Math.floor(Math.random() * quotes.length);
      document.getElementById('quoteText').textContent = quotes[index];
    }

    function copyQuote() {
      const text = document.getElementById('quoteText').textContent + "\n— শাহরিয়া সবুজ শিশির";
      navigator.clipboard.writeText(text).then(() => {
        alert("উক্তি কপি করা হয়েছে!");
      });
    }

    function printQuote() {
      const quote = document.getElementById('quoteText').textContent;
      const printWindow = window.open('', '', 'width=600,height=400');
      printWindow.document.write(`
        <html><head><title>প্রিন্ট করুন</title></head><body>
        <h2>${quote}</h2>
        <p style="text-align:right; font-weight:bold;">— শাহরিয়া সবুজ শিশির</p>
        <script>window.print();</script>
        </body></html>
      `);
      printWindow.document.close();
    }

    function shareQuote() {
      const text = document.getElementById('quoteText').textContent + "\n— শাহরিয়া সবুজ শিশির";
      if (navigator.share) {
        navigator.share({
          title: 'অনুপ্রেরণার উক্তি',
          text: text,
          url: window.location.href
        }).catch((error) => console.log('Sharing failed:', error));
      } else {
        alert("আপনার ব্রাউজারে শেয়ার অপশনটি সাপোর্ট করে না। আপনি কপি ব্যবহার করুন।");
      }
    }

    window.onload = newQuote;
  </script>
