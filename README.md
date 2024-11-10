# needed-files
Some files I need to store in the internet and load via code (pandas et cetera).

# Available data

## Stack Overflow Annual Developer Survey 2019-2023

```python
import pandas as pd

year = <YEAR>
df = pd.read_csv(
  f"https://media.githubusercontent.com/media/MenzurkaKBAPK/needed-files/refs/heads/main/stack-overflow-dev-survey/survey_results_public_{year}.csv"
)
```
