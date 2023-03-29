# hotspots

The Python implementation of Google's bug prediction algorithm.  
[Bug Prediction at Google | Google Engineering Tools](http://google-engtools.blogspot.com/2011/12/bug-prediction-at-google.html)

There is a difference that the original algorithm uses only bug fix commits, whereas this tool uses all commits.


## Requirements

- Git
- Python 3.7+


## Installation

Place `hotspots` to PATH.


## Usage

```sh
# all files under current directory
hotspots

# include
hotspots --include 'src/*'

# exclude
hotspots --exclude '*.md'
```

Run `hotspots -h` to show help.
