import pandas as pd
from sklearn.model_selection import train_test_split
from sklearn.metrics import accuracy_score, classification_report
from sklearn.ensemble import RandomForestClassifier
# loading data
df = pd.read_csv('/kaggle/input/asthma-disease-prediction/processed-data.csv')
df
