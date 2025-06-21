📊 About the Dataset

This dataset is based on digitized images of Fine Needle Aspirates (FNA) used to examine breast masses 🧬.
Each image captures the cell nuclei 🧫 characteristics to help in identifying breast cancer.

📚 The data originates from:
📝 K. P. Bennett and O. L. Mangasarian, “Robust Linear Programming Discrimination of Two Linearly Inseparable Sets,” Optimization Methods and Software, 1992.

🌐 UCI ML Repository: 🔗 Breast Cancer Wisconsin (Diagnostic)

🧾 Attribute Information
1️⃣ ID Number
2️⃣ Diagnosis
  - 🟥 M = Malignant (Cancerous)
  - 🟩 B = Benign (Non-cancerous)

3️⃣ – 32️⃣ Features derived from cell nuclei images:
(Each measured as Mean, Standard Error, and Worst value)

🔟 Ten Core Features per nucleus:

📏 Radius – mean distance from center to perimeter

🌫️ Texture – standard deviation of gray-scale values

📐 Perimeter

🔳 Area

🧵 Smoothness – local variation in radius lengths

⚙️ Compactness – (perimeter² / area − 1.0)

🌀 Concavity – severity of concave portions

📍 Concave Points – count of concave sections

🔁 Symmetry

🌊 Fractal Dimension – "coastline approximation" − 1

➡️ A total of 30 real-valued features calculated per image.

📌 Example:

Feature 3️⃣ = Mean Radius

Feature 1️⃣3️⃣ = Radius SE (Standard Error)

Feature 2️⃣3️⃣ = Worst Radius

📈 Additional Info
🧮 All values rounded to 4 significant digits

❌ No missing values

🧑‍⚕️ Class Distribution:
  - ✅ Benign: 357 cases
  - 🚨 Malignant: 212 cases

