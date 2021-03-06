# FAQT
Flywing Analysis and Quantification tool 
![Image](https://github.com/kapoorlab/FAQT/blob/master/images/faqtD.png)
![Image](https://github.com/kapoorlab/FAQT/blob/master/images/faqtA.png)
![Image](https://github.com/kapoorlab/FAQT/blob/master/images/faqtC.png)
![Image](https://github.com/kapoorlab/FAQT/blob/master/images/faqtB.png)
## Installation
This package can be installed by 


`pip install --user faqt`

If you are building this from the source, clone the repository and install via

```bash
git clone https://github.com/kapoorlab/FAQT/

cd faqt

pip install --user -e .

# or, to install in editable mode AND grab all of the developer tools
# (this is required if you want to contribute code back to NapaTrackMater)
pip install --user -r requirements.txt
```


### Pipenv install

Pipenv allows you to install dependencies in a virtual environment.

```bash
# install pipenv if you don't already have it installed
pip install --user pipenv

# clone the repository and sync the dependencies
git clone https://github.com/kapoorlab/FAQT/
cd faqt
pipenv sync

# make the current package available
pipenv run python setup.py develop

# you can run the example notebooks by starting the jupyter notebook inside the virtual env
pipenv run jupyter notebook
```

Access the `example` folder and run the cells.


## Requirements

- Python 3.7 and above.


## License

Under MIT license. See [LICENSE](LICENSE).

## Authors

- Varun Kapoor <randomaccessiblekapoor@gmail.com>
- Blanco Obregon Dalmiro
- Laura Boulan
