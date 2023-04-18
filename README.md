# Alternative-Food-Recommendation-System
This is my final group project for DS2500 where we built a food recommendation system that returns alternatives to inputted foods. We used machine learning methods such as clustering and PCA to group foods together by similar nutritional values. When the system is given a food from the nutritional value dataset, it outputs foods with similar nutrition. This system can be supported for users who have dietary restrictions or allergies.

# Installation
To run the simulation, you will need Python 3 and the following libraries:

```
import pandas as pd
import matplotlib.pyplot as plt
import numpy as np
from copy import copy
import plotly.graph_objects as go
from sklearn.decomposition import PCA
import plotly.express as px
from sklearn.cluster import KMeans
import seaborn as sns
import math
```

# Usage
To start the notebook, simply download and open the file through Jupyter Notebook. 
