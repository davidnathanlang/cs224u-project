# Modeling Student Response Times: Towards Efficient One-on-one Tutoring Dialogues 

## Setup
1. Create a virtual environment called `rt`:
```
conda create -n rt python=3.6 anaconda
```
To enter the environment run
```
source activate rt
```
To exit the environment run
```
source deactivate rt
```

2. Enter the newly created virtual environment
3. Install package requirements
```
pip install -r requirements.txt
```

4. Install package
```
python setup.py install
```

**Note:** You will have to repeat steps 3. and 4. throughout development as we add new dependencies and modules.

## Project Structure

- *requirements.txt* - make sure to update this file every time you add a new import!
- *data/* - directory that will contain all data.
- *runs/* - directory to store training run outputs.
- *src/* - directory for all source code (e.g. models, trainers, analysis scripts etc.)
- *src/config.py* - central location for any project structure constants (e.g. paths to data). This is not intended for model parameters.
