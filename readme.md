# About this version
This version of the script works with Python 3+, as opposed to the original which only works with Python version 2

# About Duplicate Files.
This script will scan a directory tree looking for duplicate files, it uses a two stage approach of comparing file sizes and then hashes of file contents to find duplicates.

## Running Duplicate files.
An example of running this script to just list all the duplicate files would be:

```
python DuplicateFiles.py -root /Users/Daniel/Documents
```

An example of running this script to list and delete all the duplicate files would be:

```
python DuplicateFiles.py -root /Users/Daniel/Documents -remove
```
