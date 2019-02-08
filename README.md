### lcov-badger
This script generates a SVG badge from **lcov** coverage data (.info text file), which is created by **lcov**, **geninfo** and other tools.

Example output:
![Sample SVG](sample.svg)

### Usage
Just drop the **lcov-badger.py** file where you need it, pass the path to .info file and the path for output:
```
python lcov-badger.py /awesome/project/cover.gcda.info /docs/coverage.svg
```

### Credits
The SVG template is created from flat style SVG taken from [shields.io](https://shields.io).