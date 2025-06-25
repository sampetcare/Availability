<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My Availability</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Poppins', sans-serif;
      background-color: #f5f7fb;
      color: #333;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: flex-start;
      min-height: 100vh;
    }

    h1 {
      margin-top: 40px;
      font-weight: 600;
      font-size: 2em;
      color: #444;
    }

    p {
      font-weight: 300;
      color: #666;
      margin-bottom: 20px;
    }

    .calendar-wrapper {
      background: white;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      border-radius: 10px;
      padding: 20px;
      max-width: 900px;
      width: 90%;
      margin-bottom: 40px;
    }

    iframe {
      width: 100%;
      height: 600px;
      border: none;
      border-radius: 8px;
    }
  </style>
</head>
<body>
  <h1>🗓️ My Availability</h1>
  <p>If a date shows as <strong>BOOKED</strong>, I’m unfortunately full for <strong>dogsitting</strong> slots, but still may be available for <strong>dogwalks</strong> or <strong>drop ins</strong>! Please contact me directly to make any booking - Thank you! ☺️</p>

  <div class="calendar-wrapper">
    <iframe 
      src="https://calendar.google.com/calendar/embed?height=600&amp;wkst=2&amp;ctz=Europe%2FLondon&amp;showPrint=0&amp;src=c2FtOTRhbGxlbkBnbWFpbC5jb20&amp;color=%23F06292"
      frameborder="0" scrolling="no">
    </iframe>
  </div>
</body>
</html>
