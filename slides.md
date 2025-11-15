---
theme: default
background: https://images.unsplash.com/photo-1451187580459-43490279c0fa?w=1920
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## Heckscher-Ohlin Model
  International Trade Theory - Chapter 5
drawings:
  persist: false
transition: slide-left
title: Heckscher-Ohlin Model
mdc: true
---

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap');

* {
  font-family: 'Inter', sans-serif;
   user-select: text !important;
  -webkit-user-select: text !important;
  -moz-user-select: text !important;
  -ms-user-select: text !important;
}

.slidev-layout {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}

h1 {
  background: linear-gradient(120deg, #fdfbfb 0%, #ebedee 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-weight: 700;
  text-shadow: 0 0 30px rgba(255,255,255,0.3);
}

.text-gradient {
  background: linear-gradient(90deg, #ffd89b 0%, #19547b 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-weight: 600;
}

.glass-effect {
  background: rgba(255, 255, 255, 0.1);
  backdrop-filter: blur(10px);
  border-radius: 15px;
  border: 1px solid rgba(255, 255, 255, 0.2);
  padding: 2rem;
  box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37);
}

@keyframes fadeInUp {
  from {
    opacity: 0;
    transform: translateY(30px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

@keyframes pulse {
  0%, 100% {
    transform: scale(1);
  }
  50% {
    transform: scale(1.05);
  }
}

@keyframes float {
  0%, 100% {
    transform: translateY(0px);
  }
  50% {
    transform: translateY(-20px);
  }
}

@keyframes glow {
  0%, 100% {
    box-shadow: 0 0 20px rgba(255, 255, 255, 0.3);
  }
  50% {
    box-shadow: 0 0 40px rgba(255, 255, 255, 0.6);
  }
}

.fadeInUp {
  animation: fadeInUp 0.8s cubic-bezier(0.4, 0, 0.2, 1);
}

.pulse {
  animation: pulse 2s cubic-bezier(0.4, 0, 0.2, 1) infinite;
}

.float {
  animation: float 3s ease-in-out infinite;
}

.glow {
  animation: glow 2s ease-in-out infinite;
}

.hover-lift {
  transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
}

.hover-lift:hover {
  transform: translateY(-10px);
  box-shadow: 0 20px 40px rgba(0, 0, 0, 0.3);
}

.neon-text {
  text-shadow: 0 0 10px #fff, 0 0 20px #fff, 0 0 30px #fff, 0 0 40px #00ff88;
}

.card-3d {
  transition: all 0.5s cubic-bezier(0.4, 0, 0.2, 1);
  transform-style: preserve-3d;
}

.card-3d:hover {
  transform: rotateY(5deg) rotateX(5deg) scale(1.05);
}
</style>

# Resources and Trade
## <span class="neon-text">The Heckscher-Ohlin Model</span>

<div class="pt-12 fadeInUp">
  <span class="text-xl opacity-80">
    📚 International Economics: Theory and Policy
  </span>
</div>

<div class="abs-br m-6 flex gap-2 fadeInUp">
  <span class="text-sm opacity-50">Chapter 5 • Theory and Applications</span>
</div>

---
transition: fade-out
layout: center
class: text-center
---

<div class="glass-effect fadeInUp">

# 🕰️ Trade Theory Timeline

<div class="grid grid-cols-1 gap-6 mt-8 text-left">

<div class="hover-lift p-6 bg-gradient-to-r from-purple-500 to-pink-500 rounded-xl">
<h3 class="text-2xl font-bold mb-2">👥 The Architects</h3>
<p class="text-lg opacity-90">Developed by Swedish economists <strong>Eli Heckscher</strong> and <strong>Bertil Ohlin</strong></p>
<p class="text-sm mt-2 opacity-75">🏆 Ohlin received the Nobel Prize in Economics in 1977</p>
</div>

<div class="hover-lift p-6 bg-gradient-to-r from-blue-500 to-cyan-500 rounded-xl">
<h3 class="text-2xl font-bold mb-2">🎯 The Concept</h3>
<p class="text-lg opacity-90">Also known as the <strong>Factor-Proportions Theory</strong></p>
<p class="text-sm mt-2 opacity-75">Emphasizes the interplay between factor availability and usage proportions</p>
</div>

</div>

</div>

---
transition: slide-up
---

<div class="glass-effect p-8 fadeInUp">

# 🎯 Why Does Trade Occur?

<div class="grid grid-cols-2 gap-8 mt-8">

<div class="card-3d hover-lift p-6 bg-gradient-to-br from-orange-400 to-red-500 rounded-xl">
<div class="text-4xl mb-4">🌲</div>
<h3 class="text-xl font-bold mb-3">Real World Example</h3>
<p class="opacity-90">Canada exports forest products to the U.S. not because of productivity differences, but because of <strong>more forested land per capita</strong></p>
</div>

<div class="card-3d hover-lift p-6 bg-gradient-to-br from-green-400 to-blue-500 rounded-xl">
<div class="text-4xl mb-4">💡</div>
<h3 class="text-xl font-bold mb-3">Key Insight</h3>
<p class="opacity-90">Trade is driven by differences in <strong>resources</strong> across countries, not just labor productivity</p>
</div>

</div>

<div class="mt-8 p-6 bg-gradient-to-r from-purple-600 to-pink-600 rounded-xl pulse">
<p class="text-xl text-center">
⚡ <strong>Trade occurs due to differences in factor endowments across countries</strong>
</p>
</div>

</div>

---
layout: two-cols
---

<div class="pr-4">

# 🏗️ Model Assumptions

<div class="glass-effect p-6 mt-4 fadeInUp">

### 🌍 Countries
<div class="p-3 bg-blue-500/20 rounded-lg mb-3">
Two countries: Home and Foreign
</div>

### 📦 Goods
<div class="p-3 bg-purple-500/20 rounded-lg mb-3">
Two goods: Cloth and Food
</div>

### ⚙️ Factors
<div class="p-3 bg-green-500/20 rounded-lg mb-3">
Two factors: Labor (L) and Capital (K)
</div>

</div>

</div>

::right::

<div class="pl-4">

<div class="glass-effect p-6 mt-4 fadeInUp" style="animation-delay: 0.2s;">

### 🔄 Key Features

<div class="space-y-4 mt-4">

<div class="hover-lift p-4 bg-gradient-to-r from-yellow-400 to-orange-500 rounded-lg">
<strong>✨ Factor Mix Varies</strong><br/>
Different goods use L and K in different proportions
</div>

<div class="hover-lift p-4 bg-gradient-to-r from-pink-400 to-red-500 rounded-lg">
<strong>🔒 Supply is Constant</strong><br/>
But varies across countries
</div>

<div class="hover-lift p-4 bg-gradient-to-r from-blue-400 to-purple-500 rounded-lg">
<strong>🏃 Long-Run Mobility</strong><br/>
Both L and K can move between sectors
</div>

</div>

</div>

</div>

---
transition: fade
---

<div class="glass-effect p-8 fadeInUp">

# 📊 Production Possibilities

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="p-6 bg-gradient-to-br from-indigo-500 to-purple-600 rounded-xl hover-lift">
<h3 class="text-2xl font-bold mb-4">🎨 Why PPF is Curved?</h3>
<p class="text-lg mb-4">With multiple factors, opportunity cost is <strong>not constant</strong></p>
<div class="p-4 bg-white/10 rounded-lg">
<p class="text-sm opacity-90">When resources shift to one good, marginal productivity ↓ so opportunity cost ↑</p>
</div>
</div>

<div class="p-6 bg-gradient-to-br from-blue-500 to-cyan-600 rounded-xl hover-lift">
<h3 class="text-2xl font-bold mb-4">⚖️ Resource Constraints</h3>
<div class="space-y-3">
<div class="p-3 bg-white/10 rounded-lg">

**Capital:** $a_{KC}Q_C + a_{KF}Q_F \leq K$

</div>
<div class="p-3 bg-white/10 rounded-lg">

**Labor:** $a_{LC}Q_C + a_{LF}Q_F \leq L$

</div>
</div>
</div>

</div>

<div class="mt-6 p-6 bg-gradient-to-r from-green-500 to-teal-500 rounded-xl text-center pulse">
<p class="text-xl">
💎 <strong>Production must satisfy BOTH constraints simultaneously</strong>
</p>
</div>

</div>

---
layout: center
---

<div class="glass-effect p-10 fadeInUp text-center">

# 🧮 Numerical Example

<div class="grid grid-cols-2 gap-8 mt-10">

<div class="card-3d p-8 bg-gradient-to-br from-pink-500 to-rose-600 rounded-2xl">
<h3 class="text-3xl font-bold mb-6">👕 Cloth Production</h3>
<div class="space-y-4 text-left">
<p class="text-lg">Capital per yard: <span class="text-2xl font-bold">2</span></p>
<p class="text-lg">Labor per yard: <span class="text-2xl font-bold">2</span></p>
</div>
</div>

<div class="card-3d p-8 bg-gradient-to-br from-green-500 to-emerald-600 rounded-2xl">
<h3 class="text-3xl font-bold mb-6">🌾 Food Production</h3>
<div class="space-y-4 text-left">
<p class="text-lg">Capital per calorie: <span class="text-2xl font-bold">3</span></p>
<p class="text-lg">Labor per calorie: <span class="text-2xl font-bold">1</span></p>
</div>
</div>

</div>

<div class="mt-10 grid grid-cols-2 gap-6">
<div class="p-6 bg-yellow-500/30 rounded-xl glow">
<p class="text-2xl font-bold">K = 3,000</p>
<p class="opacity-80">Total Capital</p>
</div>
<div class="p-6 bg-blue-500/30 rounded-xl glow">
<p class="text-2xl font-bold">L = 2,000</p>
<p class="opacity-80">Total Labor</p>
</div>
</div>

</div>

---
transition: slide-left
---

<div class="glass-effect p-8 fadeInUp">

# 📈 Production Constraints

<div class="mt-6 space-y-6">

<div class="hover-lift p-6 bg-gradient-to-r from-purple-600 to-pink-600 rounded-xl">
<h3 class="text-2xl font-bold mb-3">💎 Capital Constraint</h3>
<div class="text-3xl font-mono p-4 bg-black/30 rounded-lg">
2Q_C + 3Q_F ≤ 3,000
</div>
</div>

<div class="hover-lift p-6 bg-gradient-to-r from-blue-600 to-cyan-600 rounded-xl">
<h3 class="text-2xl font-bold mb-3">👷 Labor Constraint</h3>
<div class="text-3xl font-mono p-4 bg-black/30 rounded-lg">
2Q_C + Q_F ≤ 2,000
</div>
</div>

<div class="grid grid-cols-3 gap-4 mt-8">
<div class="card-3d p-6 bg-green-500/30 rounded-xl text-center">
<p class="text-sm opacity-80 mb-2">Max Food</p>
<p class="text-4xl font-bold">1,000</p>
<p class="text-xs mt-2 opacity-60">(uses all capital)</p>
</div>
<div class="card-3d p-6 bg-yellow-500/30 rounded-xl text-center">
<p class="text-sm opacity-80 mb-2">Max Cloth</p>
<p class="text-4xl font-bold">1,000</p>
<p class="text-xs mt-2 opacity-60">(uses all labor)</p>
</div>
<div class="card-3d p-6 bg-red-500/30 rounded-xl text-center pulse">
<p class="text-sm opacity-80 mb-2">Optimal Mix</p>
<p class="text-2xl font-bold">750 + 500</p>
<p class="text-xs mt-2 opacity-60">(cloth + food)</p>
</div>
</div>

</div>

</div>

---
layout: two-cols
---

<div class="pr-4">

# 🔄 Comparing PPF Models

<div class="space-y-4 mt-6">

<div class="glass-effect p-5 fadeInUp hover-lift">
<h3 class="text-xl font-bold mb-3 text-gradient">📐 Ricardian Model</h3>
<ul class="space-y-2 text-sm opacity-90">
<li>✓ Only labor factor</li>
<li>✓ Constant supply</li>
<li>✓ Productivity varies by technology</li>
<li>✓ <strong>Straight-line PPF</strong></li>
</ul>
</div>

<div class="glass-effect p-5 fadeInUp hover-lift" style="animation-delay: 0.1s;">
<h3 class="text-xl font-bold mb-3 text-gradient">⚙️ Specific Factors</h3>
<ul class="space-y-2 text-sm opacity-90">
<li>✓ Labor mobile between sectors</li>
<li>✓ Capital/Land sector-specific</li>
<li>✓ $L = L_C + L_F$</li>
<li>✓ <strong>Curved PPF</strong></li>
</ul>
</div>

</div>

</div>

::right::

<div class="pl-4">

<div class="glass-effect p-5 fadeInUp hover-lift" style="animation-delay: 0.2s;">
<h3 class="text-xl font-bold mb-3 text-gradient">🌟 Heckscher-Ohlin</h3>
<ul class="space-y-2 text-sm opacity-90">
<li>✓ Multiple mobile factors (L & K)</li>
<li>✓ Factor substitution possible</li>
<li>✓ Different factor intensities</li>
<li>✓ <strong>Smooth curved PPF</strong></li>
</ul>
</div>

<div class="mt-6 p-6 bg-gradient-to-br from-orange-500 to-red-600 rounded-xl pulse">
<h4 class="text-lg font-bold mb-3">🎯 Key Difference</h4>
<p class="text-sm">
Opportunity cost <strong>increases</strong> as we produce more of one good because marginal productivity of resources <strong>decreases</strong>
</p>
</div>

<div class="mt-4 p-6 bg-gradient-to-br from-teal-500 to-blue-600 rounded-xl float">
<h4 class="text-lg font-bold mb-3">💫 Factor Substitution</h4>
<p class="text-sm">
When capital can substitute for labor (and vice versa), PPF becomes <strong>smooth and bowed</strong>
</p>
</div>

</div>

---
transition: fade
---

<div class="glass-effect p-8 fadeInUp">

# 💰 Optimum Production

<div class="grid grid-cols-2 gap-6 mt-6">

<div class="p-6 bg-gradient-to-br from-violet-500 to-purple-600 rounded-xl hover-lift">
<h3 class="text-2xl font-bold mb-4">📊 Isovalue Line</h3>
<p class="mb-4">Line representing constant value of production:</p>
<div class="p-4 bg-black/30 rounded-lg text-center">
<p class="text-2xl font-mono">V = P_C × Q_C + P_F × Q_F</p>
</div>
<p class="mt-4 text-sm opacity-80">Slope = -P_C / P_F</p>
</div>

<div class="p-6 bg-gradient-to-br from-cyan-500 to-blue-600 rounded-xl hover-lift">
<h3 class="text-2xl font-bold mb-4">🎯 Maximization</h3>
<p class="mb-4">Economy produces at point that:</p>
<ul class="space-y-3 text-sm">
<li class="p-3 bg-white/10 rounded-lg">✓ Maximizes production value</li>
<li class="p-3 bg-white/10 rounded-lg">✓ Touches highest isovalue line</li>
<li class="p-3 bg-white/10 rounded-lg">✓ PPF tangent to isovalue line</li>
</ul>
</div>

</div>

<div class="mt-6 p-6 bg-gradient-to-r from-pink-500 to-rose-500 rounded-xl text-center pulse">
<p class="text-xl">
⚖️ <strong>At optimum: Opportunity Cost = Relative Price</strong>
</p>
<p class="text-sm mt-2 opacity-80">Slope of PPF = Slope of Isovalue Line</p>
</div>

</div>

---
layout: center
---

<div class="glass-effect p-10 fadeInUp text-center">

# 🏭 Factor Intensity

<div class="mt-8 space-y-6">

<div class="card-3d p-8 bg-gradient-to-r from-blue-500 to-indigo-600 rounded-2xl">
<h3 class="text-3xl font-bold mb-4">📐 Definition</h3>
<p class="text-xl mb-6">A good is <strong>labor-intensive</strong> if it uses more labor relative to capital</p>
<div class="text-3xl font-mono p-4 bg-black/30 rounded-lg">
L_C / K_C > L_F / K_F
</div>
</div>

<div class="grid grid-cols-2 gap-6">

<div class="hover-lift p-8 bg-gradient-to-br from-purple-500 to-pink-600 rounded-2xl">
<div class="text-5xl mb-4">👕</div>
<h4 class="text-2xl font-bold mb-3">Cloth</h4>
<p class="text-lg"><strong>Labor-Intensive</strong></p>
<p class="text-sm opacity-80 mt-2">Higher L/K ratio</p>
</div>

<div class="hover-lift p-8 bg-gradient-to-br from-green-500 to-teal-600 rounded-2xl">
<div class="text-5xl mb-4">🌾</div>
<h4 class="text-2xl font-bold mb-3">Food</h4>
<p class="text-lg"><strong>Capital-Intensive</strong></p>
<p class="text-sm opacity-80 mt-2">Lower L/K ratio</p>
</div>

</div>

</div>

</div>

---
transition: slide-up
---

<div class="glass-effect p-8 fadeInUp">

# 📊 Relative Factor Demand

<div class="mt-6 p-6 bg-gradient-to-br from-indigo-600 to-purple-700 rounded-xl">

<h3 class="text-2xl font-bold mb-4">📈 Key Relationship</h3>

<div class="grid grid-cols-2 gap-6 mt-4">

<div class="p-5 bg-white/10 rounded-lg">
<p class="text-lg mb-3">When <strong>w/r increases</strong>:</p>
<ul class="space-y-2 text-sm opacity-90">
<li>↓ Use less labor</li>
<li>↑ Use more capital</li>
<li>🔄 Applies to BOTH sectors</li>
</ul>
</div>

<div class="p-5 bg-white/10 rounded-lg">
<p class="text-lg mb-3">At any wage-rental ratio:</p>
<ul class="space-y-2 text-sm opacity-90">
<li>👕 Cloth uses higher L/K</li>
<li>🌾 Food uses lower L/K</li>
<li>📐 Intensity persists</li>
</ul>
</div>

</div>

</div>

<div class="mt-6 p-6 bg-gradient-to-r from-yellow-500 to-orange-500 rounded-xl text-center pulse">
<p class="text-xl">
💡 <strong>Factor prices influence input choices in both sectors</strong>
</p>
</div>

</div>

---
layout: center
class: text-center
---

<div class="glass-effect p-12 fadeInUp">

# 🏆 Stolper-Samuelson Theorem

<div class="mt-8 p-8 bg-gradient-to-r from-red-500 via-pink-500 to-purple-600 rounded-2xl glow">
<p class="text-2xl font-bold mb-6">
⚡ The Core Principle
</p>
<p class="text-xl leading-relaxed">
If the <strong>relative price of a good increases</strong>, then the <strong>real wage/rental rate</strong> of the factor used <strong>intensively</strong> in that good <strong>increases</strong>, while the other factor's return <strong>decreases</strong>
</p>
</div>

<div class="grid grid-cols-2 gap-6 mt-10">

<div class="card-3d p-8 bg-gradient-to-br from-blue-500 to-cyan-600 rounded-xl">
<h4 class="text-2xl font-bold mb-4">👕 If P_C ↑</h4>
<div class="space-y-3">
<p class="text-lg">✓ Wage (w) increases</p>
<p class="text-lg">✗ Rental rate (r) decreases</p>
<p class="text-sm opacity-75 mt-4">(Cloth is labor-intensive)</p>
</div>
</div>

<div class="card-3d p-8 bg-gradient-to-br from-green-500 to-teal-600 rounded-xl">
<h4 class="text-2xl font-bold mb-4">🌾 If P_F ↑</h4>
<div class="space-y-3">
<p class="text-lg">✓ Rental rate (r) increases</p>
<p class="text-lg">✗ Wage (w) decreases</p>
<p class="text-sm opacity-75 mt-4">(Food is capital-intensive)</p>
</div>
</div>

</div>

<div class="mt-8 text-sm opacity-75">
📚 Wolfgang Stolper & Paul Samuelson (1941) • "Protection and Real Wages"
</div>

</div>

---
transition: fade
---

<div class="glass-effect p-8 fadeInUp">

# 💸 Income Distribution Effects

<div class="mt-6 space-y-6">

<div class="hover-lift p-6 bg-gradient-to-r from-orange-500 to-red-600 rounded-xl">
<h3 class="text-2xl font-bold mb-4">🌾 When Food Price Increases</h3>
<div class="grid grid-cols-2 gap-4">
<div class="p-4 bg-white/10 rounded-lg">
<p class="text-lg font-bold mb-2">👷 Workers</p>
<p class="text-sm">✓ Real wages increase</p>
<p class="text-sm">✓ Purchasing power ↑</p>
</div>
<div class="p-4 bg-white/10 rounded-lg">
<p class="text-lg font-bold mb-2">🏭 Capital Owners</p>
<p class="text-sm">✗ Real rents fall</p>
<p class="text-sm">✗ Purchasing power ↓</p>
</div>
</div>
</div>

<div class="hover-lift p-6 bg-gradient-to-r from-purple-500 to-pink-600 rounded-xl">
<h3 class="text-2xl font-bold mb-4">👕 When Cloth Price Rises</h3>
<div class="grid grid-cols-2 gap-4">
<div class="p-4 bg-white/10 rounded-lg">
<p class="text-lg font-bold mb-2">🏭 Capital Owners</p>
<p class="text-sm">✓ Real rents increase</p>
<p class="text-sm">✓ Purchasing power ↑</p>
</div>
<div class="p-4 bg-white/10 rounded-lg">
<p class="text-lg font-bold mb-2">👷 Workers</p>
<p class="text-sm">✗ Real wages fall</p>
<p class="text-sm">✗ Purchasing power ↓</p>
</div>
</div>
</div>

<div class="p-6 bg-gradient-to-r from-blue-500 to-cyan-500 rounded-xl text-center pulse">
<p class="text-xl">
⚖️ <strong>Price changes redistribute income between factors</strong>
</p>
</div>

</div>

</div>

---
layout: center
class: text-center
---

<div class="glass-effect p-12 fadeInUp">

# 🔄 Rybczynski Theorem

<div class="mt-8 p-8 bg-gradient-to-r from-green-500 via-teal-500 to-blue-600 rounded-2xl glow">
<p class="text-2xl font-bold mb-6">
⚡ Resource-Output Relationship
</p>
<p class="text-xl leading-relaxed">
If <strong>output prices remain constant</strong> and a <strong>factor increases</strong>, then the supply of the good using that factor <strong>intensively increases</strong>, while the other good's supply <strong>decreases</strong>
</p>
</div>

<div class="grid grid-cols-2 gap-6 mt-10">

<div class="card-3d p-8 bg-gradient-to-br from-purple-500 to-pink-600 rounded-xl">
<h4 class="text-2xl font-bold mb-4">👷 If Labor ↑</h4>
<div class="space-y-3">
<p class="text-lg">✓ Cloth production ↑</p>
<p class="text-lg">✗ Food production ↓</p>
<p class="text-sm opacity-75 mt-4">(Cloth is labor-intensive)</p>
</div>
</div>

<div class="card-3d p-8 bg-gradient-to-br from-yellow-500 to-orange-600 rounded-xl">
<h4 class="text-2xl font-bold mb-4">🏭 If Capital ↑</h4>
<div class="space-y-3">
<p class="text-lg">✓ Food production ↑</p>
<p class="text-lg">✗ Cloth production ↓</p>
<p class="text-sm opacity-75 mt-4">(Food is capital-intensive)</p>
</div>
</div>

</div>

<div class="mt-8 text-sm opacity-75">
📚 T.M. Rybczynski (1955) • "Factor Endowments and Relative Commodity Prices"
</div>

</div>

---
transition: slide-left
---

<div class="glass-effect p-8 fadeInUp">

# 🌍 Trade Pattern Determinants

<div class="mt-6 space-y-6">

<div class="hover-lift p-6 bg-gradient-to-r from-indigo-500 to-purple-600 rounded-xl">
<h3 class="text-2xl font-bold mb-4">🤝 Common Ground</h3>

<div class="grid grid-cols-2 gap-4">
<div class="p-4 bg-white/10 rounded-lg">
<p class="text-lg font-bold mb-2">🔧 Technology</p>
<p class="text-sm">Both countries have the SAME technology</p>
</div>
<div class="p-4 bg-white/10 rounded-lg">
<p class="text-lg font-bold mb-2">🎯 Preferences</p>
<p class="text-sm">Both countries have the SAME tastes</p>
</div>
</div>
</div>

<div class="hover-lift p-6 bg-gradient-to-r from-pink-500 to-rose-600 rounded-xl">
<h3 class="text-2xl font-bold mb-4">⚡ The Key Difference</h3>
<div class="p-4 bg-white/10 rounded-lg text-center">
<p class="text-2xl font-bold mb-2">FACTOR ENDOWMENTS</p>
<p class="text-lg">Home has higher L/K ratio than Foreign</p>
<p class="text-sm opacity-75 mt-2">This determines comparative advantage!</p>
</div>
</div>

<div class="grid grid-cols-2 gap-6">
<div class="card-3d p-6 bg-gradient-to-br from-blue-500 to-cyan-600 rounded-xl">
<h4 class="text-xl font-bold mb-3">🏠 Home Country</h4>
<p class="text-lg mb-2">Labor abundant → L/K high</p>
<p class="text-sm opacity-80">Comparative advantage in cloth (labor-intensive)</p>
</div>
<div class="card-3d p-6 bg-gradient-to-br from-green-500 to-teal-600 rounded-xl">
<h4 class="text-xl font-bold mb-3">🌐 Foreign Country</h4>
<p class="text-lg mb-2">Capital abundant → K/L high</p>
<p class="text-sm opacity-80">Comparative advantage in food (capital-intensive)</p>
</div>
</div>

</div>

</div>

---
layout: center
---

<div class="glass-effect p-10 fadeInUp text-center">

# 📈 Relative Supply Curves

<div class="mt-8 p-8 bg-gradient-to-br from-violet-600 to-purple-700 rounded-2xl">
<h3 class="text-2xl font-bold mb-6">🌟 Before Trade</h3>
<div class="grid grid-cols-2 gap-8">
<div class="p-6 bg-white/10 rounded-xl">
<p class="text-4xl mb-3">🏠</p>
<p class="text-xl font-bold mb-2">Home</p>
<p class="text-sm opacity-90">Equilibrium at Point 1</p>
<p class="text-sm opacity-75">Lower relative price of cloth</p>
</div>
<div class="p-6 bg-white/10 rounded-xl">
<p class="text-4xl mb-3">🌐</p>
<p class="text-xl font-bold mb-2">Foreign</p>
<p class="text-sm opacity-90">Equilibrium at Point 3</p>
<p class="text-sm opacity-75">Higher relative price of cloth</p>
</div>
</div>
</div>

<div class="mt-6 p-8 bg-gradient-to-r from-green-500 to-teal-600 rounded-2xl pulse">
<h3 class="text-2xl font-bold mb-4">🔄 With Trade</h3>
<p class="text-xl mb-3">World price converges to Point 2</p>
<p class="text-lg opacity-90">Between the two pretrade prices</p>
</div>

<div class="mt-6 text-sm opacity-75">
💡 Home's relative supply curve lies to the RIGHT of Foreign's
</div>

</div>

---
transition: fade
---

<div class="glass-effect p-8 fadeInUp">

# 🔄 Price Convergence Effects

<div class="mt-6 space-y-6">

<div class="grid grid-cols-2 gap-6">

<div class="hover-lift p-6 bg-gradient-to-br from-blue-500 to-indigo-600 rounded-xl">
<h3 class="text-2xl font-bold mb-4">🏠 Home (Labor Abundant)</h3>
<div class="space-y-3">
<div class="p-3 bg-white/10 rounded-lg">
<p class="font-bold">📈 Price Change</p>
<p class="text-sm">Relative price of cloth RISES</p>
</div>
<div class="p-3 bg-white/10 rounded-lg">
<p class="font-bold">🏭 Production</p>
<p class="text-sm">Cloth production ↑, Food ↓</p>
</div>
<div class="p-3 bg-white/10 rounded-lg">
<p class="font-bold">🛒 Consumption</p>
<p class="text-sm">Cloth consumption ↓, Food ↑</p>
</div>
<div class="p-3 bg-green-500/30 rounded-lg text-center pulse">
<p class="font-bold">→ EXPORTS CLOTH 👕</p>
<p class="text-sm">IMPORTS FOOD 🌾</p>
</div>
</div>
</div>

<div class="hover-lift p-6 bg-gradient-to-br from-purple-500 to-pink-600 rounded-xl">
<h3 class="text-2xl font-bold mb-4">🌐 Foreign (Capital Abundant)</h3>
<div class="space-y-3">
<div class="p-3 bg-white/10 rounded-lg">
<p class="font-bold">📉 Price Change</p>
<p class="text-sm">Relative price of cloth FALLS</p>
</div>
<div class="p-3 bg-white/10 rounded-lg">
<p class="font-bold">🏭 Production</p>
<p class="text-sm">Food production ↑, Cloth ↓</p>
</div>
<div class="p-3 bg-white/10 rounded-lg">
<p class="font-bold">🛒 Consumption</p>
<p class="text-sm">Food consumption ↓, Cloth ↑</p>
</div>
<div class="p-3 bg-green-500/30 rounded-lg text-center pulse">
<p class="font-bold">→ EXPORTS FOOD 🌾</p>
<p class="text-sm">IMPORTS CLOTH 👕</p>
</div>
</div>
</div>

</div>

</div>

</div>

---
layout: center
class: text-center
---

<div class="glass-effect p-12 fadeInUp">

# 🏆 The Heckscher-Ohlin Theorem

<div class="mt-8 p-10 bg-gradient-to-r from-yellow-500 via-orange-500 to-red-600 rounded-2xl glow">
<p class="text-3xl font-bold mb-8">
🌟 The Core Prediction
</p>
<p class="text-2xl leading-relaxed">
A country that is <strong>abundant in a factor</strong> exports the good whose production is <strong>intensive in that factor</strong>
</p>
</div>

<div class="grid grid-cols-2 gap-8 mt-10">

<div class="card-3d p-10 bg-gradient-to-br from-blue-600 to-cyan-700 rounded-2xl">
<div class="text-6xl mb-4">🏠</div>
<h4 class="text-3xl font-bold mb-4">Home</h4>
<div class="space-y-3 text-left">
<p class="text-lg">✓ Labor abundant</p>
<p class="text-lg">✓ Cloth is labor-intensive</p>
<p class="text-2xl font-bold mt-4 text-center">→ Exports Cloth 👕</p>
</div>
</div>

<div class="card-3d p-10 bg-gradient-to-br from-green-600 to-teal-700 rounded-2xl">
<div class="text-6xl mb-4">🌐</div>
<h4 class="text-3xl font-bold mb-4">Foreign</h4>
<div class="space-y-3 text-left">
<p class="text-lg">✓ Capital abundant</p>
<p class="text-lg">✓ Food is capital-intensive</p>
<p class="text-2xl font-bold mt-4 text-center">→ Exports Food 🌾</p>
</div>
</div>

</div>

</div>

---
transition: slide-up
---

<div class="glass-effect p-8 fadeInUp">

# 🔬 The Leontief Paradox

<div class="mt-6 space-y-6">

<div class="hover-lift p-6 bg-gradient-to-r from-red-500 to-pink-600 rounded-xl">
<h3 class="text-2xl font-bold mb-4">🎯 The Study (1953)</h3>
<div class="grid grid-cols-2 gap-4">
<div class="p-4 bg-white/10 rounded-lg">
<p class="font-bold mb-2">👨‍🔬 Researcher</p>
<p class="text-sm">Wassily Leontief</p>
<p class="text-xs opacity-75 mt-1">Nobel Prize 1973</p>
</div>
<div class="p-4 bg-white/10 rounded-lg">
<p class="font-bold mb-2">🇺🇸 Subject</p>
<p class="text-sm">U.S. Trade Data</p>
<p class="text-xs opacity-75 mt-1">Most capital-abundant country</p>
</div>
</div>
</div>

<div class="p-8 bg-gradient-to-br from-yellow-500 to-orange-600 rounded-xl">
<h3 class="text-3xl font-bold mb-6 text-center">⚠️ The Shocking Finding</h3>
<div class="p-6 bg-black/30 rounded-lg text-center">
<p class="text-2xl font-bold mb-4">U.S. EXPORTS were LESS capital-intensive than IMPORTS!</p>
<p class="text-lg opacity-90">This contradicts H-O theory predictions</p>
</div>
</div>

<div class="grid grid-cols-3 gap-4">
<div class="card-3d p-6 bg-blue-500/30 rounded-xl text-center">
<p class="text-sm opacity-80 mb-2">Capital/Million $</p>
<p class="text-xl font-bold">Exports</p>
<p class="text-3xl font-mono">$1.88M</p>
</div>
<div class="card-3d p-6 bg-purple-500/30 rounded-xl text-center">
<p class="text-sm opacity-80 mb-2">Capital/Million $</p>
<p class="text-xl font-bold">Imports</p>
<p class="text-3xl font-mono">$2.13M</p>
</div>
<div class="card-3d p-6 bg-red-500/30 rounded-xl text-center pulse">
<p class="text-sm opacity-80 mb-2">Paradox!</p>
<p class="text-xl font-bold">K/L Ratio</p>
<p class="text-lg">Imports > Exports</p>
</div>
</div>

</div>

</div>

---
layout: two-cols
---

<div class="pr-4">

# 📊 Empirical Evidence

<div class="glass-effect p-6 mt-4 fadeInUp">

### 🇺🇸 U.S. Data (1962)

<div class="space-y-3 text-sm">

<div class="p-3 bg-gradient-to-r from-blue-500 to-cyan-500 rounded-lg hover-lift">
<p class="font-bold mb-1">Capital/Labor Ratio</p>
<p>Exports: $14,321</p>
<p>Imports: $17,916</p>
</div>

<div class="p-3 bg-gradient-to-r from-green-500 to-teal-500 rounded-lg hover-lift">
<p class="font-bold mb-1">Labor per Million $</p>
<p>Exports: 131 person-years</p>
<p>Imports: 119 person-years</p>
</div>

<div class="p-3 bg-gradient-to-r from-purple-500 to-pink-500 rounded-lg hover-lift">
<p class="font-bold mb-1">Education</p>
<p>Exports: 10.1 years</p>
<p>Imports: 9.9 years</p>
</div>

<div class="p-3 bg-gradient-to-r from-orange-500 to-red-500 rounded-lg hover-lift">
<p class="font-bold mb-1">Engineers & Scientists</p>
<p>Exports: 2.55%</p>
<p>Imports: 1.89%</p>
</div>

</div>

</div>

</div>

::right::

<div class="pl-4">

<div class="glass-effect p-6 mt-4 fadeInUp" style="animation-delay: 0.2s;">

### 🌍 Global Evidence

<div class="space-y-4">

<div class="p-4 bg-gradient-to-br from-indigo-500 to-purple-600 rounded-lg">
<p class="font-bold text-lg mb-2">📚 Study by Bowen, Leamer & Sveikauskas</p>
<p class="text-sm opacity-90 mb-2">27 countries analyzed (1987)</p>
<p class="text-sm">✓ Confirmed Leontief Paradox internationally</p>
</div>

<div class="p-4 bg-gradient-to-br from-rose-500 to-red-600 rounded-lg">
<p class="font-bold text-lg mb-2">💡 Key Insight</p>
<p class="text-sm opacity-90">U.S. exports were more skill-intensive and education-intensive</p>
</div>

<div class="p-4 bg-gradient-to-br from-yellow-500 to-orange-600 rounded-lg pulse">
<p class="font-bold text-lg mb-2">🎯 Implication</p>
<p class="text-sm opacity-90">Need to consider HUMAN CAPITAL as a separate factor!</p>
</div>

</div>

</div>

</div>

---
transition: fade
---

<div class="glass-effect p-8 fadeInUp">

# 💰 Trade and Income Distribution

<div class="mt-6 space-y-6">

<div class="p-6 bg-gradient-to-r from-indigo-600 to-purple-700 rounded-xl">
<h3 class="text-2xl font-bold mb-4 text-center">⚖️ Winners and Losers from Trade</h3>
</div>

<div class="grid grid-cols-2 gap-6">

<div class="hover-lift p-6 bg-gradient-to-br from-green-500 to-emerald-600 rounded-xl">
<h4 class="text-2xl font-bold mb-4">✅ Winners</h4>
<div class="space-y-3">
<div class="p-3 bg-white/10 rounded-lg">
<p class="font-bold">Owners of Abundant Factors</p>
<p class="text-sm mt-2 opacity-90">🏠 Home: Workers (labor abundant)</p>
<p class="text-sm opacity-90">🌐 Foreign: Capital owners (capital abundant)</p>
</div>
<div class="p-3 bg-white/20 rounded-lg">
<p class="text-sm">Purchasing power increases in terms of BOTH goods</p>
</div>
</div>
</div>

<div class="hover-lift p-6 bg-gradient-to-br from-red-500 to-rose-600 rounded-xl">
<h4 class="text-2xl font-bold mb-4">❌ Losers</h4>
<div class="space-y-3">
<div class="p-3 bg-white/10 rounded-lg">
<p class="font-bold">Owners of Scarce Factors</p>
<p class="text-sm mt-2 opacity-90">🏠 Home: Capital owners (capital scarce)</p>
<p class="text-sm opacity-90">🌐 Foreign: Workers (labor scarce)</p>
</div>
<div class="p-3 bg-white/20 rounded-lg">
<p class="text-sm">Purchasing power decreases in terms of BOTH goods</p>
</div>
</div>
</div>

</div>

<div class="p-6 bg-gradient-to-r from-yellow-500 to-orange-500 rounded-xl text-center pulse">
<p class="text-xl font-bold mb-2">🎯 Import-Competing Industries</p>
<p class="text-lg">Factors used intensively here are hurt by trade opening</p>
<p class="text-sm mt-2 opacity-90">Example: Home imports food → Capital owners hurt regardless of their industry</p>
</div>

</div>

</div>

---
layout: center
---

<div class="glass-effect p-10 fadeInUp text-center">

# 📉 Income Inequality Puzzle

<div class="mt-8 space-y-6">

<div class="p-8 bg-gradient-to-r from-red-500 to-pink-600 rounded-2xl">
<h3 class="text-2xl font-bold mb-4">🤔 What Theory Predicts</h3>
<p class="text-lg mb-4">In developing countries (unskilled-labor abundant):</p>
<div class="p-4 bg-white/20 rounded-lg">
<p class="text-xl">Wages of unskilled workers should ↑ relative to skilled workers</p>
</div>
</div>

<div class="p-8 bg-gradient-to-r from-orange-500 to-yellow-600 rounded-2xl glow">
<h3 class="text-2xl font-bold mb-4">⚠️ What Actually Happened</h3>
<p class="text-lg mb-4">In many cases, the REVERSE occurred!</p>
<div class="p-4 bg-white/20 rounded-lg">
<p class="text-xl">🇲🇽 Mexico Example:</p>
<p class="text-lg mt-2">Skilled wages increased MORE than unskilled wages</p>
<p class="text-sm mt-2 opacity-80">(Despite Mexico being unskilled-labor abundant relative to US/Canada)</p>
</div>
</div>

</div>

</div>

---
transition: slide-up
---

<div class="glass-effect p-8 fadeInUp">

# 🔧 Explaining the Puzzle

<div class="mt-6 space-y-6">

<div class="hover-lift p-6 bg-gradient-to-r from-blue-500 to-indigo-600 rounded-xl">
<h3 class="text-2xl font-bold mb-4">❌ No Price Change Evidence</h3>
<p class="text-lg mb-3">Model predicts income distribution changes through output price changes</p>
<div class="p-4 bg-white/10 rounded-lg">
<p class="text-sm">But NO evidence of relative price changes for skill-intensive vs unskilled-intensive goods</p>
</div>
</div>

<div class="hover-lift p-6 bg-gradient-to-r from-purple-500 to-pink-600 rounded-xl">
<h3 class="text-2xl font-bold mb-4">💡 Alternative Explanation</h3>
<p class="text-lg mb-3">Trade as an <strong>indirect contributor</strong> through technology:</p>
<div class="space-y-3">
<div class="p-4 bg-white/10 rounded-lg">
<p class="font-bold mb-2">🏭 Exporting Firms</p>
<p class="text-sm">Upgrade to more skill-intensive production technologies</p>
</div>
<div class="p-4 bg-white/10 rounded-lg">
<p class="font-bold mb-2">🌐 Trade Liberalization</p>
<p class="text-sm">Induces widespread technological change across many firms</p>
</div>
</div>
</div>

<div class="p-6 bg-gradient-to-r from-green-500 to-teal-500 rounded-xl text-center pulse">
<p class="text-xl">
🔄 <strong>Trade accelerates technological change, which affects wage inequality</strong>
</p>
</div>

</div>

</div>

---
layout: center
class: text-center
---

<div class="glass-effect p-12 fadeInUp">

# 📚 Key Takeaways

<div class="grid grid-cols-2 gap-6 mt-10">

<div class="card-3d p-8 bg-gradient-to-br from-blue-500 to-cyan-600 rounded-2xl">
<div class="text-5xl mb-4">📐</div>
<h4 class="text-2xl font-bold mb-3">Curved PPF</h4>
<p class="text-lg">Factor substitution creates increasing opportunity costs</p>
</div>

<div class="card-3d p-8 bg-gradient-to-br from-purple-500 to-pink-600 rounded-2xl">
<div class="text-5xl mb-4">🏆</div>
<h4 class="text-2xl font-bold mb-3">Stolper-Samuelson</h4>
<p class="text-lg">Price changes redistribute income between factors</p>
</div>

<div class="card-3d p-8 bg-gradient-to-br from-green-500 to-teal-600 rounded-2xl">
<div class="text-5xl mb-4">🔄</div>
<h4 class="text-2xl font-bold mb-3">Rybczynski</h4>
<p class="text-lg">Resource growth biases production toward intensive sector</p>
</div>

<div class="card-3d p-8 bg-gradient-to-br from-orange-500 to-red-600 rounded-2xl">
<div class="text-5xl mb-4">🌍</div>
<h4 class="text-2xl font-bold mb-3">H-O Theorem</h4>
<p class="text-lg">Countries export goods intensive in abundant factors</p>
</div>

</div>

</div>

---
transition: fade
---

<div class="glass-effect p-8 fadeInUp">

# 🎯 Summary: Trade Patterns

<div class="mt-6 space-y-6">

<div class="hover-lift p-6 bg-gradient-to-r from-indigo-500 to-purple-600 rounded-xl">
<h3 class="text-2xl font-bold mb-4">1️⃣ Production Location</h3>
<p class="text-lg">Economy produces where PPF slope equals relative price (opportunity cost = market price)</p>
</div>

<div class="hover-lift p-6 bg-gradient-to-r from-blue-500 to-cyan-600 rounded-xl">
<h3 class="text-2xl font-bold mb-4">2️⃣ Factor Intensity Matters</h3>
<p class="text-lg">Goods differ in their use of labor vs capital (relative intensity determines trade pattern)</p>
</div>

<div class="hover-lift p-6 bg-gradient-to-r from-green-500 to-teal-600 rounded-xl">
<h3 class="text-2xl font-bold mb-4">3️⃣ Endowment Differences Drive Trade</h3>
<p class="text-lg">Countries export goods intensive in their abundant factors</p>
</div>

<div class="p-6 bg-gradient-to-r from-yellow-500 via-orange-500 to-red-500 rounded-xl text-center pulse">
<p class="text-2xl font-bold mb-3">💎 Bottom Line</p>
<p class="text-xl">Country gains overall from trade, but income redistribution occurs</p>
<p class="text-lg mt-2 opacity-90">Winners COULD compensate losers (but often don't in practice)</p>
</div>

</div>

</div>

---
layout: center
class: text-center
---

<div class="glass-effect p-12 fadeInUp">

# ❓ Study Questions

<div class="grid grid-cols-1 gap-4 mt-8 text-left">

<div class="hover-lift p-5 bg-gradient-to-r from-blue-500 to-indigo-600 rounded-xl">
<p class="text-lg">1. What are the key assumptions of the Heckscher-Ohlin Model?</p>
</div>

<div class="hover-lift p-5 bg-gradient-to-r from-purple-500 to-pink-600 rounded-xl">
<p class="text-lg">2. How does H-O differ from Ricardian and Specific Factors models?</p>
</div>

<div class="hover-lift p-5 bg-gradient-to-r from-green-500 to-teal-600 rounded-xl">
<p class="text-lg">3. What do Stolper-Samuelson and Rybczynski theorems suggest?</p>
</div>

<div class="hover-lift p-5 bg-gradient-to-r from-orange-500 to-red-600 rounded-xl">
<p class="text-lg">4. What is the Leontief Paradox and why is it important?</p>
</div>

<div class="hover-lift p-5 bg-gradient-to-r from-yellow-500 to-amber-600 rounded-xl">
<p class="text-lg">5. What real-world evidence challenges the H-O model predictions?</p>
</div>

</div>

</div>

---
layout: center
class: text-center
---

<style>
.thank-you {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-size: 5rem;
  font-weight: 900;
  animation: pulse 2s ease-in-out infinite;
}

.subtitle {
  font-size: 2rem;
  margin-top: 2rem;
  opacity: 0.9;
  animation: fadeInUp 1s ease-out;
}
</style>

<div class="fadeInUp">

<h1 class="thank-you glow">Thank You!</h1>

<p class="subtitle float">
  📚 Questions? Discussion? 💬
</p>

<div class="mt-16 grid grid-cols-3 gap-6">
<div class="card-3d p-6 bg-gradient-to-br from-blue-500 to-cyan-600 rounded-2xl">
<div class="text-4xl mb-3">🌍</div>
<p class="text-lg font-bold">International Trade</p>
</div>
<div class="card-3d p-6 bg-gradient-to-br from-purple-500 to-pink-600 rounded-2xl">
<div class="text-4xl mb-3">📊</div>
<p class="text-lg font-bold">Factor Endowments</p>
</div>
<div class="card-3d p-6 bg-gradient-to-br from-green-500 to-teal-600 rounded-2xl">
<div class="text-4xl mb-3">⚖️</div>
<p class="text-lg font-bold">Income Distribution</p>
</div>
</div>

</div>