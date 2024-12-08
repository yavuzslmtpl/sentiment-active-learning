# Tested Host
Mac M1 Pro Max

# Prepare
```
cd $WORKSPACE
python3 -m venv ./venv
source ./venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

# Run
```
jupyter notebook
```

### Install for Model Graph
```
brew install graphviz
```

### Google Colab
```
%%shell
pip install datasets
```