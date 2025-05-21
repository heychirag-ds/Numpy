⚡ Why NumPy? Because Speed, Power & Clean Code.
<p align="center"> <img src="https://media.giphy.com/media/f9k1tV7HyORcngKF8v/giphy.gif" width="250"/> </p>
Welcome to the NumPy Playground — the first stop in my journey to becoming a Data Scientist. If you’ve ever wondered:

“Why not just use Python lists?”

This folder answers that question — with code, speed tests, memory checks, and pure NumPy magic.
📦 Structure
The Why Use Numpy/ folder contains the core arguments for why NumPy should be in every data scientist’s toolkit.

📁 Why Use Numpy/
├── 📄 01_SpeedTests.ipynb       → ⏱️ Python Lists vs NumPy Arrays: The Ultimate Speed Showdown
├── 📄 02_Creating_Arrays.ipynb  → 🛠️ Learn to build arrays: zeros, ones, arange, linspace, random
├── 📄 03_MemoryEfficiency.ipynb → 💾 Comparing RAM usage: NumPy vs List (spoiler: NumPy wins)
├── 📄 04_Vectorization.ipynb    → ⚡ Eliminate loops using blazing-fast vectorized operations
├── 📄 Exersice.ipynb            → 🧠 Hands-on mini challenges to sharpen your NumPy chops
└── 📄 Summary.txt               → 📜 TL;DR-style notes of everything above for quick revision

🧠 What You’ll Learn Here
Why NumPy is insanely fast

How to build arrays like a pro

The magic of vectorized operations

Memory profiling: arrays vs lists

How real-world ML/DS tools are built on top of this foundation

🛠️ Tech You're Using
<p align="left"> <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/Jupyter_Notebook-F37626?style=flat&logo=jupyter&logoColor=white"/> <img src="https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white"/> </p>
🚀 Why This Matters
NumPy isn’t “just a faster list.”
It’s the mathematical backbone of:

🔬 Machine Learning (scikit-learn, TensorFlow)

📊 Data Analysis (Pandas)

🧪 Scientific Computing (SciPy)

🧱 Data Visualization (Matplotlib, Seaborn)

You don’t learn NumPy for fun — you learn it because it’s mission-critical.

⭐ Bonus: Speed Teaser
Here’s a sneak peek from 01_SpeedTests.ipynb:

# Multiply two Python lists
list1 = [2,4,6]
list2 = [2,4,6]
multiply = [list1[i]*list2[i] for i in range(len(list1))]

# Multiply two NumPy arrays
arr1 = np.array(list1)
arr2 = np.array(list2)
res = arr1 * arr2  # One line. Super fast.
🧠 Clean. 💨 Fast. ⚡ Powerful.

<p align="center"> <strong>🎯 TL;DR:</strong> NumPy is where Python gets serious about numbers. <br/> This folder proves it. Let's go. 💥 </p>
