# Zip Crack (Forked from https://github.com/Royz2123/Zip-Cracker)

A brute force approach for unlocking a password protected zip file
Created for educational purposes only, as part of IBM's Capture the flag

## Running the code

Simply run the following line in your command line. Notice required and optional arguments.

```bash
For brute force:
python main.py <zip file> <min_length> <max_length> [<-u UPPERCASE> <-l LOWERCASE> <-d digits> <-s symbols>]

For Dictionary:
python main.py <zip file> <min_length> <max_length> [<-d DICTIONARRY ATTACK> <dict file>]
```

## Algorithms

1) Simple Brute force
2) Dictionary

## Credits

All credits go to https://github.com/Royz2123
I just forked it for my personal use :
- correcting some minor problems due to language evolution
- adding min_length in CLI options
- (and potentially custom characters list)
