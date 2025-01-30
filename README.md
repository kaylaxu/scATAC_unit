# scATAC_unit
Unit test files and script for scATAC mongodb insert. 

Documents will be inserted in to a database named 'scATAC' and collection named 'UNIT'.

Test file unit_1000.csv contains counts for 1,000 ATAC loci across 4,863 PFPP cells (9.4 MB).

To run:
1. Create a python environment with pymongo python package.
2. Run ``` python unit_insert.py unit_1000.csv ```
