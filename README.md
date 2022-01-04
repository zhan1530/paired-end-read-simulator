## General info
A simple next generation paired-end sequencing read simulator.
	
## Technologies
The simulaor is created with:
* Python 3

## Installation
```
git clone https://github.com/zhan1530/paired-end-read-simulator.git
cd paired-end-read-simulator/
```
## Required options 
* -i STR reference genome
* -n INT number of read 
* -m INT mean of the insert size 
* -d INT standard deviation of the insert size
* -l INT read length

## Examples of use
To run this project, python 3 is required.
```
python program_rev_2022.01.py -i EF1813.fasta -n 10000  -m 500 -d 50 -l 75
```
