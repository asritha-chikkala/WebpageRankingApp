# 🌐 WebPage Ranker — A Visual MATLAB App for PageRank Analysis

**WebPage Ranker** is a MATLAB-based GUI application that helps users understand and visualize the PageRank algorithm in action. Whether you're an academic exploring graph-based ranking or a student diving into link analysis, this interactive tool gives you a hands-on approach to PageRank, web link graphs, and matrix-based ranking systems.

---

## 🚀 What Does It Do?

The app enables you to:

- 🌍 Input real or custom webpage URLs for ranking  
- 🧮 Fetch live PageRank scores from OpenPageRank API  
- 🔢 Construct a transition matrix using PageRank + domain authority  
- 📊 Visualize ranking through bar graphs, pie charts, and heatmaps  
- 🧠 Run eigenvalue-based power iteration to simulate convergence of ranks  
- 👁️ Observe changes over iterations in an intuitive format

---

## 🧩 Features

- ✅ **Tabbed Interface** — Cleanly separates inputs, visualizations, and analysis results  
- 🌐 **Live PageRank Fetching** — Pulls actual PageRank data from OpenPageRank (API key required)  
- 🧮 **Custom Ranking Matrix** — Combines fetched scores into a probability matrix  
- 📊 **Multiple Chart Types** — Displays grouped bar charts, pie charts, and correlation heatmaps  
- 🔁 **Power Iteration Algorithm** — Simulates how rank stabilizes over time  
- 🎯 **Automatic Sorting** — Displays final ranks in descending order  
- 🔄 **Reset/Refresh Buttons** — For trying new input domains instantly

---

## 💡 How to Use

1. Open MATLAB (R2019b or later recommended)  
2. Open the app:
   - Load `webpage_ranking_app.mlapp` into App Designer
   - Click **Run**  

---

## ⚠️ Important Note

Make sure to **replace the placeholder API key** in the code with your actual [OpenPageRank API key](https://openpagerank.com/api/).  
You can find the assignment near the API URL in the script (usually marked as `replace with ur api key'.

---

## ⚙️ Behind the Scenes

- 🔢 **Matrix Construction** — Transition matrix `T` built using PageRank and domain rank values  
- 🔁 **Power Iteration** — Iteratively computes eigenvector centrality from `T`  
- 📈 **Convergence Graph** — Shows how ranking stabilizes across iterations  
- 📉 **Correlation Heatmap** — Visualizes relationship between initial and final ranks

---

## 🌐 Tech Stack

- 🖥 MATLAB App Designer  
- 📊 MATLAB Visualization & Plotting Tools  
- 🔁 Eigenvector-based Ranking Logic  
- 📡 Optional OpenPageRank API Integration

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## ⭐ Show Your Support

If you find this project helpful, consider starring the repository!  
Feedback and contributions are welcome via issues or pull requests.

---
