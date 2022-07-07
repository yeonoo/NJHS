# NJHS

1. 나눔 폰트 설치 후 런타임 재시작<br>
!sudo apt-get install -y fonts-nanum<br>
!sudo fc-cache -fv<br>
!rm ~/.cache/matplotlib -rf<br>
<br>
2. 나눔 폰트 적용<br>
import matplotlib.pyplot as plt<br>
plt.rc('font', family='NanumBarunGothic') <br>
<br>
3. 패키지<br>
import pandas as pd<br>
import numpy as np<br>
import matplotlib.pyplot as plt<br>
%matplotlib inline<br>
plt.rc('font', family='NanumBarunGothic') <br>
<br>
4.selenium 설치<br>
!pip install selenium<br>
!apt-get update<br>
!apt install chromium-chromedriver<br>
!cp /usr/lib/chromium-browser/chromedriver /usr/bin<br>
