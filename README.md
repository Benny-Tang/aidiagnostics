---

# 🏥 AI Diagnostics Agent – Early Cancer Discovery

⚠️ **Research demo only. Not for clinical use.**

AI-powered prototype for **early cancer risk detection** that combines **imaging analysis + lab markers** into a single explainable summary.

---

## ✨ Features

* 🖼 **Imaging Agent** – Analyzes chest X-rays and highlights findings relevant to cancer risk (opacity, nodule, mass).
* 🔥 **Heatmap overlay** – Visual explanation of suspicious regions in uploaded X-rays.
* 🧪 **Lab Agent** – Parses tumor marker results (PSA, CA125, AFP) and flags abnormalities against thresholds.
* 🤝 **Coordinator Agent** – Integrates imaging + lab results into one consolidated report.
* 📂 **Demo Samples** – Includes mock labs, MRI, and CT reports for testing.

---

## 📂 Project Structure

```
ai_diagnostics/
│── app.py              # Main Gradio app
│── requirements.txt    # Dependencies
│── README.md           # Documentation
│── .gitignore          # Ignore cache, IDE, and env files
│── samples/            # Demo sample files
│    ├── sample_xray1.png
│    ├── sample_xray2.png
│    ├── sample_labs.txt
│    ├── sample_mri.txt
│    └── sample_ct.txt
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/USERNAME/ai_diagnostics.git
cd ai_diagnostics
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the demo

```bash
python app.py
```

The Gradio interface will launch in your browser.

---

## 🧪 Demo Samples

* **X-rays** → `samples/sample_xray1.png`, `sample_xray2.png`
* **Lab results** → `samples/sample_labs.txt`
* **MRI report** → `samples/sample_mri.txt`
* **CT report** → `samples/sample_ct.txt`

⚠️ All samples are **mock or public domain**.
🚫 Do not upload real patient data.

---

## 📋 Example Output

```
📋 Coordinator Summary (Early Cancer Screening)

🖼️ Imaging Agent (Chest X-ray for cancer risk)
Lung Opacity: 65.1%
Nodule: 61.6%
Mass: 53.4%

🧪 Lab Agent (Tumor Markers)
PSA: 8.0 ng/mL → elevated
CA125: 20.0 U/mL → ok
AFP: 15.0 ng/mL → elevated

Flags: PSA high, AFP high
```

---

## ⚖️ Disclaimer

This project is a **research demo only**.
It is **not a medical device** and **must not be used for clinical decision-making**.

---
