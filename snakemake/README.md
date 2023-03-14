1. Through the command line
snakemake --cluster "sbatch -A CLUSTER_ACCOUNT -t CLUSTER_TIME -p CLUSTER_PARTITION -N CLUSTER_NODES -J JOBNAME" --jobs NUM_JOBS_TO_SUBMIT 

2. Using a config file


Source: https://bluegenes.github.io/snakemake-via-slurm/
