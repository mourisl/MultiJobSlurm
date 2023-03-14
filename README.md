Notes on how to submit multiple jobs on slurm system.

1. sbatchdrvier

Use one bash as the driver to iterate over the sample list, and sbatch run_program.scr with a subset of samples. 

2. snakemake

Put sample list in the config.ymal file. The Snakemake file is written using T1K as the example.

3. easysbatch

https://github.com/shenwei356/easy_sbatch
