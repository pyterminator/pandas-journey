# Pandas kitabxanasını yüklə


```python
!pip install pandas
```

    Requirement already satisfied: pandas in c:\users\musfi\onedrive\desktop\pandas\venv\lib\site-packages (3.0.0)
    Requirement already satisfied: numpy>=1.26.0 in c:\users\musfi\onedrive\desktop\pandas\venv\lib\site-packages (from pandas) (2.4.1)
    Requirement already satisfied: python-dateutil>=2.8.2 in c:\users\musfi\onedrive\desktop\pandas\venv\lib\site-packages (from pandas) (2.9.0.post0)
    Requirement already satisfied: tzdata in c:\users\musfi\onedrive\desktop\pandas\venv\lib\site-packages (from pandas) (2025.3)
    Requirement already satisfied: six>=1.5 in c:\users\musfi\onedrive\desktop\pandas\venv\lib\site-packages (from python-dateutil>=2.8.2->pandas) (1.17.0)
    


```python
!pip show pandas
```

    Name: pandas
    Version: 3.0.0
    Summary: Powerful data structures for data analysis, time series, and statistics
    Home-page: https://pandas.pydata.org
    Author: 
    Author-email: The Pandas Development Team <pandas-dev@python.org>
    License: BSD 3-Clause License
    
     Copyright (c) 2008-2011, AQR Capital Management, LLC, Lambda Foundry, Inc. and PyData Development Team
     All rights reserved.
    
     Copyright (c) 2011-2026, Open source contributors.
    
     Redistribution and use in source and binary forms, with or without
     modification, are permitted provided that the following conditions are met:
    
     * Redistributions of source code must retain the above copyright notice, this
       list of conditions and the following disclaimer.
    
     * Redistributions in binary form must reproduce the above copyright notice,
       this list of conditions and the following disclaimer in the documentation
       and/or other materials provided with the distribution.
    
     * Neither the name of the copyright holder nor the names of its
       contributors may be used to endorse or promote products derived from
       this software without specific prior written permission.
    
     THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
     AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
     IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
     DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
     FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
     DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
     SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
     CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
     OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
     OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
    
    Location: C:\Users\musfi\OneDrive\Desktop\Pandas\venv\Lib\site-packages
    Requires: numpy, python-dateutil, tzdata
    Required-by: 
    


```python
!pip list
```

    Package                   Version
    ------------------------- -----------
    anyio                     4.12.1
    argon2-cffi               25.1.0
    argon2-cffi-bindings      25.1.0
    arrow                     1.4.0
    asttokens                 3.0.1
    async-lru                 2.1.0
    attrs                     25.4.0
    babel                     2.17.0
    beautifulsoup4            4.14.3
    bleach                    6.3.0
    certifi                   2026.1.4
    cffi                      2.0.0
    charset-normalizer        3.4.4
    colorama                  0.4.6
    comm                      0.2.3
    debugpy                   1.8.19
    decorator                 5.2.1
    defusedxml                0.7.1
    executing                 2.2.1
    fastjsonschema            2.21.2
    fqdn                      1.5.1
    h11                       0.16.0
    httpcore                  1.0.9
    httpx                     0.28.1
    idna                      3.11
    ipykernel                 7.1.0
    ipython                   9.9.0
    ipython_pygments_lexers   1.1.1
    ipywidgets                8.1.8
    isoduration               20.11.0
    jedi                      0.19.2
    Jinja2                    3.1.6
    json5                     0.13.0
    jsonpointer               3.0.0
    jsonschema                4.26.0
    jsonschema-specifications 2025.9.1
    jupyter                   1.1.1
    jupyter_client            8.8.0
    jupyter-console           6.6.3
    jupyter_core              5.9.1
    jupyter-events            0.12.0
    jupyter-lsp               2.3.0
    jupyter_server            2.17.0
    jupyter_server_terminals  0.5.4
    jupyterlab                4.5.3
    jupyterlab_pygments       0.3.0
    jupyterlab_server         2.28.0
    jupyterlab_widgets        3.0.16
    lark                      1.3.1
    MarkupSafe                3.0.3
    matplotlib-inline         0.2.1
    mistune                   3.2.0
    nbclient                  0.10.4
    nbconvert                 7.16.6
    nbformat                  5.10.4
    nest-asyncio              1.6.0
    notebook                  7.5.3
    notebook_shim             0.2.4
    numpy                     2.4.1
    overrides                 7.7.0
    packaging                 26.0
    pandas                    3.0.0
    pandocfilters             1.5.1
    parso                     0.8.5
    pip                       25.3
    platformdirs              4.5.1
    prometheus_client         0.24.1
    prompt_toolkit            3.0.52
    psutil                    7.2.1
    pure_eval                 0.2.3
    pycparser                 3.0
    Pygments                  2.19.2
    python-dateutil           2.9.0.post0
    python-json-logger        4.0.0
    pywinpty                  3.0.2
    PyYAML                    6.0.3
    pyzmq                     27.1.0
    referencing               0.37.0
    requests                  2.32.5
    rfc3339-validator         0.1.4
    rfc3986-validator         0.1.1
    rfc3987-syntax            1.1.0
    rpds-py                   0.30.0
    Send2Trash                2.1.0
    setuptools                65.5.0
    six                       1.17.0
    soupsieve                 2.8.3
    stack-data                0.6.3
    terminado                 0.18.1
    tinycss2                  1.4.0
    tornado                   6.5.4
    traitlets                 5.14.3
    typing_extensions         4.15.0
    tzdata                    2025.3
    uri-template              1.3.0
    urllib3                   2.6.3
    wcwidth                   0.5.0
    webcolors                 25.10.0
    webencodings              0.5.1
    websocket-client          1.9.0
    widgetsnbextension        4.0.15
    

# Pandası import edək


```python
import pandas as pd
```


```python
pd
```




    <module 'pandas' from 'C:\\Users\\musfi\\OneDrive\\Desktop\\Pandas\\venv\\Lib\\site-packages\\pandas\\__init__.py'>



# Dummy (Fake) Data


```python
# mockaroo.com
```


```python
file_name = "employees.csv"
```

### Dataset nədir ?


```python
# Dataset - müəyyən bir qayda çərçivəsində məlumatların saxlanmasıdır.
comment = """ .csv
id, name, surname, age
1, Mushvig, Shukurov, 23
2, ...
"""
```

# DataFrame & Series

## DataFrame


```python
df = pd.read_csv(file_name)
```


```python
df
```




<div>

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>id</th>
      <th>first_name</th>
      <th>last_name</th>
      <th>email</th>
      <th>gender</th>
      <th>salary</th>
      <th>city</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>Josias</td>
      <td>Wilce</td>
      <td>jwilce0@1688.com</td>
      <td>Male</td>
      <td>$4483.98</td>
      <td>Rybnoye</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2</td>
      <td>Johnath</td>
      <td>Westrope</td>
      <td>jwestrope1@liveinternet.ru</td>
      <td>Female</td>
      <td>$2838.24</td>
      <td>San Cristóbal Cucho</td>
    </tr>
    <tr>
      <th>2</th>
      <td>3</td>
      <td>Rob</td>
      <td>Malden</td>
      <td>rmalden2@hostgator.com</td>
      <td>Male</td>
      <td>$6569.55</td>
      <td>Sighnaghi</td>
    </tr>
    <tr>
      <th>3</th>
      <td>4</td>
      <td>Perry</td>
      <td>Jellicorse</td>
      <td>pjellicorse3@uol.com.br</td>
      <td>Female</td>
      <td>$3537.36</td>
      <td>Huxiaoqiao</td>
    </tr>
    <tr>
      <th>4</th>
      <td>5</td>
      <td>Danny</td>
      <td>Bremmell</td>
      <td>dbremmell4@about.me</td>
      <td>Male</td>
      <td>$2528.52</td>
      <td>Vischongo</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>95</th>
      <td>96</td>
      <td>Prent</td>
      <td>Bichener</td>
      <td>pbichener2n@businessinsider.com</td>
      <td>Male</td>
      <td>$7862.33</td>
      <td>Ipauçu</td>
    </tr>
    <tr>
      <th>96</th>
      <td>97</td>
      <td>Barrett</td>
      <td>Reinmar</td>
      <td>breinmar2o@facebook.com</td>
      <td>Male</td>
      <td>$5681.56</td>
      <td>Torreira</td>
    </tr>
    <tr>
      <th>97</th>
      <td>98</td>
      <td>Filberto</td>
      <td>Admans</td>
      <td>fadmans2p@myspace.com</td>
      <td>Male</td>
      <td>$7908.45</td>
      <td>Pegongan</td>
    </tr>
    <tr>
      <th>98</th>
      <td>99</td>
      <td>Kandace</td>
      <td>Lockner</td>
      <td>klockner2q@walmart.com</td>
      <td>Female</td>
      <td>$3410.48</td>
      <td>Sidaraja</td>
    </tr>
    <tr>
      <th>99</th>
      <td>100</td>
      <td>Morganne</td>
      <td>McGeady</td>
      <td>mmcgeady2r@cloudflare.com</td>
      <td>Female</td>
      <td>$9508.89</td>
      <td>Midões</td>
    </tr>
  </tbody>
</table>
<p>100 rows × 7 columns</p>
</div>




```python
df_2 = pd.read_csv(file_name, index_col="id")
```


```python
df_2
```




<div>

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>first_name</th>
      <th>last_name</th>
      <th>email</th>
      <th>gender</th>
      <th>salary</th>
      <th>city</th>
    </tr>
    <tr>
      <th>id</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>1</th>
      <td>Josias</td>
      <td>Wilce</td>
      <td>jwilce0@1688.com</td>
      <td>Male</td>
      <td>$4483.98</td>
      <td>Rybnoye</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Johnath</td>
      <td>Westrope</td>
      <td>jwestrope1@liveinternet.ru</td>
      <td>Female</td>
      <td>$2838.24</td>
      <td>San Cristóbal Cucho</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Rob</td>
      <td>Malden</td>
      <td>rmalden2@hostgator.com</td>
      <td>Male</td>
      <td>$6569.55</td>
      <td>Sighnaghi</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Perry</td>
      <td>Jellicorse</td>
      <td>pjellicorse3@uol.com.br</td>
      <td>Female</td>
      <td>$3537.36</td>
      <td>Huxiaoqiao</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Danny</td>
      <td>Bremmell</td>
      <td>dbremmell4@about.me</td>
      <td>Male</td>
      <td>$2528.52</td>
      <td>Vischongo</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>96</th>
      <td>Prent</td>
      <td>Bichener</td>
      <td>pbichener2n@businessinsider.com</td>
      <td>Male</td>
      <td>$7862.33</td>
      <td>Ipauçu</td>
    </tr>
    <tr>
      <th>97</th>
      <td>Barrett</td>
      <td>Reinmar</td>
      <td>breinmar2o@facebook.com</td>
      <td>Male</td>
      <td>$5681.56</td>
      <td>Torreira</td>
    </tr>
    <tr>
      <th>98</th>
      <td>Filberto</td>
      <td>Admans</td>
      <td>fadmans2p@myspace.com</td>
      <td>Male</td>
      <td>$7908.45</td>
      <td>Pegongan</td>
    </tr>
    <tr>
      <th>99</th>
      <td>Kandace</td>
      <td>Lockner</td>
      <td>klockner2q@walmart.com</td>
      <td>Female</td>
      <td>$3410.48</td>
      <td>Sidaraja</td>
    </tr>
    <tr>
      <th>100</th>
      <td>Morganne</td>
      <td>McGeady</td>
      <td>mmcgeady2r@cloudflare.com</td>
      <td>Female</td>
      <td>$9508.89</td>
      <td>Midões</td>
    </tr>
  </tbody>
</table>
<p>100 rows × 6 columns</p>
</div>




```python
type(df_2)
```




    pandas.DataFrame



## Series


```python
s_1 = df.city
```


```python
type(s_1)
```




    pandas.Series




```python
s_1
```




    0                 Rybnoye
    1     San Cristóbal Cucho
    2               Sighnaghi
    3              Huxiaoqiao
    4               Vischongo
                 ...         
    95                 Ipauçu
    96               Torreira
    97               Pegongan
    98               Sidaraja
    99                 Midões
    Name: city, Length: 100, dtype: str



# Metodlar


```python
df
```




<div>

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>id</th>
      <th>first_name</th>
      <th>last_name</th>
      <th>email</th>
      <th>gender</th>
      <th>salary</th>
      <th>city</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>Josias</td>
      <td>Wilce</td>
      <td>jwilce0@1688.com</td>
      <td>Male</td>
      <td>$4483.98</td>
      <td>Rybnoye</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2</td>
      <td>Johnath</td>
      <td>Westrope</td>
      <td>jwestrope1@liveinternet.ru</td>
      <td>Female</td>
      <td>$2838.24</td>
      <td>San Cristóbal Cucho</td>
    </tr>
    <tr>
      <th>2</th>
      <td>3</td>
      <td>Rob</td>
      <td>Malden</td>
      <td>rmalden2@hostgator.com</td>
      <td>Male</td>
      <td>$6569.55</td>
      <td>Sighnaghi</td>
    </tr>
    <tr>
      <th>3</th>
      <td>4</td>
      <td>Perry</td>
      <td>Jellicorse</td>
      <td>pjellicorse3@uol.com.br</td>
      <td>Female</td>
      <td>$3537.36</td>
      <td>Huxiaoqiao</td>
    </tr>
    <tr>
      <th>4</th>
      <td>5</td>
      <td>Danny</td>
      <td>Bremmell</td>
      <td>dbremmell4@about.me</td>
      <td>Male</td>
      <td>$2528.52</td>
      <td>Vischongo</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>95</th>
      <td>96</td>
      <td>Prent</td>
      <td>Bichener</td>
      <td>pbichener2n@businessinsider.com</td>
      <td>Male</td>
      <td>$7862.33</td>
      <td>Ipauçu</td>
    </tr>
    <tr>
      <th>96</th>
      <td>97</td>
      <td>Barrett</td>
      <td>Reinmar</td>
      <td>breinmar2o@facebook.com</td>
      <td>Male</td>
      <td>$5681.56</td>
      <td>Torreira</td>
    </tr>
    <tr>
      <th>97</th>
      <td>98</td>
      <td>Filberto</td>
      <td>Admans</td>
      <td>fadmans2p@myspace.com</td>
      <td>Male</td>
      <td>$7908.45</td>
      <td>Pegongan</td>
    </tr>
    <tr>
      <th>98</th>
      <td>99</td>
      <td>Kandace</td>
      <td>Lockner</td>
      <td>klockner2q@walmart.com</td>
      <td>Female</td>
      <td>$3410.48</td>
      <td>Sidaraja</td>
    </tr>
    <tr>
      <th>99</th>
      <td>100</td>
      <td>Morganne</td>
      <td>McGeady</td>
      <td>mmcgeady2r@cloudflare.com</td>
      <td>Female</td>
      <td>$9508.89</td>
      <td>Midões</td>
    </tr>
  </tbody>
</table>
<p>100 rows × 7 columns</p>
</div>



### Columns


```python
df.columns
```




    Index(['id', 'first_name', 'last_name', 'email', 'gender', 'salary', 'city'], dtype='str')




```python
headers = list(df.columns)
```


```python
headers
```




    ['id', 'first_name', 'last_name', 'email', 'gender', 'salary', 'city']



### Shape


```python
df
```




<div>

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>id</th>
      <th>first_name</th>
      <th>last_name</th>
      <th>email</th>
      <th>gender</th>
      <th>salary</th>
      <th>city</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>Josias</td>
      <td>Wilce</td>
      <td>jwilce0@1688.com</td>
      <td>Male</td>
      <td>$4483.98</td>
      <td>Rybnoye</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2</td>
      <td>Johnath</td>
      <td>Westrope</td>
      <td>jwestrope1@liveinternet.ru</td>
      <td>Female</td>
      <td>$2838.24</td>
      <td>San Cristóbal Cucho</td>
    </tr>
    <tr>
      <th>2</th>
      <td>3</td>
      <td>Rob</td>
      <td>Malden</td>
      <td>rmalden2@hostgator.com</td>
      <td>Male</td>
      <td>$6569.55</td>
      <td>Sighnaghi</td>
    </tr>
    <tr>
      <th>3</th>
      <td>4</td>
      <td>Perry</td>
      <td>Jellicorse</td>
      <td>pjellicorse3@uol.com.br</td>
      <td>Female</td>
      <td>$3537.36</td>
      <td>Huxiaoqiao</td>
    </tr>
    <tr>
      <th>4</th>
      <td>5</td>
      <td>Danny</td>
      <td>Bremmell</td>
      <td>dbremmell4@about.me</td>
      <td>Male</td>
      <td>$2528.52</td>
      <td>Vischongo</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>95</th>
      <td>96</td>
      <td>Prent</td>
      <td>Bichener</td>
      <td>pbichener2n@businessinsider.com</td>
      <td>Male</td>
      <td>$7862.33</td>
      <td>Ipauçu</td>
    </tr>
    <tr>
      <th>96</th>
      <td>97</td>
      <td>Barrett</td>
      <td>Reinmar</td>
      <td>breinmar2o@facebook.com</td>
      <td>Male</td>
      <td>$5681.56</td>
      <td>Torreira</td>
    </tr>
    <tr>
      <th>97</th>
      <td>98</td>
      <td>Filberto</td>
      <td>Admans</td>
      <td>fadmans2p@myspace.com</td>
      <td>Male</td>
      <td>$7908.45</td>
      <td>Pegongan</td>
    </tr>
    <tr>
      <th>98</th>
      <td>99</td>
      <td>Kandace</td>
      <td>Lockner</td>
      <td>klockner2q@walmart.com</td>
      <td>Female</td>
      <td>$3410.48</td>
      <td>Sidaraja</td>
    </tr>
    <tr>
      <th>99</th>
      <td>100</td>
      <td>Morganne</td>
      <td>McGeady</td>
      <td>mmcgeady2r@cloudflare.com</td>
      <td>Female</td>
      <td>$9508.89</td>
      <td>Midões</td>
    </tr>
  </tbody>
</table>
<p>100 rows × 7 columns</p>
</div>




```python
df.shape
```




    (100, 7)




```python
rows, cols = df.shape
```


```python
rows
```




    100




```python
type(rows)
```




    int




```python
cols
```




    7




```python
type(cols)
```




    int




```python
type(df.shape)
```




    tuple




```python
len(df.shape)
```




    2




```python
s_1
```




    0                 Rybnoye
    1     San Cristóbal Cucho
    2               Sighnaghi
    3              Huxiaoqiao
    4               Vischongo
                 ...         
    95                 Ipauçu
    96               Torreira
    97               Pegongan
    98               Sidaraja
    99                 Midões
    Name: city, Length: 100, dtype: str




```python
s_1.shape
```




    (100,)




```python
len(s_1.shape)
```




    1



### Head


```python
df
```




<div>

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>id</th>
      <th>first_name</th>
      <th>last_name</th>
      <th>email</th>
      <th>gender</th>
      <th>salary</th>
      <th>city</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>Josias</td>
      <td>Wilce</td>
      <td>jwilce0@1688.com</td>
      <td>Male</td>
      <td>$4483.98</td>
      <td>Rybnoye</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2</td>
      <td>Johnath</td>
      <td>Westrope</td>
      <td>jwestrope1@liveinternet.ru</td>
      <td>Female</td>
      <td>$2838.24</td>
      <td>San Cristóbal Cucho</td>
    </tr>
    <tr>
      <th>2</th>
      <td>3</td>
      <td>Rob</td>
      <td>Malden</td>
      <td>rmalden2@hostgator.com</td>
      <td>Male</td>
      <td>$6569.55</td>
      <td>Sighnaghi</td>
    </tr>
    <tr>
      <th>3</th>
      <td>4</td>
      <td>Perry</td>
      <td>Jellicorse</td>
      <td>pjellicorse3@uol.com.br</td>
      <td>Female</td>
      <td>$3537.36</td>
      <td>Huxiaoqiao</td>
    </tr>
    <tr>
      <th>4</th>
      <td>5</td>
      <td>Danny</td>
      <td>Bremmell</td>
      <td>dbremmell4@about.me</td>
      <td>Male</td>
      <td>$2528.52</td>
      <td>Vischongo</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>95</th>
      <td>96</td>
      <td>Prent</td>
      <td>Bichener</td>
      <td>pbichener2n@businessinsider.com</td>
      <td>Male</td>
      <td>$7862.33</td>
      <td>Ipauçu</td>
    </tr>
    <tr>
      <th>96</th>
      <td>97</td>
      <td>Barrett</td>
      <td>Reinmar</td>
      <td>breinmar2o@facebook.com</td>
      <td>Male</td>
      <td>$5681.56</td>
      <td>Torreira</td>
    </tr>
    <tr>
      <th>97</th>
      <td>98</td>
      <td>Filberto</td>
      <td>Admans</td>
      <td>fadmans2p@myspace.com</td>
      <td>Male</td>
      <td>$7908.45</td>
      <td>Pegongan</td>
    </tr>
    <tr>
      <th>98</th>
      <td>99</td>
      <td>Kandace</td>
      <td>Lockner</td>
      <td>klockner2q@walmart.com</td>
      <td>Female</td>
      <td>$3410.48</td>
      <td>Sidaraja</td>
    </tr>
    <tr>
      <th>99</th>
      <td>100</td>
      <td>Morganne</td>
      <td>McGeady</td>
      <td>mmcgeady2r@cloudflare.com</td>
      <td>Female</td>
      <td>$9508.89</td>
      <td>Midões</td>
    </tr>
  </tbody>
</table>
<p>100 rows × 7 columns</p>
</div>




```python
df.head()
```




<div>

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>id</th>
      <th>first_name</th>
      <th>last_name</th>
      <th>email</th>
      <th>gender</th>
      <th>salary</th>
      <th>city</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>Josias</td>
      <td>Wilce</td>
      <td>jwilce0@1688.com</td>
      <td>Male</td>
      <td>$4483.98</td>
      <td>Rybnoye</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2</td>
      <td>Johnath</td>
      <td>Westrope</td>
      <td>jwestrope1@liveinternet.ru</td>
      <td>Female</td>
      <td>$2838.24</td>
      <td>San Cristóbal Cucho</td>
    </tr>
    <tr>
      <th>2</th>
      <td>3</td>
      <td>Rob</td>
      <td>Malden</td>
      <td>rmalden2@hostgator.com</td>
      <td>Male</td>
      <td>$6569.55</td>
      <td>Sighnaghi</td>
    </tr>
    <tr>
      <th>3</th>
      <td>4</td>
      <td>Perry</td>
      <td>Jellicorse</td>
      <td>pjellicorse3@uol.com.br</td>
      <td>Female</td>
      <td>$3537.36</td>
      <td>Huxiaoqiao</td>
    </tr>
    <tr>
      <th>4</th>
      <td>5</td>
      <td>Danny</td>
      <td>Bremmell</td>
      <td>dbremmell4@about.me</td>
      <td>Male</td>
      <td>$2528.52</td>
      <td>Vischongo</td>
    </tr>
  </tbody>
</table>
</div>




```python
df.head(10)
```




<div>

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>id</th>
      <th>first_name</th>
      <th>last_name</th>
      <th>email</th>
      <th>gender</th>
      <th>salary</th>
      <th>city</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>Josias</td>
      <td>Wilce</td>
      <td>jwilce0@1688.com</td>
      <td>Male</td>
      <td>$4483.98</td>
      <td>Rybnoye</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2</td>
      <td>Johnath</td>
      <td>Westrope</td>
      <td>jwestrope1@liveinternet.ru</td>
      <td>Female</td>
      <td>$2838.24</td>
      <td>San Cristóbal Cucho</td>
    </tr>
    <tr>
      <th>2</th>
      <td>3</td>
      <td>Rob</td>
      <td>Malden</td>
      <td>rmalden2@hostgator.com</td>
      <td>Male</td>
      <td>$6569.55</td>
      <td>Sighnaghi</td>
    </tr>
    <tr>
      <th>3</th>
      <td>4</td>
      <td>Perry</td>
      <td>Jellicorse</td>
      <td>pjellicorse3@uol.com.br</td>
      <td>Female</td>
      <td>$3537.36</td>
      <td>Huxiaoqiao</td>
    </tr>
    <tr>
      <th>4</th>
      <td>5</td>
      <td>Danny</td>
      <td>Bremmell</td>
      <td>dbremmell4@about.me</td>
      <td>Male</td>
      <td>$2528.52</td>
      <td>Vischongo</td>
    </tr>
    <tr>
      <th>5</th>
      <td>6</td>
      <td>Gay</td>
      <td>Quenby</td>
      <td>gquenby5@harvard.edu</td>
      <td>Male</td>
      <td>$977.72</td>
      <td>Monte Redondo</td>
    </tr>
    <tr>
      <th>6</th>
      <td>7</td>
      <td>Veronique</td>
      <td>Dimitriades</td>
      <td>vdimitriades6@businessweek.com</td>
      <td>Female</td>
      <td>$7177.23</td>
      <td>Talisayan</td>
    </tr>
    <tr>
      <th>7</th>
      <td>8</td>
      <td>Karoline</td>
      <td>Ciobutaru</td>
      <td>kciobutaru7@sogou.com</td>
      <td>Female</td>
      <td>$3266.93</td>
      <td>Wangtuan</td>
    </tr>
    <tr>
      <th>8</th>
      <td>9</td>
      <td>Knox</td>
      <td>Gillbanks</td>
      <td>kgillbanks8@huffingtonpost.com</td>
      <td>Male</td>
      <td>$4741.50</td>
      <td>Ocala</td>
    </tr>
    <tr>
      <th>9</th>
      <td>10</td>
      <td>Felizio</td>
      <td>Andress</td>
      <td>fandress9@who.int</td>
      <td>Bigender</td>
      <td>$8995.77</td>
      <td>Boden</td>
    </tr>
  </tbody>
</table>
</div>




```python
ilk_10_setir = df.head(10)
```


```python
ilk_10_setir
```




<div>

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>id</th>
      <th>first_name</th>
      <th>last_name</th>
      <th>email</th>
      <th>gender</th>
      <th>salary</th>
      <th>city</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>Josias</td>
      <td>Wilce</td>
      <td>jwilce0@1688.com</td>
      <td>Male</td>
      <td>$4483.98</td>
      <td>Rybnoye</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2</td>
      <td>Johnath</td>
      <td>Westrope</td>
      <td>jwestrope1@liveinternet.ru</td>
      <td>Female</td>
      <td>$2838.24</td>
      <td>San Cristóbal Cucho</td>
    </tr>
    <tr>
      <th>2</th>
      <td>3</td>
      <td>Rob</td>
      <td>Malden</td>
      <td>rmalden2@hostgator.com</td>
      <td>Male</td>
      <td>$6569.55</td>
      <td>Sighnaghi</td>
    </tr>
    <tr>
      <th>3</th>
      <td>4</td>
      <td>Perry</td>
      <td>Jellicorse</td>
      <td>pjellicorse3@uol.com.br</td>
      <td>Female</td>
      <td>$3537.36</td>
      <td>Huxiaoqiao</td>
    </tr>
    <tr>
      <th>4</th>
      <td>5</td>
      <td>Danny</td>
      <td>Bremmell</td>
      <td>dbremmell4@about.me</td>
      <td>Male</td>
      <td>$2528.52</td>
      <td>Vischongo</td>
    </tr>
    <tr>
      <th>5</th>
      <td>6</td>
      <td>Gay</td>
      <td>Quenby</td>
      <td>gquenby5@harvard.edu</td>
      <td>Male</td>
      <td>$977.72</td>
      <td>Monte Redondo</td>
    </tr>
    <tr>
      <th>6</th>
      <td>7</td>
      <td>Veronique</td>
      <td>Dimitriades</td>
      <td>vdimitriades6@businessweek.com</td>
      <td>Female</td>
      <td>$7177.23</td>
      <td>Talisayan</td>
    </tr>
    <tr>
      <th>7</th>
      <td>8</td>
      <td>Karoline</td>
      <td>Ciobutaru</td>
      <td>kciobutaru7@sogou.com</td>
      <td>Female</td>
      <td>$3266.93</td>
      <td>Wangtuan</td>
    </tr>
    <tr>
      <th>8</th>
      <td>9</td>
      <td>Knox</td>
      <td>Gillbanks</td>
      <td>kgillbanks8@huffingtonpost.com</td>
      <td>Male</td>
      <td>$4741.50</td>
      <td>Ocala</td>
    </tr>
    <tr>
      <th>9</th>
      <td>10</td>
      <td>Felizio</td>
      <td>Andress</td>
      <td>fandress9@who.int</td>
      <td>Bigender</td>
      <td>$8995.77</td>
      <td>Boden</td>
    </tr>
  </tbody>
</table>
</div>



### Tail


```python
son_5_setir = df.tail()
```


```python
son_5_setir
```




<div>

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>id</th>
      <th>first_name</th>
      <th>last_name</th>
      <th>email</th>
      <th>gender</th>
      <th>salary</th>
      <th>city</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>95</th>
      <td>96</td>
      <td>Prent</td>
      <td>Bichener</td>
      <td>pbichener2n@businessinsider.com</td>
      <td>Male</td>
      <td>$7862.33</td>
      <td>Ipauçu</td>
    </tr>
    <tr>
      <th>96</th>
      <td>97</td>
      <td>Barrett</td>
      <td>Reinmar</td>
      <td>breinmar2o@facebook.com</td>
      <td>Male</td>
      <td>$5681.56</td>
      <td>Torreira</td>
    </tr>
    <tr>
      <th>97</th>
      <td>98</td>
      <td>Filberto</td>
      <td>Admans</td>
      <td>fadmans2p@myspace.com</td>
      <td>Male</td>
      <td>$7908.45</td>
      <td>Pegongan</td>
    </tr>
    <tr>
      <th>98</th>
      <td>99</td>
      <td>Kandace</td>
      <td>Lockner</td>
      <td>klockner2q@walmart.com</td>
      <td>Female</td>
      <td>$3410.48</td>
      <td>Sidaraja</td>
    </tr>
    <tr>
      <th>99</th>
      <td>100</td>
      <td>Morganne</td>
      <td>McGeady</td>
      <td>mmcgeady2r@cloudflare.com</td>
      <td>Female</td>
      <td>$9508.89</td>
      <td>Midões</td>
    </tr>
  </tbody>
</table>
</div>




```python
son_10_setir = df.tail(10)
```


```python
son_10_setir
```




<div>

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>id</th>
      <th>first_name</th>
      <th>last_name</th>
      <th>email</th>
      <th>gender</th>
      <th>salary</th>
      <th>city</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>90</th>
      <td>91</td>
      <td>Pincus</td>
      <td>Rustidge</td>
      <td>prustidge2i@yelp.com</td>
      <td>Male</td>
      <td>$2682.62</td>
      <td>Valle de Ángeles</td>
    </tr>
    <tr>
      <th>91</th>
      <td>92</td>
      <td>Merna</td>
      <td>MacCracken</td>
      <td>mmaccracken2j@mit.edu</td>
      <td>Agender</td>
      <td>$6653.45</td>
      <td>Nancha</td>
    </tr>
    <tr>
      <th>92</th>
      <td>93</td>
      <td>Barbabra</td>
      <td>Klainer</td>
      <td>bklainer2k@nationalgeographic.com</td>
      <td>Female</td>
      <td>$9885.07</td>
      <td>Cawayan</td>
    </tr>
    <tr>
      <th>93</th>
      <td>94</td>
      <td>Farr</td>
      <td>Fishly</td>
      <td>ffishly2l@oracle.com</td>
      <td>Male</td>
      <td>$6407.92</td>
      <td>Leran Kulon</td>
    </tr>
    <tr>
      <th>94</th>
      <td>95</td>
      <td>Winna</td>
      <td>Tolcher</td>
      <td>wtolcher2m@huffingtonpost.com</td>
      <td>Female</td>
      <td>$1291.73</td>
      <td>Taloqan</td>
    </tr>
    <tr>
      <th>95</th>
      <td>96</td>
      <td>Prent</td>
      <td>Bichener</td>
      <td>pbichener2n@businessinsider.com</td>
      <td>Male</td>
      <td>$7862.33</td>
      <td>Ipauçu</td>
    </tr>
    <tr>
      <th>96</th>
      <td>97</td>
      <td>Barrett</td>
      <td>Reinmar</td>
      <td>breinmar2o@facebook.com</td>
      <td>Male</td>
      <td>$5681.56</td>
      <td>Torreira</td>
    </tr>
    <tr>
      <th>97</th>
      <td>98</td>
      <td>Filberto</td>
      <td>Admans</td>
      <td>fadmans2p@myspace.com</td>
      <td>Male</td>
      <td>$7908.45</td>
      <td>Pegongan</td>
    </tr>
    <tr>
      <th>98</th>
      <td>99</td>
      <td>Kandace</td>
      <td>Lockner</td>
      <td>klockner2q@walmart.com</td>
      <td>Female</td>
      <td>$3410.48</td>
      <td>Sidaraja</td>
    </tr>
    <tr>
      <th>99</th>
      <td>100</td>
      <td>Morganne</td>
      <td>McGeady</td>
      <td>mmcgeady2r@cloudflare.com</td>
      <td>Female</td>
      <td>$9508.89</td>
      <td>Midões</td>
    </tr>
  </tbody>
</table>
</div>



### Info


```python
df.info()
```

    <class 'pandas.DataFrame'>
    RangeIndex: 100 entries, 0 to 99
    Data columns (total 7 columns):
     #   Column      Non-Null Count  Dtype
    ---  ------      --------------  -----
     0   id          100 non-null    int64
     1   first_name  100 non-null    str  
     2   last_name   100 non-null    str  
     3   email       100 non-null    str  
     4   gender      100 non-null    str  
     5   salary      100 non-null    str  
     6   city        100 non-null    str  
    dtypes: int64(1), str(6)
    memory usage: 5.6 KB
    

### Describe


```python
df.describe()
```




<div>

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>id</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>count</th>
      <td>100.000000</td>
    </tr>
    <tr>
      <th>mean</th>
      <td>50.500000</td>
    </tr>
    <tr>
      <th>std</th>
      <td>29.011492</td>
    </tr>
    <tr>
      <th>min</th>
      <td>1.000000</td>
    </tr>
    <tr>
      <th>25%</th>
      <td>25.750000</td>
    </tr>
    <tr>
      <th>50%</th>
      <td>50.500000</td>
    </tr>
    <tr>
      <th>75%</th>
      <td>75.250000</td>
    </tr>
    <tr>
      <th>max</th>
      <td>100.000000</td>
    </tr>
  </tbody>
</table>
</div>



### Index


```python
df.index
```




    RangeIndex(start=0, stop=100, step=1)




```python
df.index = range(100, 300, 2)
```


```python
df
```




<div>

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>id</th>
      <th>first_name</th>
      <th>last_name</th>
      <th>email</th>
      <th>gender</th>
      <th>salary</th>
      <th>city</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>100</th>
      <td>1</td>
      <td>Josias</td>
      <td>Wilce</td>
      <td>jwilce0@1688.com</td>
      <td>Male</td>
      <td>$4483.98</td>
      <td>Rybnoye</td>
    </tr>
    <tr>
      <th>102</th>
      <td>2</td>
      <td>Johnath</td>
      <td>Westrope</td>
      <td>jwestrope1@liveinternet.ru</td>
      <td>Female</td>
      <td>$2838.24</td>
      <td>San Cristóbal Cucho</td>
    </tr>
    <tr>
      <th>104</th>
      <td>3</td>
      <td>Rob</td>
      <td>Malden</td>
      <td>rmalden2@hostgator.com</td>
      <td>Male</td>
      <td>$6569.55</td>
      <td>Sighnaghi</td>
    </tr>
    <tr>
      <th>106</th>
      <td>4</td>
      <td>Perry</td>
      <td>Jellicorse</td>
      <td>pjellicorse3@uol.com.br</td>
      <td>Female</td>
      <td>$3537.36</td>
      <td>Huxiaoqiao</td>
    </tr>
    <tr>
      <th>108</th>
      <td>5</td>
      <td>Danny</td>
      <td>Bremmell</td>
      <td>dbremmell4@about.me</td>
      <td>Male</td>
      <td>$2528.52</td>
      <td>Vischongo</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>290</th>
      <td>96</td>
      <td>Prent</td>
      <td>Bichener</td>
      <td>pbichener2n@businessinsider.com</td>
      <td>Male</td>
      <td>$7862.33</td>
      <td>Ipauçu</td>
    </tr>
    <tr>
      <th>292</th>
      <td>97</td>
      <td>Barrett</td>
      <td>Reinmar</td>
      <td>breinmar2o@facebook.com</td>
      <td>Male</td>
      <td>$5681.56</td>
      <td>Torreira</td>
    </tr>
    <tr>
      <th>294</th>
      <td>98</td>
      <td>Filberto</td>
      <td>Admans</td>
      <td>fadmans2p@myspace.com</td>
      <td>Male</td>
      <td>$7908.45</td>
      <td>Pegongan</td>
    </tr>
    <tr>
      <th>296</th>
      <td>99</td>
      <td>Kandace</td>
      <td>Lockner</td>
      <td>klockner2q@walmart.com</td>
      <td>Female</td>
      <td>$3410.48</td>
      <td>Sidaraja</td>
    </tr>
    <tr>
      <th>298</th>
      <td>100</td>
      <td>Morganne</td>
      <td>McGeady</td>
      <td>mmcgeady2r@cloudflare.com</td>
      <td>Female</td>
      <td>$9508.89</td>
      <td>Midões</td>
    </tr>
  </tbody>
</table>
<p>100 rows × 7 columns</p>
</div>



### Dtypes


```python
# df.dtypes
```


```python
# new_df = pd.read_csv(file_name)
```


```python
# new_df
```


```python
# new_df.dtypes
```

### Rename


```python
my_dict = {
    "id": "ID",
    "first_name": "Name",
    "last_name": "Surname",
    "last_name": "Surname",
    "email": "Email",
    "gender": "Gender",
    "salary": "Salary",
    "city": "City",
}
```


```python
df.rename(columns=my_dict)
```




<div>

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>ID</th>
      <th>Name</th>
      <th>Surname</th>
      <th>Email</th>
      <th>Gender</th>
      <th>Salary</th>
      <th>City</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>100</th>
      <td>1</td>
      <td>Josias</td>
      <td>Wilce</td>
      <td>jwilce0@1688.com</td>
      <td>Male</td>
      <td>$4483.98</td>
      <td>Rybnoye</td>
    </tr>
    <tr>
      <th>102</th>
      <td>2</td>
      <td>Johnath</td>
      <td>Westrope</td>
      <td>jwestrope1@liveinternet.ru</td>
      <td>Female</td>
      <td>$2838.24</td>
      <td>San Cristóbal Cucho</td>
    </tr>
    <tr>
      <th>104</th>
      <td>3</td>
      <td>Rob</td>
      <td>Malden</td>
      <td>rmalden2@hostgator.com</td>
      <td>Male</td>
      <td>$6569.55</td>
      <td>Sighnaghi</td>
    </tr>
    <tr>
      <th>106</th>
      <td>4</td>
      <td>Perry</td>
      <td>Jellicorse</td>
      <td>pjellicorse3@uol.com.br</td>
      <td>Female</td>
      <td>$3537.36</td>
      <td>Huxiaoqiao</td>
    </tr>
    <tr>
      <th>108</th>
      <td>5</td>
      <td>Danny</td>
      <td>Bremmell</td>
      <td>dbremmell4@about.me</td>
      <td>Male</td>
      <td>$2528.52</td>
      <td>Vischongo</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>290</th>
      <td>96</td>
      <td>Prent</td>
      <td>Bichener</td>
      <td>pbichener2n@businessinsider.com</td>
      <td>Male</td>
      <td>$7862.33</td>
      <td>Ipauçu</td>
    </tr>
    <tr>
      <th>292</th>
      <td>97</td>
      <td>Barrett</td>
      <td>Reinmar</td>
      <td>breinmar2o@facebook.com</td>
      <td>Male</td>
      <td>$5681.56</td>
      <td>Torreira</td>
    </tr>
    <tr>
      <th>294</th>
      <td>98</td>
      <td>Filberto</td>
      <td>Admans</td>
      <td>fadmans2p@myspace.com</td>
      <td>Male</td>
      <td>$7908.45</td>
      <td>Pegongan</td>
    </tr>
    <tr>
      <th>296</th>
      <td>99</td>
      <td>Kandace</td>
      <td>Lockner</td>
      <td>klockner2q@walmart.com</td>
      <td>Female</td>
      <td>$3410.48</td>
      <td>Sidaraja</td>
    </tr>
    <tr>
      <th>298</th>
      <td>100</td>
      <td>Morganne</td>
      <td>McGeady</td>
      <td>mmcgeady2r@cloudflare.com</td>
      <td>Female</td>
      <td>$9508.89</td>
      <td>Midões</td>
    </tr>
  </tbody>
</table>
<p>100 rows × 7 columns</p>
</div>




```python
my_index = list(range(300, 600, 3))
```


```python
# df.rename(index=my_index)
```


```python
# my_index
```


```python
#list(df.index)
```


```python
# df.index.to_list()
```


```python
old_ind = df.index.to_list()
```


```python
new_ind = dict(zip(old_ind, my_index))
```


```python
df.rename(index=new_ind)
```




<div>

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>id</th>
      <th>first_name</th>
      <th>last_name</th>
      <th>email</th>
      <th>gender</th>
      <th>salary</th>
      <th>city</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>300</th>
      <td>1</td>
      <td>Josias</td>
      <td>Wilce</td>
      <td>jwilce0@1688.com</td>
      <td>Male</td>
      <td>$4483.98</td>
      <td>Rybnoye</td>
    </tr>
    <tr>
      <th>303</th>
      <td>2</td>
      <td>Johnath</td>
      <td>Westrope</td>
      <td>jwestrope1@liveinternet.ru</td>
      <td>Female</td>
      <td>$2838.24</td>
      <td>San Cristóbal Cucho</td>
    </tr>
    <tr>
      <th>306</th>
      <td>3</td>
      <td>Rob</td>
      <td>Malden</td>
      <td>rmalden2@hostgator.com</td>
      <td>Male</td>
      <td>$6569.55</td>
      <td>Sighnaghi</td>
    </tr>
    <tr>
      <th>309</th>
      <td>4</td>
      <td>Perry</td>
      <td>Jellicorse</td>
      <td>pjellicorse3@uol.com.br</td>
      <td>Female</td>
      <td>$3537.36</td>
      <td>Huxiaoqiao</td>
    </tr>
    <tr>
      <th>312</th>
      <td>5</td>
      <td>Danny</td>
      <td>Bremmell</td>
      <td>dbremmell4@about.me</td>
      <td>Male</td>
      <td>$2528.52</td>
      <td>Vischongo</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>585</th>
      <td>96</td>
      <td>Prent</td>
      <td>Bichener</td>
      <td>pbichener2n@businessinsider.com</td>
      <td>Male</td>
      <td>$7862.33</td>
      <td>Ipauçu</td>
    </tr>
    <tr>
      <th>588</th>
      <td>97</td>
      <td>Barrett</td>
      <td>Reinmar</td>
      <td>breinmar2o@facebook.com</td>
      <td>Male</td>
      <td>$5681.56</td>
      <td>Torreira</td>
    </tr>
    <tr>
      <th>591</th>
      <td>98</td>
      <td>Filberto</td>
      <td>Admans</td>
      <td>fadmans2p@myspace.com</td>
      <td>Male</td>
      <td>$7908.45</td>
      <td>Pegongan</td>
    </tr>
    <tr>
      <th>594</th>
      <td>99</td>
      <td>Kandace</td>
      <td>Lockner</td>
      <td>klockner2q@walmart.com</td>
      <td>Female</td>
      <td>$3410.48</td>
      <td>Sidaraja</td>
    </tr>
    <tr>
      <th>597</th>
      <td>100</td>
      <td>Morganne</td>
      <td>McGeady</td>
      <td>mmcgeady2r@cloudflare.com</td>
      <td>Female</td>
      <td>$9508.89</td>
      <td>Midões</td>
    </tr>
  </tbody>
</table>
<p>100 rows × 7 columns</p>
</div>




```python
df.index = range(400, 800, 4)
```


```python
df
```




<div>

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>id</th>
      <th>first_name</th>
      <th>last_name</th>
      <th>email</th>
      <th>gender</th>
      <th>salary</th>
      <th>city</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>400</th>
      <td>1</td>
      <td>Josias</td>
      <td>Wilce</td>
      <td>jwilce0@1688.com</td>
      <td>Male</td>
      <td>$4483.98</td>
      <td>Rybnoye</td>
    </tr>
    <tr>
      <th>404</th>
      <td>2</td>
      <td>Johnath</td>
      <td>Westrope</td>
      <td>jwestrope1@liveinternet.ru</td>
      <td>Female</td>
      <td>$2838.24</td>
      <td>San Cristóbal Cucho</td>
    </tr>
    <tr>
      <th>408</th>
      <td>3</td>
      <td>Rob</td>
      <td>Malden</td>
      <td>rmalden2@hostgator.com</td>
      <td>Male</td>
      <td>$6569.55</td>
      <td>Sighnaghi</td>
    </tr>
    <tr>
      <th>412</th>
      <td>4</td>
      <td>Perry</td>
      <td>Jellicorse</td>
      <td>pjellicorse3@uol.com.br</td>
      <td>Female</td>
      <td>$3537.36</td>
      <td>Huxiaoqiao</td>
    </tr>
    <tr>
      <th>416</th>
      <td>5</td>
      <td>Danny</td>
      <td>Bremmell</td>
      <td>dbremmell4@about.me</td>
      <td>Male</td>
      <td>$2528.52</td>
      <td>Vischongo</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>780</th>
      <td>96</td>
      <td>Prent</td>
      <td>Bichener</td>
      <td>pbichener2n@businessinsider.com</td>
      <td>Male</td>
      <td>$7862.33</td>
      <td>Ipauçu</td>
    </tr>
    <tr>
      <th>784</th>
      <td>97</td>
      <td>Barrett</td>
      <td>Reinmar</td>
      <td>breinmar2o@facebook.com</td>
      <td>Male</td>
      <td>$5681.56</td>
      <td>Torreira</td>
    </tr>
    <tr>
      <th>788</th>
      <td>98</td>
      <td>Filberto</td>
      <td>Admans</td>
      <td>fadmans2p@myspace.com</td>
      <td>Male</td>
      <td>$7908.45</td>
      <td>Pegongan</td>
    </tr>
    <tr>
      <th>792</th>
      <td>99</td>
      <td>Kandace</td>
      <td>Lockner</td>
      <td>klockner2q@walmart.com</td>
      <td>Female</td>
      <td>$3410.48</td>
      <td>Sidaraja</td>
    </tr>
    <tr>
      <th>796</th>
      <td>100</td>
      <td>Morganne</td>
      <td>McGeady</td>
      <td>mmcgeady2r@cloudflare.com</td>
      <td>Female</td>
      <td>$9508.89</td>
      <td>Midões</td>
    </tr>
  </tbody>
</table>
<p>100 rows × 7 columns</p>
</div>



### Concat


```python
s_1 = df.first_name
```


```python
s_2 = df.salary
```


```python
s_1
```




    400      Josias
    404     Johnath
    408         Rob
    412       Perry
    416       Danny
             ...   
    780       Prent
    784     Barrett
    788    Filberto
    792     Kandace
    796    Morganne
    Name: first_name, Length: 100, dtype: str




```python
s_2
```




    400    $4483.98
    404    $2838.24
    408    $6569.55
    412    $3537.36
    416    $2528.52
             ...   
    780    $7862.33
    784    $5681.56
    788    $7908.45
    792    $3410.48
    796    $9508.89
    Name: salary, Length: 100, dtype: str




```python
pd.concat([s_1, s_2], axis=1)
```




<div>

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>first_name</th>
      <th>salary</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>400</th>
      <td>Josias</td>
      <td>$4483.98</td>
    </tr>
    <tr>
      <th>404</th>
      <td>Johnath</td>
      <td>$2838.24</td>
    </tr>
    <tr>
      <th>408</th>
      <td>Rob</td>
      <td>$6569.55</td>
    </tr>
    <tr>
      <th>412</th>
      <td>Perry</td>
      <td>$3537.36</td>
    </tr>
    <tr>
      <th>416</th>
      <td>Danny</td>
      <td>$2528.52</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>780</th>
      <td>Prent</td>
      <td>$7862.33</td>
    </tr>
    <tr>
      <th>784</th>
      <td>Barrett</td>
      <td>$5681.56</td>
    </tr>
    <tr>
      <th>788</th>
      <td>Filberto</td>
      <td>$7908.45</td>
    </tr>
    <tr>
      <th>792</th>
      <td>Kandace</td>
      <td>$3410.48</td>
    </tr>
    <tr>
      <th>796</th>
      <td>Morganne</td>
      <td>$9508.89</td>
    </tr>
  </tbody>
</table>
<p>100 rows × 2 columns</p>
</div>



### Task 1


```python
# Maaş sütunundakı dollar işarəsini və nöqtəli hissəni silib, first_name və salary sütunlu bir df yaradın.
```


```python
salary = df.salary
```


```python
salary
```




    400    $4483.98
    404    $2838.24
    408    $6569.55
    412    $3537.36
    416    $2528.52
             ...   
    780    $7862.33
    784    $5681.56
    788    $7908.45
    792    $3410.48
    796    $9508.89
    Name: salary, Length: 100, dtype: str




```python
salary = df.salary.to_list()
```


```python
salary
```




    ['$4483.98',
     '$2838.24',
     '$6569.55',
     '$3537.36',
     '$2528.52',
     '$977.72',
     '$7177.23',
     '$3266.93',
     '$4741.50',
     '$8995.77',
     '$9153.68',
     '$2180.60',
     '$5003.24',
     '$8498.14',
     '$1202.36',
     '$8206.10',
     '$4571.62',
     '$3637.18',
     '$9067.37',
     '$518.71',
     '$839.90',
     '$3707.11',
     '$4596.90',
     '$6928.31',
     '$4724.12',
     '$6156.79',
     '$4087.80',
     '$8119.49',
     '$3219.60',
     '$7705.36',
     '$6293.30',
     '$3011.39',
     '$5518.81',
     '$2221.83',
     '$3396.71',
     '$9431.91',
     '$9274.60',
     '$6718.89',
     '$2900.61',
     '$6501.90',
     '$2822.22',
     '$3350.66',
     '$3741.68',
     '$7802.44',
     '$9514.62',
     '$2369.69',
     '$699.57',
     '$4648.70',
     '$7266.39',
     '$9836.45',
     '$5114.69',
     '$2463.01',
     '$2861.21',
     '$2985.42',
     '$3762.06',
     '$5010.39',
     '$2144.75',
     '$7995.46',
     '$5493.25',
     '$2220.08',
     '$9040.15',
     '$6522.24',
     '$4678.45',
     '$919.02',
     '$1484.72',
     '$880.23',
     '$7947.47',
     '$8481.17',
     '$3551.87',
     '$2519.05',
     '$7443.88',
     '$1480.46',
     '$9439.61',
     '$4650.60',
     '$1052.23',
     '$3569.18',
     '$4051.14',
     '$7254.79',
     '$9933.70',
     '$2841.44',
     '$3843.15',
     '$2874.53',
     '$4382.74',
     '$7790.79',
     '$2072.45',
     '$2956.71',
     '$2866.90',
     '$3036.67',
     '$6050.82',
     '$2379.87',
     '$2682.62',
     '$6653.45',
     '$9885.07',
     '$6407.92',
     '$1291.73',
     '$7862.33',
     '$5681.56',
     '$7908.45',
     '$3410.48',
     '$9508.89']




```python
from math import trunc as truncate
def Clean(s: str|int) -> int: 
    if isinstance(s, str):
        return truncate(float(s[1:]))
    else:
        return truncate(s)
```


```python
salary = list(map(Clean, salary))
```


```python
salary
```




    [4483,
     2838,
     6569,
     3537,
     2528,
     977,
     7177,
     3266,
     4741,
     8995,
     9153,
     2180,
     5003,
     8498,
     1202,
     8206,
     4571,
     3637,
     9067,
     518,
     839,
     3707,
     4596,
     6928,
     4724,
     6156,
     4087,
     8119,
     3219,
     7705,
     6293,
     3011,
     5518,
     2221,
     3396,
     9431,
     9274,
     6718,
     2900,
     6501,
     2822,
     3350,
     3741,
     7802,
     9514,
     2369,
     699,
     4648,
     7266,
     9836,
     5114,
     2463,
     2861,
     2985,
     3762,
     5010,
     2144,
     7995,
     5493,
     2220,
     9040,
     6522,
     4678,
     919,
     1484,
     880,
     7947,
     8481,
     3551,
     2519,
     7443,
     1480,
     9439,
     4650,
     1052,
     3569,
     4051,
     7254,
     9933,
     2841,
     3843,
     2874,
     4382,
     7790,
     2072,
     2956,
     2866,
     3036,
     6050,
     2379,
     2682,
     6653,
     9885,
     6407,
     1291,
     7862,
     5681,
     7908,
     3410,
     9508]




```python
first_name = df.first_name.to_list()
```


```python
first_name
```




    ['Josias',
     'Johnath',
     'Rob',
     'Perry',
     'Danny',
     'Gay',
     'Veronique',
     'Karoline',
     'Knox',
     'Felizio',
     'Idelle',
     'Chantal',
     'Corrina',
     'Thaxter',
     'Eustace',
     'Wainwright',
     'Duncan',
     'Briant',
     'Ivory',
     'Tomi',
     'Margaretha',
     'Tallia',
     'Nalani',
     'Kristin',
     'Lucio',
     'Thea',
     'Daveen',
     'Olympe',
     'Julia',
     'Charyl',
     'Ofelia',
     'Leonard',
     'Cobb',
     'Juliana',
     'Becki',
     'Gilbertine',
     'Athena',
     'Bonnee',
     'Trescha',
     'Jenn',
     'Reiko',
     'Codee',
     'Catie',
     'Maryann',
     'Orella',
     'Nate',
     'Orion',
     'Magdalena',
     'Hadria',
     'Lurleen',
     'Clementina',
     'Samson',
     'Ashbey',
     'Immanuel',
     'Alejandra',
     'Ken',
     'Putnem',
     'Benjamen',
     'Bondy',
     'Trix',
     'Bonnie',
     'Page',
     'Hallsy',
     'Albertina',
     'Marje',
     'Maxim',
     'Bobbye',
     'Sydney',
     'Josi',
     'Wat',
     'Micky',
     'Rollin',
     'Franchot',
     'Kean',
     'Bendix',
     'Carin',
     'Abel',
     'Gardiner',
     'Virginie',
     'Gerty',
     'Alexei',
     'Talbert',
     'Calv',
     'Ignaz',
     'Nero',
     'Garv',
     'Findley',
     'Englebert',
     'Rodolph',
     'Lisa',
     'Pincus',
     'Merna',
     'Barbabra',
     'Farr',
     'Winna',
     'Prent',
     'Barrett',
     'Filberto',
     'Kandace',
     'Morganne']




```python
df = pd.DataFrame(list(zip(first_name, salary)), columns=["Ad", "Maaş"])
```


```python
df
```




<div>

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Ad</th>
      <th>Maaş</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Josias</td>
      <td>4483</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Johnath</td>
      <td>2838</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Rob</td>
      <td>6569</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Perry</td>
      <td>3537</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Danny</td>
      <td>2528</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>95</th>
      <td>Prent</td>
      <td>7862</td>
    </tr>
    <tr>
      <th>96</th>
      <td>Barrett</td>
      <td>5681</td>
    </tr>
    <tr>
      <th>97</th>
      <td>Filberto</td>
      <td>7908</td>
    </tr>
    <tr>
      <th>98</th>
      <td>Kandace</td>
      <td>3410</td>
    </tr>
    <tr>
      <th>99</th>
      <td>Morganne</td>
      <td>9508</td>
    </tr>
  </tbody>
</table>
<p>100 rows × 2 columns</p>
</div>



### Sum


```python
total_salary = df.Maaş.sum()
```


```python
total_salary
```




    np.int64(491851)




```python
total_salary  = df["Maaş"].sum()
```


```python
total_salary
```




    np.int64(491851)



### Mean


```python
avg_salary = df["Maaş"].mean()
```


```python
avg_salary
```




    np.float64(4918.51)




```python

```
