# Getting started
Step 1: Create the environment using conda:
```conda env create -f environment.yml```

Step 2: Activate the environment:
```conda activate nsdf-cookbook```

## Alternative
Instead of using conda, you can also use ```pip```.

Step 1: Create a new virtual environment:
```bash
python -m venv .venv
source .venv/bin/activate
```
Step 2: Install the required libraries:

```bash
python -m pip install jupyterlab matplotlib requests aiohttp bokeh panel xmltodict colorcet boto3 basemap OpenVisus openvisuspy 
```