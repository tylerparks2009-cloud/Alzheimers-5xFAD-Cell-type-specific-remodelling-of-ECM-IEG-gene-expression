# Dataset-to-figures pipeline

Single Jupyter notebook. Run Blocks 1 through 13 in order, one at a time.

Block 5's output is not guaranteed to reproduce the paper's reported
results. For accurate reproduction, download `5xFAD_WT_Integrated_Annotated.h5ad`
from [Zenodo DOI -- add once deposited] and place it in the working
directory before running the notebook -- Block 5 will detect it and skip
automatically.

Blocks 1 and 5 each pause partway through for a manual step: upload the
generated CSV to MapMyCells (https://knowledge.brain-map.org/mapmycells/process/),
place the downloaded results back in this directory, then rerun the block.

See `requirements.txt` for dependencies.
