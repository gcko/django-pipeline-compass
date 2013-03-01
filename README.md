# Django Pipeline Compass

[Compass](http://compass-style.org/) compiler for django-pipeline using the original Ruby gem.

## Requirements

- Compass: `gem install compass`

## Installation

```
pip install git+https://github.com/gcko/django-pipeline-compass.git
```

## Usage

```python
# settings.py

PIPELINE_COMPASS_BINARY = '/usr/local/bin/compass'   # default: '/usr/bin/env compass'
PIPELINE_COMPASS_ARGUMENTS = '-c path/to/config.rb'  # default: ''

PIPELINE_COMPILERS = (
  'pipeline_compass.compass.CompassCompiler',
)
```
