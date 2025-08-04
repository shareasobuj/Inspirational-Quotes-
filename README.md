Inspiration Quotes

<html lang="bn">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>অনুপ্রেরণার উক্তি</title>
  <style>
    body {
      font-family: 'SolaimanLipi', sans-serif, Arial, sans-serif;
      background: linear-gradient(to right, #e0f2f1, #f3e5f5);
      margin: 0;
      padding: 0;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: flex-start;
      color: #333;
    }
    header {
      background-color: #6a1b9a;
      color: #fff;
      width: 100%;
      padding: 20px 0;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2rem;
    }
    .container {
      max-width: 700px;
      width: 90%;
      margin-top: 40px;
      text-align: center;
    }
    .quote-box {
      background: #fff;
      padding: 30px 25px;
      border-radius: 12px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.1);
      margin-bottom: 25px;
      transition: transform 0.3s ease;
    }
    .quote-box:hover {
      transform: scale(1.03);
    }
    .quote-text {
      font-size: 1.6rem;
      line-height: 1.5;
      margin-bottom: 15px;
      min-height: 90px;
    }
    .author {
      font-weight: bold;
      font-size: 1.1rem;
      color: #6a1b9a;
      text-align: right;
    }
    .buttons {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 12px;
    }
    button {
      background-color: #6a1b9a;
      color: #fff;
      border: none;
      padding: 12px 22px;
      border-radius: 8px;
      font-size: 1rem;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }
    button:hover {
      background-color: #4a148c;
    }
    footer {
      margin-top: auto;
      padding: 20px 10px;
      width: 100%;
      text-align: center;
      background-color: #ede7f6;
      font-size: 0.9rem;
      color: #555;
    }
    @media print {
      body * {
        visibility: hidden;
      }
      #printable, #printable * {
        visibility: visible;
      }
      #printable {
        position: absolute;
        left: 0;
        top: 0;
        width: 100%;
        padding: 20px;
        background: white;
        color: black;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>প্রেরণাদায়ক বাংলা উক্তি</h1>
  </header>

  <main class="container">
    <div class="quote-box" id="printable">
      <p class="quote-text" id="quoteText">লোড হচ্ছে...</p>
      <p class="author">— শাহরিয়া সবুজ শিশির</p>
    </div>

    <div class="buttons">
      <button id="newQuoteBtn">নতুন উক্তি</button>
      <button id="copyBtn">কপি</button>
      <button id="printBtn">প্রিন্ট / PDF</button>
      <button id="shareBtn">শেয়ার</button>
    </div>
  </main>

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

    // এলোমেলো উক্তি দেখানোর ফাংশন
    function showRandomQuote() {
      const idx = Math.floor(Math.random() * quotes.length);
      document.getElementById('quoteText').textContent = quotes[idx];
    }

    // কপি ফাংশন
    function copyQuote() {
      const text = document.getElementById('quoteText').textContent + "\n— শাহরিয়া সবুজ শিশির";
      if (navigator.clipboard) {
        navigator.clipboard.writeText(text).then(() => {
          alert("উক্তি কপি করা হয়েছে!");
        }).catch(() => {
          alert("কপি করতে সমস্যা হয়েছে।");
        });
      } else {
        alert("আপনার ব্রাউজার কপি সাপোর্ট করে না।");
      }
    }

    // প্রিন্ট ফাংশন
    function printQuote() {
      window.print();
    }

    // শেয়ার ফাংশন
    function shareQuote() {
      const text = document.getElementById('quoteText').textContent + "\n— শাহরিয়া সবুজ শিশির";
      if (navigator.share) {
        navigator.share({
          title: 'অনুপ্রেরণার উক্তি',
          text: text,
          url: window.location.href
        }).catch((err) => {
          alert('শেয়ার করতে সমস্যা হয়েছে।');
          console.error(err);
        });
      } else {
        alert("আপনার ব্রাউজারে শেয়ার সাপোর্ট নেই। কপি বাটন ব্যবহার করুন।");
      }
    }

    // ইভেন্ট লিসেনার যুক্ত করা
    document.getElementById('newQuoteBtn').addEventListener('click', showRandomQuote);
    document.getElementById('copyBtn').addEventListener('click', copyQuote);
    document.getElementById('printBtn').addEventListener('click', printQuote);
    document.getElementById('shareBtn').addEventListener('click', shareQuote);

    // পেজ লোডের সময় একবার উক্তি দেখানো
    window.onload = showRandomQuote;
  </script>
</body>
</html>
