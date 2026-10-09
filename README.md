[about-me.html](https://github.com/user-attachments/files/33228889/about-me.html)
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Chloe Kataev</title>
<style>
  :root {
    --bg: #0f1115;
    --card: #171a21;
    --accent: #7dd3fc;
    --accent2: #c4b5fd;
    --text: #e8e8ec;
    --muted: #9aa0ac;
  }
  * { box-sizing: border-box; }
  body {
    margin: 0;
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    background: radial-gradient(circle at 20% 20%, #1b1f2a, var(--bg) 60%);
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
    color: var(--text);
    padding: 2rem;
  }
  .card {
    max-width: 640px;
    width: 100%;
    background: var(--card);
    border-radius: 20px;
    padding: 3rem 2.5rem;
    box-shadow: 0 20px 60px rgba(0,0,0,0.45);
    border: 1px solid rgba(255,255,255,0.06);
  }
  .avatar {
    width: 84px;
    height: 84px;
    border-radius: 50%;
    background: linear-gradient(135deg, var(--accent), var(--accent2));
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 2rem;
    font-weight: 700;
    color: #0f1115;
    margin-bottom: 1.5rem;
  }
  h1 {
    margin: 0 0 0.25rem;
    font-size: 2.2rem;
    letter-spacing: -0.02em;
  }
  .role {
    margin: 0 0 2rem;
    color: var(--accent);
    font-size: 1.1rem;
    font-weight: 600;
  }
  h2 {
    font-size: 0.85rem;
    text-transform: uppercase;
    letter-spacing: 0.1em;
    color: var(--muted);
    margin: 0 0 1rem;
  }
  ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    flex-direction: column;
    gap: 0.9rem;
  }
  li {
    display: flex;
    align-items: flex-start;
    gap: 0.75rem;
    background: rgba(255,255,255,0.03);
    border: 1px solid rgba(255,255,255,0.06);
    border-radius: 12px;
    padding: 1rem 1.1rem;
    font-size: 1rem;
    line-height: 1.4;
  }
  .emoji {
    font-size: 1.3rem;
    flex-shrink: 0;
  }
  footer {
    margin-top: 2.5rem;
    font-size: 0.8rem;
    color: var(--muted);
  }
</style>
</head>
<body>
  <div class="card">
    <div class="avatar">CK</div>
    <h1>Chloe Kataev</h1>
    <p class="role">Director, Head of EPAI &middot; Zeal</p>

    <h2>Fun Facts</h2>
    <ul>
      <li><span class="emoji">🐇</span> Imported a pet rabbit all the way from Russia to the US.</li>
      <li><span class="emoji">🗣️</span> Grew up speaking Hungarian.</li>
      <li><span class="emoji">🐄</span> Once lived on an operating cow farm for a year.</li>
    </ul>

    <footer>Built with care.</footer>
  </div>
</body>
</html>
