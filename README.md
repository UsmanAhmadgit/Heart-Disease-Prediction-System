# Heart-Disease-Prediction-System

## Setup: Running This Notebook From Scratch

Follow these steps in a terminal, inside this project's folder, before opening the notebook.

### 1. Put the dataset in the folder
Download the dataset from https://archive.ics.uci.edu/dataset/45/heart+disease, extract the zip, and copy **`processed.cleveland.data`** into the same folder as this notebook.


### 2. Install the required packages
```
pip install -r requirements.txt
```

## Input and Output

### Inputs (Features / Attributes)

Only **4 input attributes** are used 

| **Input Feature/Attribute** | **Possible Values** |
| --------------------------- | ------------------- |
| **ChestPain** | Typical Angina, Atypical Angina, Non-anginal Pain, Asymptomatic |
| **MaxHeartRate** | Low (below 130 bpm), Medium (130-159 bpm), High (160 bpm or more) |
| **STDepression** | Zero (0), Low (up to 1.5), High (above 1.5) |
| **ExerciseAngina** | No, Yes |

### Output (Prediction)

| **Output Attribute** | **Possible Values** |
| -------------------- | ------------------- |
| **HeartDisease** | Yes, No |

