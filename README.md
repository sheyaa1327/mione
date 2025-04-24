<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Míone Promotion</title>
  <style>
    :root {
      --pink: #ff69b4;
      --black: #1a1a1a;
      --white: #fff;
    }
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body { font-family: 'Segoe UI', sans-serif; background: var(--black); color: var(--white); }
    header, footer { background: var(--pink); color: var(--black); padding: 1rem; text-align: center; }
    nav ul { list-style: none; display: flex; justify-content: center; gap: 1rem; padding: 0.5rem 0; }
    nav ul li a { text-decoration: none; color: var(--black); font-weight: bold; }
    section { padding: 2rem; }
    .game-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 1rem; }
    .game-card { background: #2c2c2c; padding: 1rem; border-radius: 10px; text-align: center; }
    .game-card h4 { color: var(--pink); }
    input, select, button { width: 100%; padding: 0.75rem; margin: 0.5rem 0; border-radius: 5px; border: none; }
    button { background: var(--pink); color: var(--black); font-weight: bold; cursor: pointer; }
    .footer-links a { margin-right: 10px; color: var(--black); text-decoration: underline; }
  </style>
</head>
<body>
  <header>
    <h1>Míone Promotion</h1>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#games">Games</a></li>
        <li><a href="#register">Register</a></li>
        <li><a href="#account">My Account</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#help">Help</a></li>
      </ul>
    </nav>
  </header>

  <section id="home">
    <h2>Welcome to Míone Promotion</h2>
    <p>Invest in your favorite Steam games and earn daily income with Míone Promotion!</p>
    <button onclick="document.getElementById('register').scrollIntoView()">Start Investing Now</button>
  </section>

  <section id="games">
    <h3>Current Steam Game Promotions</h3>
    <div class="game-grid">
      <div class="game-card"><h4>Team Fortress 2</h4><p>₱300 → ₱20/day for 60 days</p></div>
      <div class="game-card"><h4>GTA V</h4><p>₱500 → ₱30/day for 60 days</p></div>
      <div class="game-card"><h4>Counter Strike 2</h4><p>₱1250 → ₱80/day for 60 days</p></div>
      <div class="game-card"><h4>DOTA 2</h4><p>₱2200 → ₱160/day for 60 days</p></div>
      <div class="game-card"><h4>PUBG: Battlegrounds</h4><p>₱3750 → ₱200/day for 60 days</p></div>
    </div>
  </section>

  <section id="register">
    <h3>Register with Your Philippine Number</h3>
    <form>
      <input type="tel" pattern="09[0-9]{9}" placeholder="09xxxxxxxxx" required />
      <input type="password" placeholder="Create Password" required />
      <select required>
        <option value="">Select Investment Plan</option>
        <option>₱300 - ₱20/day for 60 days</option>
        <option>₱500 - ₱30/day for 60 days</option>
        <option>₱1250 - ₱80/day for 60 days</option>
        <option>₱2200 - ₱160/day for 60 days</option>
        <option>₱3750 - ₱200/day for 60 days</option>
      </select>
      <label><input type="checkbox" required /> I agree to the Terms & Conditions</label>
      <button type="submit">Create Account</button>
    </form>
  </section>

  <section id="account">
    <h3>My Account</h3>
    <ul>
      <li>Withdrawal Account Setup: GCash, Maya, GoTyme</li>
      <li>Withdrawal History</li>
      <li>Recharge Record</li>
      <li>Bills</li>
      <li>Change Password</li>
      <li>Language Selector</li>
      <li>Referral Link & Commissions</li>
      <li>Team Invites & Earnings</li>
    </ul>
    <p>Minimum withdrawal: ₱200 | Withdrawal fee: 35%</p>
    <button>Withdraw Funds</button>
  </section>

  <section id="about">
    <h3>About Míone Promotion</h3>
    <p>Míone Promotion is a platform where Filipinos invest in game promotions and earn daily income. Join a plan, promote popular Steam games, invite others, and earn commissions from your team!</p>
  </section>

  <section id="help">
    <h3>Need Help?</h3>
    <a href="https://t.me/eliseryy" target="_blank"><button>Message @eliseryy on Telegram</button></a>
  </section>

  <footer>
    <p>&copy; 2025 Míone Promotion</p>
    <div class="footer-links">
      <a href="#about">About</a>
      <a href="#">Terms & Conditions</a>
      <a href="#">Privacy Policy</a>
      <a href="#help">Contact</a>
    </div>
  </footer>
</body>
</html>
