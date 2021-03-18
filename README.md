# HD_CARDIO
HD_CARDIO: Cardiotocogram signal classification using Hyperdimensional Computing

## Instructions

### Background
 - https://archive.ics.uci.edu/ml/datasets/cardiotocography

### Installing prerequisites.
 - pip install -r requirement.txt

### Run the application.
 - python HDC_model.py --app_ cardio --iter_ 20 --dimension_ 10000

 - Different hyperparameters
    - 1.app_: Training and testing dataset
    -  2.iter_: Number of epochs for retraining
    -   3.dimension_: Dimension of hyper-vector using in HDC model
