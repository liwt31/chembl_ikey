# chembl_ikey

This is pure python implementation of InChiKey generation algorithm based on the original C code.

This is a improved version of the chembl_ikey package developed at Chembl group, EMBL-EBI, Cambridge, UK.

The original version is only compatible with python2, and this version could run with python2 or python3. Some bugs are also fixed.

## How to use

1. Download and unzip (or clone) the package
2. Install the package by using `pip install setup.py`
3. Import the interface by using `from chembl_ikey import inchi_to_inchikey`
4. Convert inchi to inchikey by calling `inchi_to_inchikey(inchi)`

A sample of how to use the code could be found in chembl_ikey/test.py 
