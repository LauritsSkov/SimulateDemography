# SimulateDemography
Plot coalescent distribution to the outgroup for introgressed and ingroup states

## Requirements
You will need numpy, matplotlib, msprime, tskit, demes, demesdraw and hmmix

## Running the examples
In order to run examples from small paper:

```bash
python sim.py -demography=Demography_a -iterations=10000
python sim.py -demography=Demography_b -iterations=10000 -admixpop=outgroup
python sim.py -demography=Demography_c -iterations=10000
python sim.py -demography=Demography_d -iterations=10000
python sim.py -demography=Demography_e -iterations=10000 -outgroupsize=1
python sim.py -demography=Demography_f -iterations=10000 
```
