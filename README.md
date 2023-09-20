# analysis-system-env-nightlies Environment Lock Files

Nightly solves of the IRIS-HEP Analysis System tool environments

To install environments from these lock files either download them from this page or direct your installer towards their url.

**Report issues on GitHub:** [github.com/iris-hep/analysis-system-env-nightlies](https://github.com/iris-hep/analysis-system-env-nightlies)

## Usage Examples

**Python 3.11 pip example:**

```
python -m pip install --upgrade --require-hashes --requirement https://iris-hep.org/analysis-system-env-nightlies/iris-hep/3.11/requirements.lock
```

**Python 3.11 conda-lock example:**

```
micromamba create --name iris-hep --file https://iris-hep.org/analysis-system-env-nightlies/iris-hep/3.11/conda-lock.yml
```

or

```
# conda-lock install doesn't work with urls
curl -sLO https://iris-hep.org/analysis-system-env-nightlies/iris-hep/3.11/conda-lock.yml
# c.f. conda-lock install --help
conda-lock install --micromamba --name iris-hep conda-lock.yml
```

## scikit-hep

* Python 3.11
   - [requirements.txt (high level)](https://iris-hep.org/analysis-system-env-nightlies/scikit-hep/3.11/requirements.txt)
   - [requirements.lock](https://iris-hep.org/analysis-system-env-nightlies/scikit-hep/3.11/requirements.lock)
   - [environment.yml (high level)](https://iris-hep.org/analysis-system-env-nightlies/scikit-hep/3.11/environment.yml)
   - [conda-lock.yml](https://iris-hep.org/analysis-system-env-nightlies/scikit-hep/3.11/conda-lock.yml)
* Python 3.8
   - [requirements.txt (high level)](https://iris-hep.org/analysis-system-env-nightlies/scikit-hep/3.8/requirements.txt)
   - [requirements.lock](https://iris-hep.org/analysis-system-env-nightlies/scikit-hep/3.8/requirements.lock)
   - [environment.yml (high level)](https://iris-hep.org/analysis-system-env-nightlies/scikit-hep/3.8/environment.yml)
   - [conda-lock.yml](https://iris-hep.org/analysis-system-env-nightlies/scikit-hep/3.8/conda-lock.yml)

## iris-hep

* Python 3.11
   - [requirements.txt (high level)](https://iris-hep.org/analysis-system-env-nightlies/iris-hep/3.11/requirements.txt)
   - [requirements.lock](https://iris-hep.org/analysis-system-env-nightlies/iris-hep/3.11/requirements.lock)
   - [environment.yml (high level)](https://iris-hep.org/analysis-system-env-nightlies/iris-hep/3.11/environment.yml)
   - [conda-lock.yml](https://iris-hep.org/analysis-system-env-nightlies/iris-hep/3.11/conda-lock.yml)
* Python 3.8
   - [requirements.txt (high level)](https://iris-hep.org/analysis-system-env-nightlies/iris-hep/3.8/requirements.txt)
   - [requirements.lock](https://iris-hep.org/analysis-system-env-nightlies/iris-hep/3.8/requirements.lock)
   - [environment.yml (high level)](https://iris-hep.org/analysis-system-env-nightlies/iris-hep/3.8/environment.yml)
   - [conda-lock.yml](https://iris-hep.org/analysis-system-env-nightlies/iris-hep/3.8/conda-lock.yml)
