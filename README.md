# ids706_python_template
Mini project9 for ids706: 
- Cloud-Hosted Notebook Data Manipulation


## Requirements
- Python 3.8+
- Virtual environment (optional but recommended, already set up as env in Makefile)
- Packages listed in `requirements.txt` including 


## Set up
1. Run `make setup` to set up the virtual environment for the project.
note: only need to set up the environment once

2. Run `make install` to install all packages listed in requirement.txt

3. Run `make lint` to check up the style

4. Run `make format` to check up the format

5. Run `make test` to test the main.py

6. Run `make all` to finish all the set up operations at the same time


## Set up a cloud-hosted Jupyter Notebook
- In this project, google colab is used as the cloud-host plaatform for my jupyter notebook `ids706_project9.ipynb`

## Perform data manipulation tasks on a sample dataset
1. The dataset [Occupational Employment and Wage Statistics.csv](https://raw.githubusercontent.com/nogibjj/ids706_project9_ll442/4912522c139e982753fcd51a5226ad58ab5c3195/OccupationalEmploymentandWageStatistics.csv) is downloaded from the NC work website and used for this project

2. Certain data manipulation is carried out on our dataset for better understanding

3. Statistical information in the dataset has been visuliazed


## Structure
.
├── Makefile
├── OccupationalEmploymentandWageStatistics.csv
├── README.md
├── __pycache__
│   ├── describe_statistics.cpython-311.pyc
│   └── test_stat.cpython-311-pytest-7.4.2.pyc
├── ids706_project9.py
├── main.py
├── ouput.png
├── output.log
├── requirements.txt
└── test_main.py


## CI/CD
GitHub Actions are configured for Continuous Integration and Continuous Deployment. See `.github/workflows/ci_cd.yml` for details.




