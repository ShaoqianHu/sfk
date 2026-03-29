# sfk
Computing theoretical seismograms from a point source in a spheriucal multilayered medium

Reference:
Hu, Shaoqian, and Lupei Zhu. "Computing theoretical seismograms from a point source in a spherical multilayered medium." Seismological Research Letters 95.1 (2024): 448-457.

In example.tar, there is a sample script to run the code (run bash test.sh). 
Note fk.pl in example.tar is different from fk.pl in FK package (version 3.4). 
Also note that the earth flattening transformation should be applied to the input model before running the code (e.g., iasp91 in example.tar).

# update 2026/03
sfk20260328.tar is the updated version which (1) handle explosion, single force,and double couple sources (2) combine sKernelRT.f90 and tKernelRT.f90 to kernelRT, resulting in faster computation
