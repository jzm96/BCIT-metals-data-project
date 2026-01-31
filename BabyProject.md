```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
```


```python
df = pd.read_csv('precious_metals_historical_data.csv')
df.head()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Date</th>
      <th>Silver_Price</th>
      <th>Gold_Price</th>
      <th>Platinum_Price</th>
      <th>Silver_Returns</th>
      <th>Gold_Returns</th>
      <th>Platinum_Returns</th>
      <th>Gold_Silver_Ratio</th>
      <th>Silver_Volatility_30d</th>
      <th>Gold_Volatility_30d</th>
      <th>Platinum_Volatility_30d</th>
      <th>Silver_MA50</th>
      <th>Silver_MA200</th>
      <th>Gold_MA50</th>
      <th>Gold_MA200</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>2/3/2016</td>
      <td>13.95</td>
      <td>109.250000</td>
      <td>84.940002</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>7.831541</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2/4/2016</td>
      <td>14.17</td>
      <td>110.570000</td>
      <td>87.260002</td>
      <td>0.015771</td>
      <td>0.012082</td>
      <td>0.027313</td>
      <td>7.803105</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2</th>
      <td>2/5/2016</td>
      <td>14.34</td>
      <td>112.320000</td>
      <td>87.919998</td>
      <td>0.011997</td>
      <td>0.015827</td>
      <td>0.007564</td>
      <td>7.832636</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>3</th>
      <td>2/8/2016</td>
      <td>14.59</td>
      <td>113.830002</td>
      <td>89.199997</td>
      <td>0.017434</td>
      <td>0.013444</td>
      <td>0.014559</td>
      <td>7.801919</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>4</th>
      <td>2/9/2016</td>
      <td>14.51</td>
      <td>113.580002</td>
      <td>89.849998</td>
      <td>-0.005483</td>
      <td>-0.002196</td>
      <td>0.007287</td>
      <td>7.827705</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
  </tbody>
</table>
</div>




```python

```
