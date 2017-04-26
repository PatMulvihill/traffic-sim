# Traffic Simulator


### Installation  
To install, first make sure you have python 3.6.1 and virtualenv. Next, lets 
set up your virtual env and install deps.

```bash
# Create and activate
virtualenv -p python3 venv
source venv/bin/activate

# For Windows users:
virtualenv venv
source venv/Scripts/activate

# Check version
python --version
# Python 3.6.1

# Install deps
pip install -r requirements.txt
```

### Running  
At this point, your environment is set up to start hacking away! To run the 
app just run:

```bash
python __main__.py
```

And don't forget to deactivate your venv when you leave the directory to go do
other stuff:
```bash
deactivate
```
