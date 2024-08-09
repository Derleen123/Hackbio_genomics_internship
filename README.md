# Gene Sequence Analysis Script

This repository contains a Bash script to download a gene sequence from NCBI, analyze the nucleotide composition, and calculate the GC content. The script also creates a summary file with the counts of each nucleotide.

## Script Overview

The script performs the following tasks:

1. **Download Gene Sequence**: Fetches the FASTA sequence of the gene from NCBI using the provided URL.
2. **Count Nucleotides**: Counts the number of occurrences of each nucleotide (A, G, C, T) in the sequence.
3. **Calculate GC Content**: Calculates the percentage of the sequence that is composed of G and C nucleotides.
4. **Create Summary File**: Outputs the nucleotide counts into a file named `derleen.fasta`.

## Prerequisites

To run this script, you'll need:
- A Unix-like environment (e.g., Linux, macOS).
- Basic command-line tools like `wget`, `awk`, `grep`, `wc`, `bc`, and `nano`.

## Usage

1. **Clone the Repository** (if applicable):
   ```bash
   git clone https://github.com/your-username/repository-name.git
   cd repository-name
