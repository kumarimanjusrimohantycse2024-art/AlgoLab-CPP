# AlgoLab C++ — Sorting Algorithm Visualizer

> "Tell me and I forget. Show me and I remember. Involve me and I understand."

[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-Visit_Now-58a6ff?style=for-the-badge)](https://kumarimanjusrimohantycse2024-art.github.io/AlgoLab-CPP/)

[![GitHub Repo](https://img.shields.io/badge/GitHub-AlgoLab--CPP-181717?style=for-the-badge&logo=github)](https://github.com/kumarimanjusrimohantycse2024-art/AlgoLab-CPP)

[![Language](https://img.shields.io/badge/Language-JavaScript-e3b341?style=for-the-badge&logo=javascript)](https://github.com/kumarimanjusrimohantycse2024-art/AlgoLab-CPP)

[![Algorithms](https://img.shields.io/badge/Algorithms-10_Sorting-3fb950?style=for-the-badge)](https://github.com/kumarimanjusrimohantycse2024-art/AlgoLab-CPP)

[![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero-f78166?style=for-the-badge)](https://github.com/kumarimanjusrimohantycse2024-art/AlgoLab-CPP)

[![Made With Love](https://img.shields.io/badge/Made_with-💙_by_Pihu_Mohanty-d2a8ff?style=for-the-badge)](https://github.com/kumarimanjusrimohantycse2024-art)
---

## 🧠 What Is This?

AlgoLab C++ is a browser-based interactive learning tool that visualizes 10 classic sorting algorithms in real time, designed to bridge the gap between theoretical computer science and practical understanding. Built entirely with vanilla JavaScript, HTML5, and CSS3 — no frameworks, no dependencies, one single file that runs in any modern browser without installation or configuration.

The application renders live animated bar charts that reflect every comparison, swap, and placement as it happens, color-coded by operation type — blue for default state, red for active comparisons, yellow for swaps, green for confirmed sorted positions, and purple for pivot elements in Quick Sort. Every visual change is synchronized with a plain-English narration engine that explains each operation in real time, making complex algorithmic behavior accessible to complete beginners while remaining technically rigorous for experienced developers.

Algorithms covered include Bubble Sort, Selection Sort, Insertion Sort, Merge Sort, Quick Sort, Heap Sort, Shell Sort, Counting Sort, Radix Sort, and Tim Sort — the same hybrid algorithm used internally by Python, Java, and Android. Each algorithm ships with its complete C++ pseudocode implementation, stability and in-place memory classification, and an interactive Big-O complexity chart that plots best, average, and worst-case growth curves across input sizes up to 5,000 elements using Chart.js.

Users can configure array size from 5 to 40 elements, select from four input distributions — random, nearly sorted, reversed, and few unique values — and control animation speed dynamically using a real-time slider. A live statistics panel tracks comparisons, swaps, total steps, and elapsed time for every run. A unified comparison table presents all 10 algorithms side by side for instant analysis and decision-making.

This project demonstrates applied mastery of algorithm design, time and space complexity analysis, divide-and-conquer paradigms, non-comparison sorting techniques, DOM manipulation, and data visualization — all implemented from scratch without external dependencies beyond Chart.js.

Designed with a dark academic aesthetic using JetBrains Mono and Fraunces typefaces, the interface is professional, portfolio-ready, and built to the standard expected at top-tier software engineering roles worldwide.

---

 ✨ Features at a Glance

| Feature | Details |
|---|---|
| 🎨 Live Visualization | Animated bars update in real time for every operation |
| 🗣️ Step Narration | Every comparison and swap explained in plain English |
| 💻 C++ Pseudocode | Real implementation code for all 10 algorithms |
| 📈 Big-O Charts | Interactive complexity graphs up to n = 5,000 |
| 📋 Comparison Table | All algorithms side by side with full metadata |
| ⚙️ Full Controls | Size, input type, speed — all adjustable live |
| 🎲 Input Types | Random · Nearly Sorted · Reversed · Few Unique |
| 📊 Live Stats | Comparisons · Swaps · Steps · Time tracked per run |

---

 🔢 Algorithms Covered

| NO| Algorithm | Best | Average | Worst | Space | Stable | Category |
|---|-----------|------|---------|-------|-------|--------|----------|
| 1 | Bubble Sort | O(n) | O(n²) | O(n²) | O(1) | ✅ | Elementary |
| 2 | Selection Sort | O(n²) | O(n²) | O(n²) | O(1) | ❌ | Elementary |
| 3 | Insertion Sort | O(n) | O(n²) | O(n²) | O(1) | ✅ | Elementary |
| 4 | Merge Sort | O(n log n) | O(n log n) | O(n log n) | O(n) | ✅ | Divide & Conquer |
| 5 | Quick Sort | O(n log n) | O(n log n) | O(n²) | O(log n) | ❌ | Divide & Conquer |
| 6 | Heap Sort | O(n log n) | O(n log n) | O(n log n) | O(1) | ❌ | Selection-based |
| 7 | Shell Sort | O(n log n) | O(n log²n) | O(n²) | O(1) | ❌ | Insertion-based |
| 8 | Counting Sort | O(n+k) | O(n+k) | O(n+k) | O(k) | ✅ | Non-comparison |
| 9 | Radix Sort | O(nk) | O(nk) | O(nk) | O(n+k) | ✅ | Non-comparison |
| 10 | Tim Sort | O(n) | O(n log n) | O(n log n) | O(n) | ✅ | Hybrid |

---

 🛠️ Tech Stack

```
Frontend       →  HTML5, CSS3, Vanilla JavaScript (ES6+)
Visualization  →  Custom DOM rendering engine (built from scratch)
Charts         →  Chart.js 4.4.1 (only external dependency)
Typography     →  JetBrains Mono + Fraunces (Google Fonts)
Hosting        →  GitHub Pages (zero config)
```

> Zero build step. Zero npm install. Zero frameworks.
> Download and open `index.html` — it just works.

---

 📂 Project Structure

```
sorting-analyzer/
│
├── index.html        ← Entire application (HTML + CSS + JS)
└── README.md         ← You are here
```

---

⚡ Run Locally

```bash
# Clone the repo
git clone https://kumarimanjusrimohantycse2024-art.github.io/AlgoLab-CPP/

# Navigate into the folder
cd AlgoLab-CPP

# Open directly in browser — no server needed
open index.html
```

---

 💡 Skills Demonstrated

- ✅ Data Structures & Algorithms (DSA)
- ✅ Time & Space Complexity Analysis (Big-O)
- ✅ Divide & Conquer, Greedy, and Hybrid algorithm paradigms
- ✅ Non-comparison sorting techniques
- ✅ Asynchronous JavaScript (async/await, Promises)
- ✅ Real-time DOM manipulation and event-driven architecture
- ✅ Data visualization and animation
- ✅ Clean code, zero-dependency architecture
- ✅ Responsive UI design and dark-mode theming

---

🎯 Why This Project Matters

Most developers can *name* sorting algorithms. Few can *explain* them visually, implement them from scratch, and make them understandable to anyone. This project does all three.

It reflects the kind of thinking valued at top engineering teams — clarity, depth, and the ability to communicate complex ideas simply.

---

👩‍💻 Author

Manjusri Mohanty — B.Tech CSE, 2024 Batch

[![GitHub](https://img.shields.io/badge/GitHub-kumarimanjusrimohantycse2024--art-181717?style=flat&logo=github)](https://github.com/kumarimanjusrimohantycse2024-art)

---

 ⭐ Support

If this project helped you understand sorting algorithms better, please consider giving it a star ⭐

It takes one second and means everything to an open-source developer just getting started.

---

<div align="center">
  <sub>Built with 💙 by Pihu Mohanty · No shortcuts, no frameworks, just pure code.</sub>
</div>
