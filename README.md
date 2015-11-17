# zipfuzz

Simple script for fuzzing PKZip file(https://users.cs.jmu.edu/buchhofp/forensics/formats/pkzip.html), easily editable.

Usage: zipfuzz.py [options]

Options:

  -h, --help            show this help message and exit
  
  -f FILE, --file=FILE  input ZIP file
  
  -s SEED, --seed=SEED  input for seed value
  
It takes as input a zip file and produces as output another fuzzed zip file.
