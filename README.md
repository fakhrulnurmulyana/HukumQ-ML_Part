# HukumQ-ML Part

<p align="center">
  <img width="300px" src="https://imgur.com/IGt1Phq.png"/>
</p>

## Table of Contents
1. [About The Project](#about-the-project)
2. [Technology Stack](#technology-stack)
3. [Project Structure](#project-structure)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Model Training & Evaluation](#model-training--evaluation)
7. [License](#license)

## About The Project
HukumQ is a mobile application designed to increase public awareness of legal regulations in Indonesia.  
We aim to bridge the gap between people and regulations, providing a user-friendly platform for easily accessible legal information.

**ML Part Overview:**   
- Modular pipeline for data preprocessing, feature engineering, training, and evaluation  

**Project Status:**  
This was my first machine learning project. Initially paused to focus on fundamentals, now revisiting it with a cleaner, modular, and industry-standard structure.

## Technology Stack
<p align="center">
  <img width="65px" src="https://imgur.com/SQMaw04.png"/></a>&#8287;&#8287;&#8287;&#8287;&#8287;
  <img width="50px" src="https://imgur.com/l1a3XsY.png"/></a>&#8287;&#8287;&#8287;&#8287;&#8287;
  <img width="50px" src="https://imgur.com/hWkj1WQ.png"/></a>&#8287;&#8287;&#8287;&#8287;&#8287;
  <img width="50px" src="https://imgur.com/OwWy9VI.png"/></a>&#8287;&#8287;&#8287;&#8287;&#8287;
</p>

## Project Structure
```bash
HUKUMQ-ML_PART/
├── data/
│   ├── external/
│   ├── interim/
│   ├── processed/
│   └── raw/
│
├── models/
│
├── notebooks/
│   ├── HukumQ.ipynb
│   ├── HukumQ(model_jelek).ipynb
│   └── HukumQ(pengembangan).ipynb
│
├── outputs/
│   ├── figures/
│   ├── logs/
│   └── reports/
│
├── src/
│   ├── core/
│   │   ├── __init__.py
│   │   ├── pipeline.py
│   │   ├── predictor.py
│   │   └── trainner.py
│   │
│   ├── data/
│   │   ├── __init__.py
│   │   ├── load_data.py
│   │   ├── preprocess.py
│   │   └── split_data.py
│   │
│   ├── features/
│   │   ├── __init__.py
│   │   ├── build_features.py
│   │   └── feature_selection.py
│   │
│   ├── models/
│   │   ├── __init__.py
│   │   ├── evaluate_model.py
│   │   ├── predict.py
│   │   └── train_model.py
│   │
│   ├── utils/
│   │   ├── __init__.py
│   │   ├── config.py
│   │   ├── file_io.py
│   │   ├── logger.py
│   │   ├── metrics.py
│   │   ├── seed.py
│   │   └── timer.py
│   │
│   └── visualization/
│   │   ├── __init__.py
│   │
│   └── __init__.py
│
├── tests/
│
├── .gitignore
├── README.md
└── requirements.txt
```

## Installation
1. Clone repository:
```bash
git clone https://github.com/fakhrulnurmulyana/HukumQ-ML_Part.git
cd HUKUMQ-ML_PART
````

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Optional: Setup virtual environment (recommended):

```bash
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
```

## License

MIT License – see [LICENSE](LICENSE) file for details.
