# ML-Ops Demo/Assignment
[![codecov](https://codecov.io/gh/Vedha286/cicd-iris/branch/master/graph/badge.svg?token=O0PHAA78UA)](https://codecov.io/gh/Vedha286/cicd-iris)

![check-code-coverage](https://img.shields.io/badge/code--coverage-100%25-brightgreen)


This repository contains code which demonstrates ML-Ops using a `FastAPI` application which predicts the flower class using the IRIS dataset (https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html)

## Running Instructions

- Create a fork of the repo using the `fork` button.
- Clone your fork using `git clone https://www.github.com/Vedha286/cicd-iris.git`
- Install dependencies using `pip3 install -r requirements.txt`. I included 'pytest-cov' in the requirements
- Run application using `python3 main.py`
- Run tests using with coverage `pytest --cov=./`

## CI/CD

- `build` (test) for all the pull requests
- `build` (test) and `upload_zip` for all pushes

## Assignment Tasks (OLD Assignment)

1. Change this README to add your name here: Vedha Krishna Velthapu. Add and commit changes to a new branch and create a pull request ONLY TO YOUR OWN FORK to see the CI/CD build happening. If the build succeeds, merge the pull request with master and see the CI/CD `upload_zip` take place.
2. Add 3 more unit tests of your choice to `test_app.py` and make sure they are passing.
3. Add one more classifier to startup and use only the one with better accuracy.
4. Add the attribute `timestamp` to the response and return the current time with it.
