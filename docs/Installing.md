[<Back to Table of Contents](../README.md)
# Installing MindsDB


Before you begin, you need **[python>=3.7](https://realpython.com/installing-python/)** or **[Conda Python3](https://www.anaconda.com/download/)**, and make sure you have the **latest pip3**
```bash
curl https://bootstrap.pypa.io/get-pip.py | python3
pip3 install --upgrade pip
```

Once that, you can install MindsDB
##### On Mac or Linux 

```bash
pip3 install mindsdb --user
```

##### On Windows 10


Install Conda [download here](https://www.anaconda.com/download/#windows).
 
 and then run the **anaconda prompt**: 

```bash
conda install -c blaze 
conda install -c sqlite3 
conda install -c peterjc123 
conda install -c pytorch
curl -o reqs.txt https://raw.githubusercontent.com/mindsdb/main/master/requirements-win.txt
pip install --requirement reqs.txt
pip install mindsdb --no-dependencies
```

