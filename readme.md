Phaseme
======

PhaseMe is a tool set to assess the quality of the per read phasing information and help to reduce the errors during this process. 


# Quickstart

1- You require your VCF file to be read based phased, which can be generated by e.g. WhatsHap.

2- Run PhaseMe to obtain stats and improve the quality of phase blocks.

```
python utilities/qc.py  utilities/precomputed/pair_${chr}.txt file.vcf

python utilities/improver.py utilities/precomputed/pair_${chr}.txt file.vcf 
```


# Installation Test

Please try our sample data to establish the correctness of the pipeline instaltion. This can be found in the folder `example`.


For generating individual-specific pair list, consider checking folder `linkage`.

# Citation:

Please see and cite our manuscript: "PhaseME: automatic assessment of phasing quality and phasing improvement"




