---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: false
---

<a id="top"></a>

A curated portfolio of research and engineering systems across **Quantitative Finance** and **Machine Learning**, continuously evolving to bridge <b>theory</b> and <b>real-world intelligence</b> — where <b>algorithmic innovation</b> meets <b>practical impact</b>.

---

<h2 style="text-align:center; font-weight:700;">Table of Contents</h2>

<div style="background:#f8f9fb; border-radius:12px; padding:30px; box-shadow:0 0 15px rgba(0,0,0,0.05); max-width:850px; margin:30px auto;">
  <ol style="list-style-type: upper-roman; font-weight:600; color:#1a73e8; line-height:1.9; font-size:1.05em;">
    <li>
      <a href="#quant">Quantitative Trading Spectrum</a>
      <ol style="list-style-type: decimal; margin-top:10px; margin-left:25px;">
        <li><a href="#hft">High-Frequency Trading (HFT)</a></li>
        <li><a href="#mft">Medium-Frequency Trading (MFT)</a></li>
        <li><a href="#lft">Low-Frequency Trading (LFT)</a></li>
      </ol>
    </li>
    <li>
      <a href="#ml">Machine Learning Systems</a>
      <ol style="list-style-type: decimal; margin-top:10px; margin-left:25px;">
        <li><a href="#inventory">Inventory Optimizer</a></li>
        <li><a href="#health">Health Agent System</a></li>
        <li><a href="#memory">Agent Memory System</a></li>
      </ol>
    </li>
  </ol>
</div>

---

## <a id="quant"></a> I. Quantitative Finance Systems

Covering the **spectrum** of quantitative trading — including **high-frequency**, **medium-frequency**, and **low-frequency** systems.

---

### <a id="hft"></a> 1. High-Frequency Trading (HFT)

<div class="proj-card">
  <h3>HFT_Trading_System</h3>
  <p>
    A <b>low-latency trading platform</b> for <b>microsecond-level execution</b>, enabling real-time strategy discovery.
  </p>
  🔗 <a href="https://github.com/kevinlmf/HFT_Trading_System" target="_blank">GitHub</a>
</div>

<p class="back-top"><a href="#top">⬆ Back to top</a></p>

---

### <a id="mft"></a> 2. Medium-Frequency Trading (MFT)

<div class="proj-card">
  <h3>Multi-Agent Option Pricing</h3>
  <p>
    A <b>medium-frequency</b> framework for <b>option pricing</b> driven by time-series dynamics, exploring <b>multi-agent</b> interactions.
  </p>
  🔗 <a href="https://github.com/kevinlmf/Options_Pricing" target="_blank">GitHub</a><br>
  <small>
    See more detailed time-series forecasting methods in 
    <a href="https://github.com/kevinlmf/Time_Series_Forecasting" target="_blank">Time_Series_Forecasting</a>.
  </small>
</div>

<p class="back-top"><a href="#top">⬆ Back to top</a></p>

---

### <a id="lft"></a> 3. Low-Frequency Trading (LFT)

<div class="proj-card">
  <h3>Market-Adaptive Portfolio Optimization System</h3>
  <p>
    A <b>multi-factor portfolio optimizer</b> that adapts dynamically to <b>market regimes</b> and macroeconomic conditions.
  </p>
  🔗 <a href="https://github.com/kevinlmf/Portfolio_Optimization_system" target="_blank">GitHub</a><br>
  <small>
    Explore data-driven factor modeling in 
    <a href="https://github.com/kevinlmf/Factor-Mining" target="_blank">Factor-Mining</a>.
  </small>
</div>

<p class="back-top"><a href="#top">⬆ Back to top</a></p>

---

## <a id="ml"></a> II. Machine Learning Systems

Building systems that merge **machine learning**, **optimization**, and **control**, designed to operate under real-world uncertainty.

---

### <a id="inventory"></a> 1. Inventory Optimizer

<div class="proj-card">
  <h3>JAX Inventory Optimizer</h3>
  <p>
    A <b>JAX-based reinforcement learning optimizer</b> for <b>stochastic inventory control</b>, integrating differentiable simulation with model-based planning.
  </p>
  🔗 <a href="https://github.com/kevinlmf/Inventory_Optimizer_System" target="_blank">GitHub</a>
</div>

---

### <a id="health"></a> 2. Health Agent System

<div class="proj-card">
  <h3>Health Agent System</h3>
  <p>
    A <b>self-learning health agent</b> that automatically discovers <b>personalized reward functions</b> 
    and adapts through reinforcement learning and cognitive modeling.
  </p>
  🔗 <a href="https://github.com/kevinlmf/Health_Agent_System" target="_blank">GitHub</a><br>
  <small>
    See Psychology agent in 
    <a href="https://github.com/kevinlmf/Psychology_Agent" target="_blank">Psychology_Agent</a>, 
    and see Sport Agent in 
    <a href="https://github.com/kevinlmf/Sports_Agent" target="_blank">Sports_Agent</a>.
  </small>
</div>



---

### <a id="memory"></a> 3. Agent Memory

<div class="proj-card">
  <h3>Agent Memory System</h3>
  <p>
    A <b>cognitive memory core</b> that enables agents to <b>store long-term context</b>, 
    <b>infer latent states</b>, and <b>adapt across dynamic environments</b> — forming the backbone of 
    <b>reasoning, personalization, and multi-agent intelligence</b>.
  </p>
  🔗 <a href="https://github.com/kevinlmf/Agent_Memory" target="_blank">GitHub</a>
</div>

<p class="back-top"><a href="#top">⬆ Back to top</a></p>

---

<a href="#top" class="fixed-top-btn">⬆ Back to top</a>

<style>
html, body { scroll-behavior: smooth; }
a { color: #1a73e8; text-decoration: none; }
a:hover { text-decoration: underline; }
h3 { color: #1a73e8; margin-top: 0; }
p { line-height: 1.6; font-size: 0.95em; }

.proj-card {
  flex: 1;
  min-width: 300px;
  border: 1px solid #e0e0e0;
  border-radius: 12px;
  padding: 16px 18px;
  margin-top: 16px;
  box-shadow: 2px 2px 8px rgba(0,0,0,0.05);
  background: #fff;
  transition: transform 0.15s ease, box-shadow 0.15s ease;
}
.proj-card:hover {
  transform: translateY(-3px);
  box-shadow: 2px 4px 10px rgba(0,0,0,0.08);
}
.back-top {
  text-align: right;
  margin-top: 10px;
  font-size: 0.9em;
}
.back-top a {
  color: #666;
  text-decoration: none;
  transition: color 0.3s;
}
.back-top a:hover {
  color: #1a73e8;
}
.fixed-top-btn {
  position: fixed;
  bottom: 25px;
  right: 30px;
  background: #1a73e8;
  color: white;
  padding: 8px 12px;
  border-radius: 8px;
  font-size: 0.9em;
  box-shadow: 2px 2px 6px rgba(0,0,0,0.2);
  text-decoration: none;
  transition: background 0.3s;
}
.fixed-top-btn:hover { background: #0b59d0; }
</style>

