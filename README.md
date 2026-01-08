# DOOH Visibility Evaluation (Street View)

Automated pipeline to retrieve Street View images, detect DOOH advertising panels and rank their visibility using computer vision and zero-shot models.

## 🛠 Tech stack
- Python
- Jupyter / Google Colab
- Computer Vision (GroundingDINO, Transformers)
- Street View API
- pandas, numpy, matplotlib

## 📁 Repository structure

```text
dooh-visibility-streetview/
│
├─ notebooks/
│   └─ DOOH_eval_project.ipynb
├─ data/
│   ├─ sample_inputs.csv
│   └─ sample_outputs.csv
├─ README.md
└─ requirements.txt
```

## ▶️ How to run

1. Clone the repository:

```bash
git clone https://github.com/Gunhum/dooh-visibility-streetview.git
cd dooh-visibility-streetview
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```bash
jupyter notebook
```

Open `notebooks/DOOH_eval_project.ipynb` and run the cells.

> Note: This notebook was originally developed on Google Colab and may require minor adjustments locally.

## 📌 Notes
- Raw Street View images and large datasets are not stored in the repository.
- Only small sample data is included for demonstration.

## 🔮 Possible improvements
- Add automated scheduling (cron / Airflow)
- Improve panel detection accuracy
- Add a dashboard or reporting layer
