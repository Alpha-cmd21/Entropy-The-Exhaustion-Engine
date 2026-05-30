Here is the updated, production-ready `README.md`. I have added a dedicated **🌐 Live Deployment Link** section right at the top, along with clear instructions on how users can find your live link using GitHub Pages.

---

```markdown
# Entropy: The Absolute Lifecycle Engine 

[![Engine Status](https://img.shields.io/badge/Engine-Active-00ffcc?style=flat-for-the-badge&logo=matrix)](https://github.com)
[![Lifecycle Horizon](https://img.shields.io/badge/Horizon-2_Years_(730_Days)-ff3b30?style=flat-for-the-badge)](https://github.com)
[![Framework](https://img.shields.io/badge/Framework-Zero_Dependencies-ffffff?style=flat-for-the-badge&logo=javascript)](https://github.com)

**Entropy** is an immersive, narrative-driven text RPG and lifestyle automation engine running entirely on raw, vanilla web technologies. It compresses a fixed 2-year timeline (730 days) into a high-stakes resource management simulator where internal willpower decays exponentially, random societal anomalies intercept your routines, and hidden status matrices track your habits to unlock completely different life trajectory epilogues.

Built using a cinematic, cyber-retro CRT design language, the engine runs without a single external library dependency.

---

## 🌐 Live Demo

Experience the live, interactive simulation instantly in your browser:
👉 **[LAUNCH THE ENTROPY ENGINE LIVE](https://YOUR_GITHUB_USERNAME.github.io/YOUR_REPOSITORY_NAME/)**

*(Note to Developer: Replace the placeholder link above with your actual GitHub Pages URL once deployed!)*

---

## 🕹️ System Architecture & Mechanics

### 1. The 2-Year Horizon Deck (`730 Days`)
Time is your absolute currency. The dashboard warps forward in 40-day chronological intervals per loop phase. As time drifts closer to the termination boundary wall, an **exponential decay algorithm** actively clamps down on your maximum daily energy ceiling:

$$MaxEnergy = 100 \times e^{-1.9 \times \left(\frac{ElapsedDays}{730}\right)}$$

A random daily fluctuation modifier ($\pm 12\%$) is applied to simulate the real-world variance of human energy levels, forcing tactical triage of tasks.

### 2. The Shuffled Task Board
Unlike static milestone tracking sheets, Entropy uses a **Fisher-Yates Shuffle Engine** to dynamically alternate and compile the registry board every single day. The system pulls random variations from a master data pool, preventing repetitive task fatigue and forcing the player to adapt to changing cognitive costs.

### 3. Stateful Hidden Triggers & Narrative Vectors
The state machine monitors background action registers to dynamically branch out the storyline:
* **The Running Track Alignment (Secret Unlock):** Completing the physical fitness block (`Gym`) 5 or more times permanently flips an internal state flag. This intercepts standard random logic and injects an exclusive romantic vector with an NPC named Elena, adding an entirely new recurring date task to your master pool.
* **Emergency Vectors (Critical Incidents):** Randomly intercepting loops (15% probability) force high-stakes altruistic choices, such as sacrificing over half your remaining day's willpower capacity to execute a transit rescue to a local healthcare hospital center.

### 4. The Cosmic Singularity Override
If the internal simulation matrix grid crosses the exact real-world calendar Month and Day matching your inputted birthdate, the application triggers a **Singularity Event**. The CSS variables dynamically re-theme into stark monochrome light mode, processing costs drop to $0$, and willpower values scale to $\infty$ to simulate total self-actualization clarity.

---

## 🛠️ Visual & Interface Features

* **Historian Ledger:** A real-time scrolling console log script that actively tracks, timestamps, and displays every action, state shift, and historical bypass directly onto your control panel.
* **CRT Scanline Filter:** Custom CSS grid styling layers that simulate an authentic retro terminal screen overlay using subtle color splitting and scan line noise gradients.
* **Micro-interaction Physics:** Fluid CSS keyframes and hardware-accelerated transforms map subtle responsive translations whenever items are completed, clicked, or toggled.

---

## 🚀 How to View & Deploy This Live

Because this engine relies entirely on native browser features, you can host it for free on the web using **GitHub Pages** in less than 60 seconds:

1. Create a new repository on GitHub named `entropy-engine`.
2. Upload your `index.html` file into the root directory of the repository.
3. Go to the **Settings** tab at the top of your repository page.
4. On the left sidebar, click on **Pages**.
5. Under "Build and deployment", change the Source branch from *None* to **`main`** (or `master`) and click **Save**.
6. Wait about 1-2 minutes. Refresh the settings page, and GitHub will provide you with your live URL at the top of that screen!

To run it locally on your computer instead:
```bash
# Launch a local server environment using native python tools:
python3 -m http.server 8080

```

Then open your browser and navigate to `http://localhost:8080`.

---

## 📂 Core Engine Data Matrix Blueprint

The interface state tree is structured cleanly around a unified monolithic configuration object:

```javascript
let state = {
    birthdate: null,
    daysPassed: 0,
    energy: 100,
    birthdayStateActive: false,
    metrics: { intellect: 0, vitality: 0, romance: 0, social: 0 },
    gymStreak: 0,
    hasGirlfriend: false,
    girlName: "Elena",
    activeTasksToday: []
};

```

---

## 🔮 End-Game Epilogue Conditions

Your choices write your ending script. At Day 730, the system permanently terminates your workspace frame and renders a complete telemetry evaluation summary based on your compiled score matrix:

| Ending Type | Requirement Priority | Narrative Output Profile |
| --- | --- | --- |
| **The Saturation Ending** | `hasGirlfriend` & High Vitality | Perfect lifestyle balance. You exit the matrix alongside a partner to weather the timeline collapse. |
| **The Capitalist Ending** | Intellect > All other metrics | Hyper cognitive specialization. High-tier algorithmic engineering career achieved, but physical assets degraded. |
| **The Guardian Ending** | Social > All other metrics | Altruistic shield validated. Sacrificing energy to crisis scenarios builds a bulletproof community safety net. |
| **The Burnout Ending** | Failure to systematically clear tasks | Energy tracking loops bleed out. Systemic stagnation results in an unoptimized, baseline termination. |

```

```
