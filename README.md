# miniproject1SergioGabrielJiaweiKun

### INF601 - Advanced Programming in Python
### Sergio Gabriel Jiawei Kun
### Mini Project 1

## Description

* Historical closing prices of the last 10 trading days (obtained through yfinance module which accesses yahoo finance data), graphed using matplotlib and numpy.
* The first 5 stock tickers are using example companies, user may alter to their own needs in the following lines in main.py:
```python
tickers = ["AAPL", "GOOG", "IBM", "TSLA", "NFLX"]
```
## Getting Started
### pip install instructions
Ensure that the following lines are run for the program to function.
This pip installs all the required packages listed in requirements.txt.
```python
pip install -r requirements.txt
```

### Dependencies

* This version was developed using Python 3.12, and will run best in this version.
* Please confirm that the required modules are installed to use this program, which are contained in required.txt
and listed here: 
```python
contourpy==1.2.0
cycler==0.12.1
fonttools==4.48.1
kiwisolver==1.4.5
matplotlib==3.8.2
numpy==1.26.4
packaging==23.2
pillow==10.2.0
pyparsing==3.1.1
python-dateutil==2.8.2
six==1.16.0
yfinance==0.2.36
```
(most are requirements for matplotlib itself to run, and if you ran the pip install instructions above properly, these should all be present already.)

### Installing

* No installing required other than python and the relevant libraries mentioned above

### Executing program
The following runs the main.py file.
```python
python main.py
```
* If there is an error, please refer to the above required packages in order for the program to run smoothly.

## Help

Please refer to the dependencies section above and ensure that all python versions, and library versions are as listed.


## Authors

Contributors names and contact info
* Sergio Gabriel Jiawei Kun
  * kunsergio117@outlook.com

## Version History
* 0.1
    * Initial Release
* See [commit change]() or See [release history]()

## License
* No licencing
## Acknowledgments
* [Matplotlib](https://matplotlib.org/stable/tutorials/pyplot.html)
* [automatetheboringstuff](https://automatetheboringstuff.com/2e/chapter9/)
