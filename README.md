<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Danny Wong</title>

  <style>
    :root {
      --bg: #ffffff;
      --text: #111111;
      --muted: #555555;
      --accent: #000000;
    }

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      background: var(--bg);
      color: var(--text);
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI",
        Helvetica, Arial, sans-serif;
      line-height: 1.65;
    }

    .container {
      max-width: 720px;
      padding: 3rem 1.5rem;
      margin: 0 auto;
    }

    h1 {
      font-size: 2.25rem;
      margin-bottom: 2rem;
      font-weight: 600;
    }

    p {
      margin-bottom: 1.5rem;
    }

    a {
      color: var(--accent);
      text-decoration: none;
      border-bottom: 1px solid #ccc;
    }

    a:hover {
      border-bottom-color: var(--accent);
    }

    .contact {
      margin-top: 2.5rem;
    }

    footer {
      margin-top: 3rem;
      font-size: 0.9rem;
      color: var(--muted);
    }
  </style>
</head>

<body>
  <main class="container">
    <h1>Hi, I'm Danny.</h1>

    <p>
      I help brands build marketing programs that attract customers,
      develop partnerships, and earn media coverage.
    </p>

    <p>
      At age 19, I co-founded Blank Label, an award-winning luxury menswear
      company. At 21, I was the youngest honoree in Inc. Magazine's
      30 under 30 list in 2012.
    </p>

    <p>
      Since then, I've worked with two dozen brands — ranging from
      venture-backed startups to Fortune 500 companies — to build their
      businesses through data-driven marketing and storytelling.
      My articles and reports have been referenced by Adweek, BuzzFeed,
      Harvard Business Review, TechCrunch, The New York Times, and
      The Wall Street Journal.
      Additionally, I've contributed directly to Entrepreneur, Forbes,
      The Huffington Post, The Next Web, and VentureBeat.
    </p>

    <p>
      At any given time, I work with only a handful of brands to help power
      their digital marketing initiatives. For new engagements, I have a
      two-month wait list. So, if you have an immediate need to fill,
      I'm not your guy (though I probably know a handful of experts I can
      refer you to). But if you are willing to wait, we can hop on a call
      next week to see if my skills align with your long-term needs.
    </p>

    <div class="contact">
      <p><strong>Want to get in touch?</strong></p>

      <p>
        Reach me over email, Twitter, or LinkedIn to start a discussion
        about leading your digital marketing strategy or contributing
        to your current digital marketing initiatives.
      </p>

      <p>
        Email:
        <a href="mailto:dannywong1190@gmail.com">
          dannywong1190@gmail.com
        </a><br />
        Twitter:
        <a href="https://twitter.com/dannywong1190" target="_blank">
          @dannywong1190
        </a><br />
        LinkedIn:
        <a href="https://www.linkedin.com/in/dannywong1190" target="_blank">
          /dannywong1190
        </a>
      </p>
    </div>

    <footer>
      © <span id="year"></span> Danny Wong
    </footer>
  </main>

  <script>
    document.getElementById("year").textContent =
      new Date().getFullYear();
  </script>
</body>
</html>
