[![author](https://img.shields.io/badge/author-mohd--faizy-red)](https://github.com/mohd-faizy)
![made-with-Markdown](https://img.shields.io/badge/Made%20with-markdown-blue)
![Language](https://img.shields.io/github/languages/top/mohd-faizy/Learn_Pandas)
![Maintained](https://img.shields.io/maintenance/yes/2024)
![Last Commit](https://img.shields.io/github/last-commit/mohd-faizy/Learn_Pandas)
[![contributions welcome](https://img.shields.io/static/v1.svg?label=Contributions&message=Welcome&color=0059b3&style=flat-square)](https://github.com/mohd-faizy/Learn_Pandas)
![Size](https://img.shields.io/github/repo-size/mohd-faizy/Learn_Pandas)


# Pandas
![Pandas-roadmap](https://github.com/mohd-faizy/Learn_Pandas/blob/277e17f7cbb85319a70a68ba47566dab521e9b6b/_img/Pandas-banner.jpg)

Welcome to the Pandas repository! This repo is dedicated to providing helpful resources, tutorials, and examples for using the Pandas library in Python.

## Table of Contents

- [Pandas](#pandas)
  - [Table of Contents](#table-of-contents)
  - [Roadmap](#roadmap)
  - [Introduction](#introduction)
  - [Installation](#installation)
  - [Usage](#usage)
    - [Creating a DataFrame](#creating-a-dataframe)
    - [Reading a CSV File](#reading-a-csv-file)
    - [Data Analysis](#data-analysis)
  - [Features](#features)



 



## Roadmap
![Pandas-roadmap](https://github.com/mohd-faizy/Learn_Pandas/blob/master/_img/Pandas.png)

## Introduction

Pandas is a powerful and flexible open-source data analysis and manipulation library for Python. It provides data structures and functions needed to manipulate structured data seamlessly.

This repository aims to help users of all skill levels to better understand and utilize the Pandas library through comprehensive guides, code snippets, and example projects.

## Installation

To install Pandas, you can use pip, the Python package installer. Ensure you have Python installed, then run:

```bash
pip install pandas
```

For more detailed installation instructions, please refer to the [official Pandas installation guide](https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html).

## Usage

Here are some basic examples to get you started with Pandas:

### Creating a DataFrame

```python
import pandas as pd

data = {
    'Name': ['Alice', 'Bob', 'Charlie'],
    'Age': [25, 30, 35],
    'City': ['New York', 'Los Angeles', 'Chicago']
}

df = pd.DataFrame(data)
print(df)
```

### Reading a CSV File

```python
import pandas as pd

df = pd.read_csv('path/to/your/file.csv')
print(df.head())
```

### Data Analysis

```python
# Descriptive statistics
print(df.describe())

# Group by and aggregate
grouped = df.groupby('City').mean()
print(grouped)
```

For more examples and detailed tutorials, please refer to the [official Pandas documentation](https://pandas.pydata.org/pandas-docs/stable/).

## Features

- Data structures for efficient data manipulation (Series, DataFrame)
- Tools for reading and writing data between in-memory data structures and different formats (CSV, Excel, SQL, etc.)
- Data alignment and integrated handling of missing data
- Reshaping and pivoting of data sets
- Label-based slicing, fancy indexing, and subsetting of large data sets
- Data set merging and joining
- Time series functionality

## ⚖ ➤ License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## ❤️ Support

If you find this repository helpful, show your support by starring it! For questions or feedback, reach out on [Twitter(`X`)](https://twitter.com/F4izy).

#### $\color{skyblue}{\textbf{Connect with me:}}$

➤ If you have questions or feedback, feel free to reach out!!!

[<img align="left" src="https://cdn4.iconfinder.com/data/icons/social-media-icons-the-circle-set/48/twitter_circle-512.png" width="32px"/>][twitter]
[<img align="left" src="https://cdn-icons-png.flaticon.com/512/145/145807.png" width="32px"/>][linkedin]
[<img align="left" src="https://cdn-icons-png.flaticon.com/512/2626/2626299.png" width="32px"/>][Portfolio]

[twitter]: https://twitter.com/F4izy
[linkedin]: https://www.linkedin.com/in/mohd-faizy/
[Portfolio]: https://ai.stackexchange.com/users/36737/faizy?tab=profile

---

<img src="https://github-readme-stats.vercel.app/api?username=mohd-faizy&show_icons=true" width=380px height=200px />
