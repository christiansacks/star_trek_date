# star_trek_date

## Installation

To install this on your system, the files need to go in certain places;

### bin/* (main script and config file)

Copy the files in bin/* to your $HOME/bin directory or /usr/local/bin or /usr/bin dir (or your chosen dir that's in the $PATH)

### bash.d/* (tab completion script)

Copy the file in bash.d/* to your $HOME/.bash.d directory, and make sure your $HOME/.bashrc sources all files in that dir


## Usage

Usage: star_trek_date <language> [-d|--debug] [-l|--list]


## Examples

'''
$ star_trek_date klingon
Today's date in Klingon is: wejleS jaj 19, jar jar
```

```
$ star_trek_date vulcan
Today's date in Vulcan is: klosh wak 19, t'vash shen
```
