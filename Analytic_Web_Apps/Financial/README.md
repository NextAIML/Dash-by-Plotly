## Instructions

To get started, first clone this repo:

```
git clone https://github.com/NextAIML/Dash-by-Plotly.git 
cd Analytic_Web_Apps/Financial
```


Create and activate a conda env:
```
conda create -n analytic-financial python=3.7.6
conda activate analytic-financial
```

Or a venv (make sure your `python3` is 3.6+):
```
python3 -m venv venv
source venv/bin/activate  # for Windows, use venv\Scripts\activate.bat
```

Install all the requirements:

```
pip install -r requirements.txt
```

You can now run the app:
```
python app.py
```

and visit http://127.0.0.1:8050/.