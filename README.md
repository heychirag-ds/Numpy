⚡ Why NumPy? Because Speed, Power & Clean Code.
<p align="center"> <img src="https://media.giphy.com/media/f9k1tV7HyORcngKF8v/giphy.gif" width="250"/> </p>
Welcome to the NumPy Playground — the first stop in my journey to becoming a Data Scientist. If you’ve ever wondered:

“Why not just use Python lists?”

This folder answers that question — with code, speed tests, memory checks, and pure NumPy magic.
📦 Structure
The Why Use Numpy/ folder contains the core arguments for why NumPy should be in every data scientist’s toolkit.

bash
Copy
Edit
📁 Why Use Numpy/
├── 01_SpeedTests.ipynb       # ⏱️ NumPy vs. Python in a race
├── 02_Creating_Arrays.ipynb  # 🛠️ All the ways to make arrays
├── 03_MemoryEfficiency.ipynb # 💾 NumPy's RAM-saving powers
├── 04_Vectorization.ipynb    # ⚡ Operations without loops
├── Exersice.ipynb            # 🧠 Quick drills to test your skills
└── Summary.txt               # 📜 TL;DR of everything above
💡 PS: There are more folders coming up — Indexing, Broadcasting, Linear Algebra, and more. This is just Phase 1.

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

