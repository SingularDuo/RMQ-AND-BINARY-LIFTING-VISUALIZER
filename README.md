

# 🧠 LCA & RMQ Visualizer

**LCA & RMQ Visualizer** is an interactive web application that helps learners and instructors visualize two important algorithms used in competitive programming and algorithms courses:

* **Range Minimum Query (RMQ)** using a *Sparse Table*
* **Lowest Common Ancestor (LCA)** using *Binary Lifting*

The site shows step-by-step construction and query procedures with animations and a live execution log, so users can see exactly what the algorithms do.

---

## ✨ Key Features

* **Interactive RMQ (Sparse Table)**
  Build the sparse table from any input array and watch the table fill level-by-level. Run range queries and see which table entries are used.

* **Animated Binary Lifting (LCA)**
  Input or load a tree, build the `up[v][k]` table, and animate LCA queries. The animation shows lifting steps and ancestor checks.

* **Execution Log (step-by-step)**
  For both RMQ and LCA, a compact execution log prints human-readable steps (available in English and Vietnamese) that describe exactly what the algorithm is doing.

* **Custom input**
  Paste your own arrays or tree edges to run realistic examples.

* **Visual highlights**
  Nodes, table cells, and array segments are highlighted during animations to make each operation clear.

* **Lightweight client-only app**
  Runs fully in the browser — no backend required.

---

## 🚀 Try It

Visit the live demo:
👉 [https://singularduo.github.io/RMQ-AND-BINARY-LIFTING-VISUALIZER/](https://singularduo.github.io/RMQ-AND-BINARY-LIFTING-VISUALIZER/)


---

## 🧩 How to Use

1. **RMQ**

   * Enter an array (space separated) and click **Build** or **Animate Build**.
   * Select indices `L` and `R` (by clicking array elements or typing values) and click **Query**.
   * Watch the sparse table levels and the execution log describing the steps.

2. **Binary Lifting (LCA)**

   * Load a sample tree or paste your own tree (first line = `n`, following lines = `u v` edges).
   * Click **Build Tree** or **Animate BL Build**.
   * Choose two nodes and click **Find LCA** or **Animate LCA**. The tree, up table, and execution log show the process.

---

## 🔧 Tech Stack

* Vanilla **JavaScript** + **HTML/CSS** (single-file static app)
* **SVG** used for tree rendering and node highlighting
* Designed to be lightweight and easily deployable (GitHub Pages, Netlify, Vercel, etc.)




