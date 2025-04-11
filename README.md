# Simplified GPU Overclocking & Undervolting Guide 🎮💻

Welcome to the **GPU Overclocking and Undervolting Guide**! This guide helps you tweak your Nvidia GPU for better performance or efficiency using **MSI Afterburner**. Whether you’re chasing higher frame rates or a cooler, quieter system, you’re in the right place.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Overclocking Your GPU](#overclocking-your-gpu)
- [Undervolting Your GPU](#undervolting-your-gpu)
- [Testing for Stability](#testing-for-stability)
- [Fixing Problems](#fixing-problems)
- [Monitoring](#Monitoring)

---

## Introduction

Overclocking boosts your GPU’s clock speeds for more performance, while undervolting cuts power use and heat. This guide focuses on **Nvidia GPUs** and uses **MSI Afterburner** to make these tweaks safe and straightforward.

---

## Prerequisites

Before you start, get these ready:

### Software:
- **MSI Afterburner**: For GPU adjustments. Set a high fan curve (e.g., 70% at 70°C) to keep temps in check.
- **HWiNFO**: Monitor temps, power limits, and more.

### Benchmarks:
- Use **Superposition**, **3DMark**, or **OCCT** for stability tests.  
  *Skip Furmark—it’s too intense.*


---

## Overclocking Your GPU

Overclocking ramps up core and memory speeds for better performance. Here’s how:

### Step 1: Core Clock Boost
1. In **MSI Afterburner**, set **Core Clock** to **+75 MHz**.
2. Run a benchmark or game for **30 minutes**.
3. If stable, bump it up by **+15 MHz** (**+12.5 MHz** for Pascal GPUs like GTX 10-series).
4. If it crashes or glitches, dial it back until stable.

### Step 2: Memory Clock Boost
1. Set **Memory Clock** to **+500 MHz**.
2. Test again. If stable, increase by **+50-100 MHz**.
3. Check for **artifacts** (flickering, weird colors) or slowdowns. Lower it if they show up.

### Monitoring:
- Use **HWiNFO** to keep core temp **<80°C** and hotspot **<95°C**.
- If it’s too hot, lower clocks or boost cooling.

## Testing for Stability

After tweaks, confirm your GPU is rock-solid:

### Tools:
- **Superposition** or **3DMark**.

### Instability Signs:
- Crashes, freezes, or shutdowns.
- **Artifacts** (flickering, odd colors).

### Test Time:
- Run tests for **30+ minutes**.

If issues pop up, reduce overclock or increase undervolt.

---

## Fixing Problems

Hit a snag? Try these:

### Boot Loop:
1. Boot into **Safe Mode** (F8 or Shift+Restart).
2. Disable overclock in **MSI Afterburner**.

### Driver Issues:
1. Use **DDU** in **Safe Mode** to wipe old drivers.
2. Install fresh **Nvidia drivers**.

Search online for deeper troubleshooting if needed.

---
### Monitoring:
- Watch temps and power with **HWiNFO**.
- Tweak settings if things get too warm.
---


