# CS50 DNA Analyzer

This is a Python script built for Harvard's CS50x course. It determines a person's identity by comparing a DNA sequence against a database of short tandem repeats (STRs).

## Files

- `dna.py`: The main Python script that performs the DNA analysis.
- `data.csv`: A sample DNA database with STR counts for individuals.
- `sequence.txt`: A sample DNA sequence to be analyzed.

## How it works

The script:
1. Loads a database of people and their STR counts from a CSV file.
2. Loads a DNA sequence from a text file.
3. Finds the longest run of each STR in the DNA sequence.
4. Compares the STR counts to the database to identify a matching person.

## Usage

```bash
python dna.py data.csv sequence.txt
