<!-- ========================================= -->
<!-- ✨ GITHUB PROFILE README — GALAXY EDITION ✨ -->
<!-- ========================================= -->

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ameni Hosni — Galaxy Profile</title>

<style>
/* ===== GLOBAL ===== */
body {
  margin: 0;
  height: 100vh;
  overflow-x: hidden;
  font-family: 'Segoe UI', sans-serif;
  color: #ffffff;
  background: radial-gradient(circle at 20% 20%, #0b001a, #000010);
}

/* ===== STARS LAYER ===== */
.stars, .twinkling, .nebula {
  position: fixed;
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  z-index: 0;
  overflow: hidden;
}

/* tiny stars created with multiple radial gradients */
.stars {
  background: radial-gradient(2px 2px at 20% 30%, #ffffff, transparent),
              radial-gradient(1px 1px at 80% 60%, #c8f0ff, transparent),
              radial-gradient(1px 1px at 50% 90%, #aaf, transparent),
              radial-gradient(1px 1px at 10% 70%, #9cf, transparent),
              radial-gradient(1px 1px at 90% 20%, #ccf, transparent);
  background-repeat: repeat;
  animation: moveStars 200s linear infinite;
  opacity: 0.4;
}

/* subtle twinkling animation */
.twinkling {
  background: radial-gradient(1px 1px at 10% 10%, rgba(255,255,255,0.8), transparent),
              radial-gradient(2px 2px at 70% 40%, rgba(255,255,255,0.6), transparent),
              radial-gradient(1px 1px at 90% 80%, rgba(255,255,255,0.7), transparent),
              radial-gradient(1px 1px at 30% 60%, rgba(255,255,255,0.8), transparent);
  background-repeat: repeat;
  animation: twinkle 4s ease-in-out infinite alternate;
  opacity: 0.5;
}

/* Nebula / Galaxy glow */
.nebula {
  background: radial-gradient(circle at 30% 50%, rgba(147,0,255,0.2), transparent 70%),
              radial-gradient(circle at 70% 60%, rgba(0,217,255,0.2), transparent 70%),
              radial-gradient(circle at 50% 80%, rgba(255,0,136,0.2), transparent 80%);
  animation: floatNebula 50s ease-in-out infinite alternate;
}

/* ===== TEXT AREA ===== */
.container {
  position: relative;
  z-index: 2;
  text-align: center;
  top: 35%;
  transform: translateY(-50%);
  padding: 0 20px;
}

h1 {
  font-size: 3em;
  color: #00e7ff;
  text-shadow: 0 0 10px #00e7ff, 0 0 30px #005577;
  animation: glow 3s ease-in-out infinite alternate;
}

p {
  font-size: 1.3em;
  opacity: 0.9;
}

.section-divider {
  border: 0;
  height: 2px;
  background: linear-gradient(to right, transparent, #00E7FF, transparent);
  margin: 40px 0;
}

/* ===== KEYFRAMES ===== */
@keyframes moveStars {
  from { background-position: 0 0; }
  to { background-position: 10000px 5000px; }
}

@keyframes twinkle {
  0%, 100% { opacity: 0.3; }
  50% { opacity: 0.8; }
}

@keyframes glow {
  from { text-shadow: 0 0 5px #00E7FF, 0 0 20px #00E7FF; }
  to { text-shadow: 0 0 20px #00E7FF, 0 0 40px #00E7FF; }
}

@keyframes floatNebula {
  from { transform: scale(1) translateY(0px); }
  to { transform: scale(1.2) translateY(-30px); }
}
</style>
</head>

<body>
  <div class="stars"></div>
  <div class="twinkling"></div>
  <div class="nebula"></div>

  <div class="container">
    <h1>✨ Ameni Hosni ✨</h1>
    <hr class="section-divider">
    <p>🌌 Welcome to my Galaxy — Data Science | AI | ML | Deep Learning 🌌</p>
  </div>
</body>
</html>
