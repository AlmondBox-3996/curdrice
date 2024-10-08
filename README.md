<h2 align= 'center'>ML Workflow Automation Tool</h2>

The main goal is to simplify the machine learning workflow for users with different levels of
expertise, through a CLI app. We ask the user for certain inputs like the dataset file or folder,
and the type of ML problem and target variable (if necessary). We then perform standard data preprocessing (not dataset specific)
and feature selection (if necessary), and train relevant models for the data and present a comparative analysis
of the models trained, along with downloadable model weight files in the joblib format.

<span align = 'center'>
<a href="https://www.python.org/"><img src="https://img.shields.io/badge/built%20with-Python3-blue.svg" alt="built with Python3" /></a>
<a href="https://badge.fury.io/py/tizori-cli"><img src="https://img.shields.io/pypi/v/tizori-cli?color=blue&label=pypi%20package" alt="PyPI version" height="18"></a>
</span>

## Key Features
- [x] Compare various machine learning algorithms
- [x] Performance comparison
- [x] One line CLI command
- [x] All model files stored as a zip of joblib files

## Preview
![curdrice](./assets/preview.png)

## Deployment

Find out which ML model suits your needs by installing our package from [pypi](https://pypi.org/project/curdrice/0.1/#description)

```bash
pip install curdrice
```

## Usage

Use the following command for help -
```bash
curdrice --help
```
Template code
```bash
curdrice -p <db_path> -d <zip_name> <type> <target>
```

## Acknowledgements

- [Numpy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [Openpyxl](https://openpyxl.readthedocs.io/en/stable/)
- [Scikit Learn](https://scikit-learn.org/stable/)
- [Scikit Learn Extra](https://scikit-learn-extra.readthedocs.io/en/stable/)
- [Joblib](https://joblib.readthedocs.io/en/stable/)

## Authors

[@hrishitb](https://www.github.com/Hrishit-B) - [@pranayobla](https://www.github.com/pranay-obla) - 
[@shriharik](https://www.github.com/RiriSensei) - [@ankitthomas](https://www.github.com/AlmondBox-3996)