## Virtual Environment
```python3 -m venv --system-site-packages ./venv
source ./venv/bin/activate
pip install --upgrade pip
pip list  
pip install --upgrade tensorflow
python -c "import tensorflow as tf;print(tf.reduce_sum(tf.random.normal([1000, 1000])))"

pip install jupyter
jupyter notebook

deactivate // when you are out
```
