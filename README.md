# sge-wynton

Sun Grid Engine (SGE) profile for cluster execution of Snakemake workflows on the UCSF Wynton cluster. 

Modified from the offical [Snakemake SGE Profile](https://github.com/Snakemake-Profiles/sge)

## Usage

Clone directory into home `/wynton/home/{group}/{user}/`
```
mkdir -p ~/.config/snakemake
cd ~/.config/snakemake
git clone git@github.com:AndrewsLabUCSF/sge-wynton.git
```

Executing workflows 

```
snakemake -j 1 --profile sge-wynton
```
