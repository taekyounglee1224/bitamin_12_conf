## Bitamin 12th Generation Conference

Building a Sustainable Future With Carbon Emissions Trading

## Version
- Python : 3.9~3.11
- PyTorch : 2.1
- Scikit-Learn : 1.3.2
- Matplotlib : 3.7.2
- Statsmodels : 0.14.1

## Project Overview
### Background
- Exploring social variables and factors that influence carbon emission price forecasts
- 해당 변수들로 예측을 했을 때 예측 성능이 향상될까?

### Key Methodologies
- Selecting menaingful exogeneous variables using ARIMAX model
- Select variables as useful if p-value < 0.1
- Predicting the carbon emission price using selected variables : GRU vs LSTM vs LTSF vs Informer

## References
<a href = "https://epsis.kpx.or.kr/epsisnew/">EPSIS 전력통계정보시스템</a>

<a href = "https://ets.krx.co.kr/contents/ETS/03/03010000/ETS03010000.jsp">KRX 배출권시장 정보 플랫폼</a>

```
import numpy
import pandas
import matplotlib.pyplot as plt
import torch
from statsmodels.tsa.statespace.sarimax import SARIMAX
from statsmodels.tsa.arima_model import ARIMA
```

  
  

