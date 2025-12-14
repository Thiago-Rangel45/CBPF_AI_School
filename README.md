# CBPF_AI_school

https://jupyterhub.inct-cern.cbpf.br

## Lista de exercisios e soluções

import os, numpy as np, pandas as pd
import matplotlib.pyplot as plt

```python
import os, numpy as np, pandas as pd
import matplotlib.pyplot as plt

from sklearn.model_selection import train_test_split, learning_curve, StratifiedKFold, GridSearchCV, cross_val_score
from sklearn.tree import DecisionTreeClassifier, plot_tree
from sklearn.ensemble import RandomForestClassifier, GradientBoostingClassifier, AdaBoostClassifier
from sklearn.metrics import (roc_curve, roc_auc_score, confusion_matrix, classification_report,
                             accuracy_score, ConfusionMatrixDisplay)
from sklearn.feature_selection import SelectFromModel
from sklearn.model_selection import learning_curve, StratifiedKFold

from sklearn.metrics import roc_curve, roc_auc_score
```