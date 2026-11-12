## Student Math Score Prediction

- Create a generic structure for projects.
- Perform necessary operations
- Deploy

  [x] Structure
  [x] Log
  [x] Pipeline

> Structure

```cmd
    student-math-score-prediction/
    │   
    ├── models/
    │   
    ├── src/
    │   ├── components/
    │   │   ├── __init__.py
    │   │   ├── data-ingestion.py
    │   │   ├── data-transformation.py
    │   │   └── model-trainer.py
    │   │ 
    │   ├── pipelines/
    │   │   ├── __init__.py
    │   │   ├── predict-pipeline.py
    │   │   └── train-pipeline.py
    │   │
    │   ├── __init__.py
    │   ├── exception.py
    │   ├── logger.py
    │   └── utils.py
    │
    ├── requirements.txt
    └── README.md
```
