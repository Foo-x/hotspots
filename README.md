# hotspots

The Python implementation of Google's bug prediction algorithm.  
[Bug Prediction at Google | Google Engineering Tools](http://google-engtools.blogspot.com/2011/12/bug-prediction-at-google.html)

There are differences between the original algorithm and this tool.

- Original
    - uses only bug fix commits
    - does not normalize scores
- This tool
    - uses all commits
    - normalize scores
        - highest score will be always 1


## Requirements

- Git
- Python 3.7+


## Installation

Place `hotspots` to PATH.


## Usage

```sh
# all files under current directory
hotspots

# include/exclude
hotspots --include 'src/*' 'tests/*' --exclude '*.md' '*.svg'
```

Run `hotspots -h` to show help.
