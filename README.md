# **AI-Assisted Coding and Developer Skill Development: A Quantitative Analysis of Productivity, Dependency, and Software Quality**

**Name:** Kartik Sharma
**Email:** [kartik1758.be22@chitkara.edu.in](mailto:kartik1758.be22@chitkara.edu.in)



## **1. Developer Dependency Score (DDS)**

```
def calculate_dds(A, M, V, w1=0.5, w2=0.3, w3=0.2):
    return (w1 * A) + (w2 * (1 - M)) + (w3 * (1 - V))
```



## **2. Cyclomatic Complexity**

```
import re

def cyclomatic_complexity(code):
    keywords = ['if', 'for', 'while', 'and', 'or', 'elif']
    complexity = 1
    for k in keywords:
        complexity += len(re.findall(r'\b' + k + r'\b', code))
    return complexity
```



## **3. Maintainability Index**

```
import math

def maintainability_index(loc, complexity, volume):
    return 171 - (5.2 * math.log(volume)) - (0.23 * complexity) - (16.2 * math.log(loc))
```



## **4. Bug Density**

```
def bug_density(bugs, loc):
    return (bugs / loc) * 100
```



## **5. Productivity (Task Completion Time)**

```
import numpy as np

def average_time(times):
    return np.mean(times)
```



## **6. Statistical Validation (t-test)**

```
from scipy import stats

def t_test(ai_group, control_group):
    return stats.ttest_ind(ai_group, control_group)
```
