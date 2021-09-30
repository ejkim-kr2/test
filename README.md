# test
안녕하쇼?
---
1. 1
2. 2
4. 4
3. 3
- __1번째__
  - ~1.1.~
- _2기울임_
- ***3진하게 기울임***
> The information manager from hell.
>> git means "golbal inforation tracker"

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import tensorflow as tf

new_df = pd.read_csv('g_data_10T_6c.csv', parse_dates=["T_seg"]) #10T
df = new_df[['usage','T_seg']]
#df = df.dropna(axis=0, how='any')
```
