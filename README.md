PullYou is a tool for opening the PR associated with a given git hash.

Usage
--------
```
$ pullyou 2aaf764552e012ac33cd7b2d6

$ pullyou 2aaf76455 --repo transcom/mymove
```

Releasing
-------------
```
$ python setup.py sdist bdist_wheel
$ twine upload dist/* [-r testpypi]
$ rm -rf dist/*
* tag the release
* bump the version number
```
