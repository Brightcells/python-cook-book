# Requirements.txt

## Create

```shell
pip freeze | sort > requirements.txt  # alias sort='LC_ALL=C sort'
pip freeze | LC_ALL=C sort > requirements.txt
```

## Sort

```shell
sort requirements.txt -o requirements.txt  # alias sort='LC_ALL=C sort'
LC_ALL=C sort requirements.txt -o requirements.txt
```

## Install

```shell
pip install -r requirements.txt
```

## References

[1] KENNETH REITZ, [A Better Pip Workflow™](https://www.kennethreitz.org/essays/a-better-pip-workflow)