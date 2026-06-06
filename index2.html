<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Score Overlay</title>
<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@700;900&display=swap" rel="stylesheet">
<style>
* { margin: 0; padding: 0; box-sizing: border-box; }
body, html {
  background-color: transparent !important;
  background-image: none !important;
  overflow: hidden;
  font-family: 'Orbitron', sans-serif;
  padding: 10px;
}
.cyber-box {
  padding: 12px 16px;
  background: rgba(0, 10, 10, 0.88);
  border: 1px solid rgba(255, 0, 255, 0.15);
  border-left: 4px solid #f0f;
  clip-path: polygon(0 0, 100% 0, 100% 82%, 95% 100%, 0 100%);
  box-shadow: 0 0 8px rgba(255,0,255,0.1), inset 0 0 6px rgba(255,0,255,0.05);
  width: 100%;
}
.cyber-header { font-size: 10px; letter-spacing: 2px; color: #666; margin-bottom: 8px; font-weight: 700; }
.counter-container { display: flex; align-items: center; justify-content: center; gap: 16px; padding: 4px 0 6px; }
.score-segment { display: flex; flex-direction: column; align-items: center; gap: 4px; }
.score-num { font-size: 32px; font-weight: 900; line-height: 1; }
.num-wins { color: #0ff; text-shadow: 0 0 8px rgba(0,255,255,0.6); }
.num-losses { color: #f0f; text-shadow: 0 0 8px rgba(255,0,255,0.6); }
.score-label { font-size: 9px; letter-spacing: 1px; color: #a0a0a0; }
.score-divider { font-size: 24px; color: #444; padding-bottom: 14px; }
</style>
</head>
<body>
<div class="cyber-box">
  <div class="cyber-header">DATA_LOG // LIVE SCORE</div>
  <div class="counter-container">
    <div class="score-segment">
      <span class="score-num num-wins" id="win-val">00</span>
      <span class="score-label">WINS</span>
    </div>
    <div class="score-divider">:</div>
    <div class="score-segment">
      <span class="score-num num-losses" id="loss-val">00</span>
      <span class="score-label">LOSSES</span>
    </div>
  </div>
</div>

<script type="module">
import { initializeApp } from "https://www.gstatic.com/firebasejs/10.7.1/firebase-app.js";
import { getDatabase, ref, onValue } from "https://www.gstatic.com/firebasejs/10.7.1/firebase-database.js";

const app = initializeApp({
  databaseURL: "https://tallycounter-43685-default-rtdb.firebaseio.com"
});
const db = getDatabase(app);

function fmt(n) { return n < 10 ? '0' + n : '' + n; }

onValue(ref(db, 'score'), (snap) => {
  var data = snap.val() || { wins: 0, losses: 0 };
  document.getElementById('win-val').innerText = fmt(data.wins || 0);
  document.getElementById('loss-val').innerText = fmt(data.losses || 0);
});
</script>
</body>
</html>
