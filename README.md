## Titanic-GRADIO

### Task:
The sinking of the Titanic is one of the most infamous shipwrecks in history.

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

**In this challenge, we ask you to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).**

### Dependencies:
```
- import gradio as gr
- import numpy as np
- import pandas as pd
- import sklearn 
- from sklearn import preprocessing
- from sklearn.model_selection import train_test_split
- from sklearn.ensemble import RandomForestClassifier
- from sklearn.metrics import accuracy_score
```

### Steps:

1. Preprocessing
2. Splitting Data into Train/Test
3. Using RandomForest( Using Random Forest as it works good to most problems either classification or regression).[Here we are doing a Classification problem]
4. Predict Function
5. Gradio UI Interface

### Demo GRADIO Web-Application:
<img src="screenrecording.gif">
