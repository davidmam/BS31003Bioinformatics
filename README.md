## BS31003 Bioinformatics

This page contains links to Jupyter notebooks with code for the analyses demonstrated in the lectures. 
Feel free to play around and try things out. These are designed to run on MyBinder so will require no software installation 
on your part. You can however download them and explore on your own machine if you wish.

An introduction to coding in Python can be gained for credit in module BS32031

### Notebook 1 - GC skew analysis

In this notebook we look at GC skew, the difference in the G to C ratio between the two strands. 
Overall the genome will have equal G and C as they are complementary bases but when a region of single strand is 
considered this is not the case. The GC skew arises from differential mutation rates between the leading and lagging strands,
and can give clues as to the structure of the genome.  

Access the notebook here [GC-Skew.ipynb](GC-Skew.ipynb) or click the button to run at mybinder.org [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/davidmam/BS31003Bioinformatics/HEAD?filepath=GC-Skew.ipynb)

### Notebook 2 - kmer analysis

In this notebook we look at how frequently short DNA 'words' are reused within and between genomes. Direct alignment of genomes 
is challenging unless they are very closely related as the evolutionary processes include genome rearrangement. However the frequency 
of short 'words' in the genome changes more slowly and can give insight into species families with incomplete or unassembled genomes.

Access the notebook here [./k-mers.ipynb](k-mers.ipynb) or click the button to run at mybinder.org [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/davidmam/BS31003Bioinformatics/HEAD?filepath=k-mers.ipynb)

### Using Jupyter notebooks

Jupyter notebooks are dynamic web based documents divided into cells. These cells can be edited and run to produce output by 
highlighting the cell, then pressing `CTRL` and `ENTER` together.
To run Jupyter notebooks you can either download and install [Anaconda](https://Anaconda.org), then launch Jupyter notebooks on your own machine, 
or run these notebooks via mybinder.org at this link [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/davidmam/BS31003Bioinformatics/HEAD). 
