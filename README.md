# manual-extraction

## Overview

To extract error tables from machine manuals of industries.  

Make sure you have python and pip installed on your system.

1. Instal the libraries:
```
pip install -r requirements.txt
```

2. Configure `config.yaml` file 

3. Running script to extract csv from pdf:
```
python src/main.py
```

## Folder Structure

Below is a description of the main folders and files in the repository.

```
.
├── data
│   ├── raw
|   |   |──file1.pdf
│   ├── result
|   |   |──file1_result.csv
├── src
│   ├── main.py
│   ├── logs.py
```

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)