    updated on: 10th July 2021

<div align=center>
    <a href="https://warmachine028.github.io/KMeansExample"><img width=200 src="data/img/ico.ico" alt="KMeansExample"></a>
    <p style="font-family: roboto, calibri; font-size:12pt; font-style:italic"> A sleek CLI app for KMeans Clustering </p>
    <a href="https://madewithlove.org.in" target="_blank">Made with <span style="color: #e74c3c">&hearts;</span> in India</a>  
    <br>
    <a href="https://github.com/warmachine028/KMeansExample/releases/"> <img src="https://img.shields.io/github/v/release/warmachine028/KMeansExample"></a>
    <br>
    <a> <img src="https://img.shields.io/github/stars/warmachine028/KMeansExample?color=lawngreen"></a>
    <a href= "https://github.com/warmachine028/KMeansExample/tree/master/LICENSE"><img src="https://img.shields.io/github/license/warmachine028/KMeansExample?color=orange"></a>
    <a href="https://github.com/warmachine028/KMeansExample/network/members"><img src="https://img.shields.io/github/forks/warmachine028/KMeansExample?color=cyan"></a>
</div>

# [KMeansExample](https://github.com/warmachine028/KMeansExample)

## Whats new?

- Added a GUI Prompt component to select a csv file
- Added plot for cluster epicenters

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [TODOs](#todos)
- [ChangeLog](#changeLog)
- [Preview](#preview)
- [License](#license)

## Introduction

KMeansExample is a simple implementation of the K Means clustering Algorithm in Python.

### Features

- Accurate division of clusters
- Graphic preview of clusters
- Naming of clusters
- Making Predictions

## Getting Started

### Requirements

KMeansExample Requires these bare-minimum things to work:

- [python 3.x] - Python 3 and above
- [matplotlib] for previewing the data . If not installed

```sh
$ pip install matplotlib
```

### Installation

KMeansExample doesn't need to be installed, just run main.py with no parameters.

```sh
$ python3 main.py
```

## Usage

```sh
$ python3 main.py
 **
 Welcome to KMeansExample.
 **

```

A GUI prompt will open to let you choose a csv file

```sh
$ python3 main.py
 **
 Welcome to KMeansExample.
 **

Working on student records at data/test.csv  ..



  * (1) for Previewing the records
  * (2) for Proceeding with training
  * (3) for Exiting the predictor
Enter action:

```

hereafter, the menu interface will guide you.

## TODOs

- Reduce and optimise code

## ChangeLog

- See [CHANGELOG]

## Preview

- Rich plotting of Clusters in a dataset _students.csv_
  ![Preview]

## License

- See [LICENSE]

**Syed Nasim, 2021**

[matplotlib]: https://pypi.org/project/matplotlib/
[python 3.x]: https://www.python.org/download/releases/3.0/
[license]: https://github.com/warmachine028/KMeansExample/tree/master/LICENSE
[changelog]: https://github.com/warmachine028/KMeansExample/tree/master/.github/CHANGELOG.md
[preview]: data/img/Students.png
