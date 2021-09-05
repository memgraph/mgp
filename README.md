# mgp

Pypi package used for type hinting when creating MAGE modules.


# how to publish new versions
## prerequisites
1. installed poetry
```
pip install poetry
```
2. set up [API tokens](https://pypi.org/help/#apitoken)
3. be a collaborator on [pypi](https://pypi.org/project/mgp/)

## making changes
1. make changes to the package
2. bump version in `pyproject.tml`
3. `poetry build`
4. `poetry publish`
