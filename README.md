# Microbial Abundance Analysis

This project analyzes microbial abundance under high and low nutrient conditions using a synthetic dataset.

## 📊 Dataset

Samples:
- High_Nutrient_Sample1 & Sample2  
- Low_Nutrient_Sample1 & Sample2  

Taxa included:
- Bacteroides, Firmicutes, Proteobacteria, Actinobacteria, Verrucomicrobia

## 🔍 Analysis

- **Mean abundance** calculated for each condition.
- **Fold change** (High / Low) computed to measure microbial response.
- **Stacked bar chart** visualizes abundance shifts across samples.

## 📦 Output

- CSV file: `microbial_nutrient_samples.csv`
- Bar chart: Taxa abundance by nutrient level

## ▶️ Run Requirements

```bash
pip install pandas matplotlib
