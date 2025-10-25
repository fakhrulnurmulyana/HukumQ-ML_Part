# ML_Capstone

## Project Structure (temp)

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
│       ├── __init__.py
│       └── __init__.py   # kemungkinan duplikat
│
├── tests/
│
├── .gitignore
├── README.md
└── requirements.txt
```

## Project Status

This was my first project when I started learning machine learning.  
Initially, the development was paused as I focused on understanding the fundamentals.  

Now, I’m revisiting the project to rebuild it with a more modular and industry-standard structure.  
The first step is reorganizing the files and folders to make the project cleaner and easier to maintain.