# 🧊 Permafrost Degradation Tracking using Synthetic Satellite Data and Machine Learning

This project simulates satellite observations and uses machine learning to estimate **permafrost thaw depth**, which is a key indicator of climate change in polar and subpolar regions.

---

## 📁 Files Included

- `permafrost_tracking_synthetic.py`: Python script that:
  - Generates synthetic satellite-like data (LST, NDVI, Soil Moisture)
  - Trains a Random Forest regression model
  - Predicts thaw depth
  - Visualizes results and feature importance

- `permafrost_synthetic_data.xlsx`: Pre-generated synthetic dataset containing:
  - `LST` (Land Surface Temperature in °C)
  - `NDVI` (Normalized Difference Vegetation Index)
  - `Soil_Moisture` (volumetric moisture content, 0–1)
  - `Thaw_Depth` (simulated depth of permafrost thaw in cm)

---

## 🚀 How to Run

### Requirements

Install the necessary libraries with:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
Run the script
python permafrost_tracking_synthetic.py
This will:

Print a preview of the data

Train a regression model

Display evaluation metrics and plots

Show feature importance scores

📊 Data Description
The data is synthetic, meaning it is artificially generated for prototyping and testing purposes. It mimics real-world patterns observed in satellite monitoring of permafrost regions.

Feature	Description
LST	Land Surface Temperature (in degrees Celsius)
NDVI	Vegetation health index (0 to 1)
Soil_Moisture	Simulated surface moisture content (0 to 1)
Thaw_Depth	Estimated depth of thaw in permafrost layer (cm)

📌 Use Cases
This project is useful for:

Teaching remote sensing and machine learning

Prototyping environmental models

Simulating permafrost data workflows

📬 Author
Tarinabo williamtarinabo@gmail.com
