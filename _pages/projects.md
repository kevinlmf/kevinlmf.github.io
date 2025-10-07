---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: false
---

<a id="top"></a>

A comprehensive collection of research and engineering projects spanning **quantitative finance** and **machine learning systems**.

---

<h2 style="text-align:center; font-weight:700;">Table of Contents</h2>

<div style="background:#f8f9fb; border-radius:12px; padding:30px; box-shadow:0 0 15px rgba(0,0,0,0.05); max-width:850px; margin:30px auto;">
  <!-- Table of Contents -->
  <ol style="list-style-type: upper-roman; font-weight:600; color:#1a73e8; line-height:1.9; font-size:1.05em;">
    <li><a href="#quant">Quantitative Finance Systems</a>
      <ol style="list-style-type: decimal; margin-top:10px; margin-left:25px;">
        <li><a href="#portfolio">Adaptive Portfolio Management</a></li>
        <li><a href="#hft">High-Frequency Trading (HFT)</a></li>
        <li><a href="#options">Option Pricing & Derivatives</a></li>
        <li><a href="#factor">Factor Mining System</a></li>
      </ol>
    </li>
    <li><a href="#ml">Machine Learning Systems</a>
      <ol style="list-style-type: decimal; margin-top:10px; margin-left:25px;">
        <li><a href="#or">Operations Research</a></li>
        <li><a href="#sports">Sports Analytics</a></li>
        <li><a href="#agent">Agent Systems</a>
          <ol style="list-style-type: lower-alpha; margin-top:10px; margin-left:25px;">
            <li><a href="#llm-agents">LLM-based Agents</a></li>
            <li><a href="#rl-agents">RL-based Agents</a></li>
          </ol>
        </li>
      </ol>
    </li>
  </ol>
</div>

---

## <a id="quant"></a> I. Quantitative Finance Systems

### <a id="portfolio"></a> 1. Adaptive Portfolio Management

<div class="proj-card">
  <h3>Adaptive Portfolio Optimization System</h3>
  <p>AI-driven optimizer adapting to market regimes, balancing Sharpe, CVaR, and diversification.</p>
  🔗 <a href="https://github.com/kevinlmf/Portfolio_Optimization_system" target="_blank">GitHub</a>
</div>

<p class="back-top"><a href="#top">⬆ Back to top</a></p>
---

### <a id="hft"></a> 2. High-Frequency Trading (HFT)

<div class="proj-card">
  <h3>HFT_CPP_JAX_System</h3>
  <p>C++ order execution engine with JAX-based RL training, supporting <b>microsecond-level latency</b>.</p>
  🔗 <a href="https://github.com/kevinlmf/HFT_Trading_System" target="_blank">GitHub</a>
</div>

<p class="back-top"><a href="#top">⬆ Back to top</a></p>
---

### <a id="options"></a> 3. Option Pricing & Derivatives

<div class="proj-card">
  <h3>Multi-Agent Option Pricing</h3>
  <p>Simulation of hedgers, issuers, and arbitrageurs to explain deviations via behavioral dynamics.</p>
  🔗 <a href="https://github.com/kevinlmf/MultiAgent_OptionPricing" target="_blank">GitHub</a>
</div>

<p class="back-top"><a href="#top">⬆ Back to top</a></p>
---

### <a id="factor"></a> 4. Factor Mining System

<div class="proj-card">
  <h3>Factor Mining System</h3>
  <p>Comprehensive library for factor generation, IC tests, and ranking.</p>
  🔗 <a href="https://github.com/kevinlmf/AlphaFactor" target="_blank">GitHub</a>
</div>

<p class="back-top"><a href="#top">⬆ Back to top</a></p>
---

## <a id="ml"></a> II. Machine Learning Systems

### <a id="or"></a> 1. Operations Research

<div class="proj-card">
  <h3>JAX Inventory Optimizer</h3>
  <p>High-performance RL-based optimizer for stochastic inventory management and EOQ systems.</p>
  🔗 <a href="https://github.com/kevinlmf/JAX_Inventory_Optimizer" target="_blank">GitHub</a>
</div>

<p class="back-top"><a href="#top">⬆ Back to top</a></p>
---

### <a id="sports"></a> 2. Sports Analytics

<div class="proj-card">
  <h3>Sports Injury Risk</h3>
  <p>ML models for athlete injury prediction based on physiological metrics.</p>
  🔗 <a href="https://github.com/kevinlmf/Sports_Injury_Prediction" target="_blank">GitHub</a>
</div>

<p class="back-top"><a href="#top">⬆ Back to top</a></p>
---

### <a id="agent"></a> 3. Agent Systems

#### <a id="llm-agents"></a> (a) LLM-based Agents

<div class="proj-card special">
  <h3>Coming Soon: LLM-based Agent Framework</h3>
  <p>Language-model-driven agent system for reasoning, tool use, and multi-agent orchestration — integrating LangChain, CrewAI, and AutoGen with real-time data workflows.</p>
  🔗 <em>To be released</em>
</div>

<p class="back-top"><a href="#top">⬆ Back to top</a></p>
---

#### <a id="rl-agents"></a> (b) RL-based Agents

<div class="proj-row">
  <div class="proj-card">
    <h3>AI Psychology Assistant</h3>
    <p>Reinforcement learning–aligned conversational agent for behavioral reasoning, dialogue management, and emotional modeling.</p>
    🔗 <a href="https://github.com/kevinlmf/AI_psychology_assistant" target="_blank">GitHub</a>
  </div>

  <div class="proj-card">
    <h3>Multi-Agent Poker System</h3>
    <p>Safe multi-agent reinforcement learning framework for strategic poker decision-making and equilibrium exploration.</p>
    🔗 <a href="https://github.com/kevinlmf/MultiAgent_Poker" target="_blank">GitHub</a>
  </div>
</div>

<p class="back-top"><a href="#top">⬆ Back to top</a></p>
---

<style>
html { scroll-behavior: smooth; }
a { color: #1a73e8; text-decoration: none; }
a:hover { text-decoration: underline; }
h3 { color: #1a73e8; margin-top: 0; }
p { line-height: 1.6; font-size: 0.95em; }

.proj-card {
  flex: 1;
  min-width: 300px;
  border: 1px solid #e0e0e0;
  border-radius: 10px;
  padding: 15px;
  margin-top: 15px;
  box-shadow: 2px 2px 6px rgba(0,0,0,0.05);
  background: #fff;
}

.proj-row {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
}

.proj-card.special {
  border: 1px dashed #b0c4de;
  background: #fafcff;
}

.back-top {
  text-align: right;
  margin-top: 10px;
  font-size: 0.9em;
}
.back-top a {
  color: #666;
}
.back-top a:hover {
  color: #1a73e8;
}
</style>
