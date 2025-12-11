---
layout: archive
title: "Quantitative Finance Projects"
permalink: /quant-projects/
author_profile: false
---

<a id="top"></a>

A dedicated collection of systems built for **high-frequency**, **medium-frequency**, and **low-frequency** quantitative trading.

---

<h2 style="text-align:center; font-weight:700;">Table of Contents</h2>

<div style="background:#f8f9fb; border-radius:12px; padding:30px; box-shadow:0 0 15px rgba(0,0,0,0.05); max-width:850px; margin:30px auto;">
  <ol style="list-style-type: decimal; line-height:1.9; font-size:1.05em;">
    <li><a href="#hft">High-Frequency Trading (HFT)</a></li>
    <li><a href="#mft">Medium-Frequency Trading (MFT)</a></li>
    <li><a href="#lft">Low-Frequency Trading (LFT)</a></li>
  </ol>
</div>

---

## <a id="hft"></a> 1. High-Frequency Trading (HFT)

<div class="proj-card">
  <h3>HFT_Trading_System</h3>
  <p>
    A <b>microsecond-level</b> low-latency trading engine designed for <b>real-time strategy discovery</b>.
  </p>
  🔗 <a href="https://github.com/kevinlmf/HFT_Trading_System" target="_blank">GitHub</a>
</div>

<p class="back-top"><a href="#top">⬆ Back to top</a></p>

---

## <a id="mft"></a> 2. Medium-Frequency Trading (MFT)

<div class="proj-card">
  <h3>Multi-Agent Option Pricing</h3>
  <p>
    A <b>time-series-driven</b> multi-agent framework for <b>option pricing</b> and volatility forecasting.
  </p>
  🔗 <a href="https://github.com/kevinlmf/Options_Pricing" target="_blank">GitHub</a>
</div>

<p class="back-top"><a href="#top">⬆ Back to top</a></p>

---

## <a id="lft"></a> 3. Low-Frequency Trading (LFT)

<div class="proj-card">
  <h3>Market-Adaptive Portfolio Optimization System</h3>
  <p>
    A <b>market-regime-aware</b> low-frequency trading framework integrating 
    <b>multi-factor modeling</b>, <b>SCAD-based estimation</b>, and 
    <b>risk-aware asset allocation</b>.  
    The system jointly performs factor extraction, high-dimensional estimation, 
    and portfolio optimization under dynamic market regimes.
  </p>
  🔗 <a href="https://github.com/kevinlmf/Portfolio_Optimization_system" target="_blank">GitHub</a><br>

  <small>
    Extensions: 
    <a href="https://github.com/kevinlmf/Factor-Mining" target="_blank">Factor Mining</a>,
    <a href="https://github.com/kevinlmf/Scad" target="_blank">SCAD Factor Estimation Package</a>
  </small>
</div>

<p class="back-top"><a href="#top">⬆ Back to top</a></p>



---

<a href="#top" class="fixed-top-btn">⬆ Back to top</a>

<style>
html, body { scroll-behavior: smooth; }
a { color: #1a73e8; }
h3 { color: #1a73e8; margin-top: 0; }
.proj-card {
  flex: 1;
  min-width: 300px;
  border: 1px solid #e0e0e0;
  border-radius: 12px;
  padding: 16px 18px;
  margin-top: 16px;
  box-shadow: 2px 2px 8px rgba(0,0,0,0.05);
  background: #fff;
}
.proj-card:hover {
  transform: translateY(-3px);
  box-shadow: 2px 4px 10px rgba(0,0,0,0.08);
}
.back-top { text-align: right; font-size: 0.9em; }
.fixed-top-btn {
  position: fixed; bottom: 25px; right: 30px;
  background: #1a73e8; color: white;
  padding: 8px 12px; border-radius: 8px;
  font-size: 0.9em; box-shadow: 2px 2px 6px rgba(0,0,0,0.2);
}
</style>
