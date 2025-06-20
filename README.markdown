# Neural Networks for Chip Design Defect Prediction

This open-source project applies **Neural Networks** (Multi-Layer Perceptrons, MLP) to predict defects in semiconductor chip designs, achieving ~88% accuracy on a synthetic dataset of 1,000 samples. It analyzes structured data (e.g., transistor count, defect rate) to optimize chip design workflows.

## Features
- **Neural Network Model**: MLP for complex, non-linear defect classification.
- **Synthetic Dataset**: 1,000 samples for prototyping.
- **Scalable**: Built with scikit-learn for local execution.

## Algorithm Comparison
- **Neural Networks**: Model complex patterns, require more compute and data.
- **Gradient Boosting**: High accuracy, efficient for noisy data.
- **Random Forest**: Robust ensembles, interpretable.
- **Decision Trees**: Simple, interpretable, prone to overfitting.
- **SVMs**: Non-linear data, less interpretable.
- **LLMs**: Text-focused, compute-heavy, unsuitable for tabular data.

## Project Structure
```
neural-network-chip-design/
├── README.md
├── requirements.txt
├── .gitignore
├── CONTRIBUTING.md
├── LICENSE
├── src/
│   └── neural_network_defect_prediction.py
└── data/
    ├── chip_defect_data.csv
    └── neural_network_metrics.txt
```

## Getting Started
### Prerequisites
- Python 3.8+
- Dependencies: `pip install -r requirements.txt`

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/egkhor/neural-network-chip-design.git
   cd neural-network-chip-design
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the script:
   ```bash
   python src/neural_network_defect_prediction.py
   ```

### Output
- Generates `chip_defect_data.csv` and `neural_network_metrics.txt` with model accuracy (~88%).

## Contributing
See [CONTRIBUTING.md](CONTRIBUTING.md) to add datasets, models, or visualizations.

## License
MIT License. See [LICENSE](LICENSE).

## Contact
Open an Issue or join Discussions on [GitHub](https://github.com/egkhor/neural-network-chip-design).