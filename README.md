# Install

**Conda VENV**
```
# Download the conda environment package from the in-house server:
# * address 10.24.116.85
# * port 1172 
# * path /home/lwh/fast-prefill.tar.gz

# install the conda environment
$ mkdir -p fast-prefill
$ tar -xzf my_env.tar.gz -C fast-prefill

$ ./fast-prefill/bin/python
$ source fast-prefill/bin/activate
```

**Github Repo**
```
$ git clone https://github.com/wenhaoli-xmu/fast-prefill.git
```

**Instsall Repo**
```
$ cd fast-preill
$ pip install -e .
```


# Test
```
$ python test_ppl/test.py --env_conf test_ppl/hybirdx-1.json
```

