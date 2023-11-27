# im writing all this shit again cuz its bad yessss i already have it improved just no time to make the readme and additional shit yk yk

<div align="center" id="top"> 
  <img src="./img.png" alt="RoseGuardian Logo" />
  <br />
  <br />
  <p>:rose: A Python Code Obfuscator :shield:</p>
</div>

<h1 align="center">Rose-Obf</h1>

<p align="center">
  <img alt="Top Language" src="https://img.shields.io/github/languages/top/DamagingRose/RoseGuardian">
  <img alt="Stars" src="https://img.shields.io/github/stars/DamagingRose/RoseGuardian">
  <img alt="License" src="https://img.shields.io/github/license/DamagingRose/RoseGuardian">
</p>

<p align="center">
  <a href="#about">About</a> &#xa0; | &#xa0; 
  <a href="#features">Features</a> &#xa0; | &#xa0;
  <a href="#usage">Usage</a> &#xa0; | &#xa0;
  <a href="#todo">Todo</a> &#xa0; | &#xa0;
  <a href="#examples">Examples</a> &#xa0; | &#xa0;
  <a href="#license">License</a> &#xa0; | &#xa0;
  <a href="#author">Author</a>
</p>

<br>

<div id="about"></div>

## About :rose:

Rose-Obf is a powerful Python code obfuscator designed to safeguard your intellectual property. It employs advanced techniques to obscure your source code, making it significantly more challenging for potential reverse engineers to understand or modify.

<div id="features"></div>

## Features :sparkles:

- :closed_lock_with_key: Strong Class and Function Renaming
- :inbox_tray: Code Compression with zlib
- :package: Create Marshalized Objects
- :scroll: Remove Comments

<div id="usage"></div>

## Usage :rocket:

For optimal obfuscation, it is recommended to set the junk layers to 10 and utilize obfuscation method 1.

```bash
# Clone the project
$ git clone https://github.com/DamagingRose/RoseGuardian.git

# Navigate to project directory
$ cd RoseGuardian

# Run the project
$ python RoseGuardian.py <your_file> <junk_layers> <obfuscation_method>
```

<div id="todo"></div>

## Todo :pencil:

- [ ] Rename Variables and Parameters
- [ ] Remove Docstrings
- [ ] Add library support

<div id="examples"></div>

## Examples :clipboard:
**Command**:
```bash
# Obfuscates test.py with 2 junk layers and obfuscation method 1
$ python RoseGuardian.py test.py 2 1
```

**Before** (test.py):
```python
import random, string
import base64

def hello():
   
    global var
    
    var = 'hii' # hi
    
    print(var)

print(random.choices(string.ascii_letters, k=5))

hello()

print(base64.b64encode(var.encode('utf-8')))

class banana(): # banana
    ss = b'\nPEWPEW'

    print(ss)

def counter(num):

    for i in range(num):

        print('dogs are cool!')

counter(5)

# lalala
```

**After** (obfuscated_test.py):
```python
__obfuscator__ = 'RoseGuardian'
__author__ = 'gumbobr0t'
__github__ = 'https://github.com/DamagingRose/RoseGuardian'
__license__ = 'EPL-2.0'


def complicated_function():
    result = 0
    for i in range(1, 11):
        result += i**3 - i**2 + i
    return result

class ComplicatedAlgorithm:
    def __init__(self):
        self._ = None
        self.__ = None

    def execute(self):
        pass

def execute_complicated_algorithm():
    _ = ComplicatedAlgorithm()
    _._ = lambda _, __: _.___(__) + _.___(_.___(_.__(_.___(_.__))))

def analyze_data():
    import random
    
    data = [random.randint(1, 100) for _ in range(10)]
    result = sum(data) / len(data)


import marshal, base64, zlib; exec(marshal.loads(zlib.decompress(base64.b64decode(b'eJxNkNFLwzAQxudr/orzKQ3MPm1DhD6piAxkIFgRQdI06W5rcyOXDfzvTdeADYHku3C/77vw4WaxwOFEIULQvqVhCRwD+k7kaqPZblZCiNY6IPdlXt/x4C6FehCQVtdTo3u46HCV6YQK5B5RXvUpoWKRqioRJjHZlGZPaCwXk1up2SD+9DZGG3gJx2qtlJjb5e4pTtlsVtYbau3ILvNVnqO7u5dKjWam18zwgbXZ6if/8jjFTaUKGvntd8912vOQzCpPuXVvu/r3k45D4c9DHtRRAAT04zd1dvbwT5AtdQw6WDBE/a0ceTPWWok/MtZvYw=='))))
def gravimetric_flux():
    pass

class warp_inverter:
    def __init__(self):
        self._ = None
        self.__ = None

    def subspace_transducer(self, _):
        return self.subspace_transducer(_)

def chronal_conduit():
    _ = warp_inverter()
    _._ = lambda _, __: _.___(__) + _.___(_.___(_.__(_.___(_.__))))

def singularity_stabilizer():
    _ = gravimetric_flux()
    _._ = lambda _, __: _.___(__) + _.___(_.___(_.__(_.___(_.__))))

def entropic_reactor():
    pass
```


<div id="license"></div>

## License :page_facing_up:

This project is licensed under the EPL-2.0 license.

<div id="author"></div>

## Author :mortar_board:

Developed with :heart: by [gumbobrot](https://github.com/gumbobr0t)

<a href="#top">Back to top</a>
