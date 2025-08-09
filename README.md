# identifyingDepression
This project uses a fusion of emojis, text and range to identify depression on social media 
## Prerequisites

```bash
python >= 3.12.7
pip
```

## Installation

1. Create and activate a virtual environment:
```git clone https://github.com/yourusername/depression-detection
cd depression-detection

python3 -m venv venv
source venv/bin/activate
```
2. Install required packages:
```bash
pip install pandas numpy scikit-learn seaborn matplotlib scipy jupyter
```

## Dataset

The analysis uses 3  CSV files named `Mental-Health-Twitter.csv`, `Emoji_Sentiment_Data_v1.0.csv` and `depression_dataset_with_relabel.csv`

## Running the Analysis

1. Start Jupyter Notebook:
```bash
jupyter notebook
```

2. Open `main.ipynb`

3. Run all cells sequentially to

## Notes

- All random states are set for reproducibility
- Model parameters can be adjusted in their respective initialization cells
- Visualizations can be customized by modifying plot parameters