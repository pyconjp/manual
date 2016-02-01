# manual

- PyCon JP organizers manual
- http://manual.pycon.jp/

## How to build

```
$ git clone https://github.com/pyconjp/manual.git
$ cd manual
$ virtualenv env
$ . env/bin/activate
(env)$ pip install -r requirements.txt
(env)$ make html
(env)$ open build/html/index.html
```
