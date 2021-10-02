# faq
to help you at any time

## Table of Contents
1. [Conda Environment](conda-environment)

## Conda Environment
- Why my environment is not isolated? Why is there local site package in my environment?

> Remove all local site packages using this command
> 
> `export PYTHONNOUSERSITE=true`
> 
> You can check all the python paths using this command
> 
> `python -c "import sys; print(sys.path)"`

- My home directory / default location for conda packages disk is almost full. How can I create an environment in other locations? How can I specify the location?

> `conda create --prefix /path/env_name python=x.x`
> 
