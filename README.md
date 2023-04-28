# degrade-fastq

This tool will artificially degrade the quality of fastq files. It is intended to be used in conjunction with fastq downsampling tools such as 
[rasusa](https://github.com/mbhall88/rasusa) to aid in preparing datasets for genomic QC threshold determination.

## Development status
Work-in-progress. Not ready for routine use. Not all features implemented.

## Usage

```
usage: degrade-fastq [-h] [-1 R1] [-2 R2] [-p PROPORTION_READS_DEGRADED] [-t DEGRADATION_THRESHOLD] [-s DEGRADATION_SLOPE] [-i DEGRADATION_INTENSITY]

optional arguments:
  -h, --help            show this help message and exit
  -1 R1, --R1 R1
  -2 R2, --R2 R2
  -p PROPORTION_READS_DEGRADED, --proportion-reads-degraded PROPORTION_READS_DEGRADED
  -t DEGRADATION_THRESHOLD, --degradation-threshold DEGRADATION_THRESHOLD
  -s DEGRADATION_SLOPE, --degradation-slope DEGRADATION_SLOPE
  -i DEGRADATION_INTENSITY, --degradation-intensity DEGRADATION_INTENSITY
```
