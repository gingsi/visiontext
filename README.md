# visiontext

<p align="center">
<a href="https://github.com/gingsi/visiontext/actions/workflows/build_py37.yml">
  <img alt="build 3.7 status" title="build 3.7 status" src="https://img.shields.io/github/actions/workflow/status/gingsi/visiontext/build_py37.yml?branch=main&label=build%203.7" />
</a>
<a href="https://github.com/gingsi/visiontext/actions/workflows/build_py39.yml">
  <img alt="build 3.9 status" title="build 3.9 status" src="https://img.shields.io/github/actions/workflow/status/gingsi/visiontext/build_py39.yml?branch=main&label=build%203.9" />
</a>
<img alt="coverage" title="coverage" src="https://raw.githubusercontent.com/gingsi/visiontext/main/docs/coverage.svg" />
<a href="https://pypi.org/project/visiontext/">
  <img alt="version" title="version" src="https://img.shields.io/pypi/v/visiontext?color=success" />
</a>
</p>

Utilities for deep learning on multimodal data:

* jupyter notebooks / jupyter lab / ipython
* matplotlib
* pandas
* webdataset / tar
* pytorch

## Install

Requires `python>=3.7`

```bash
pip install visiontext
```

## Dev install

Clone repository and cd into, then:

~~~bash
pip install -e .
pip install pytest pytest-cov pylint pytest-lazy-fixture

python -m pytest --cov

pylint visiontext
pylint tests
~~~
