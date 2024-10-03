## Run in Local

### 1. Install Packages Manager
Reference: <https://blog.kyomind.tw/python-poetry/#Poetry-%E6%98%AF%E4%BB%80%E9%BA%BC%EF%BC%9F>
1. ``$ pip3 install poetry``
2. ``$ poetry init``
3. ``$ poetry config virtualenvs.in-project true``
4. ``$ poetry env use python``
5. ``$ poetry shell``

### 2. Install Notebook Kernel
1. ``$ poetry add ipykernel``
2. ``$ poetry run python -m ipykernel install --user --name <ENV NAME>``

### 3. Launch Jupyter
1. Run in Visual Studio
2. ``$ jupyter lab``
