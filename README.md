# nem_library
DUID and name mappings of common datasets of the NEM.

## About
The file `duid_map.csv` is a manually updated file with mappings of Station Name and DUIDs from different AEMO datasets. Often there is mismatch in naming conventions which make it difficult to easily collect and process data. Hence maintaining this file overcomes that issue.

## Usage
Download the .zip file for this repository. Use pandas pd.read_csv({filepath}) specifying the filepath of the `duid_map.csv` or other `.csv` files found in the archive

## Notice
This is not a production-grade package or source. These are unofficial files, maintained for my own use. Use at your own discretion. 