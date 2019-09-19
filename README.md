# Optimized Levenshtein Distance search using Clustering
This is an attempt to optimize the search of words for candidate model while building auto-correct applications. The idea is to minimize the calculation the Ld(Levenshtein distance) as it is computationally expensive. Simple implementation of DBSCAN clustering is being used to form clusters to be queried further.

## Requirements

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the requirements.

```bash
pip install numpy
```


## Usage

```bash
jupyter notebook
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)