## PV251\_viz

Vizualization project to PV251 seminar. Vizualization of OLS, GLS regression and Cochranne-Orcutt method.

## How to install:
Supposing you have some bash and Python3 in it

Go to a directory, where you whish this a new home
```
git clone https://github.com/turak97/PV251_viz.git

cd PV251_viz/

python3 -m venv env

source env/bin/activate

pip install -r requirements.txt 
```
If you get error like: error: invalid command 'bdist_wheel', no worry. Wait a minute and if nothing happens,
press ctrl^C and try pip install -r requirements.txt again. All dependencies should be now satisfied. 
Then try run the code.
## How to run:
Make sure you are in folder PV251\_viz
```
source env/bin/activate

python3 main.py
```
You can also explore your own datasets. Check
```
python3 main.py --help
```
