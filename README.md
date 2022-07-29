# HyResII
HyRes II Coarse-Grained Protein Model

HyRes II is a hybrid resolution coarse-grained protein model that contains atomistic protein backbone and intermediate resolution side chains. The model has been parameterized to provide semi-quantitative description of local helical propensities as well transient long-range interactions of intrinsically disordered proteins. The model can not be used for simulation of folded proteins, even though it will proper distinguish the overall compaction of folded vs. disordered proteins.

HyRes II requires a slightly modified CHARMM to support the Debye-Huckel electrostatic interactions. The patch can be provided upon request by contacting Jianhan Chen (jianahnc@umass.edu). This depository contains a tutorial with HyRes II topology and parameter files and a sample charmm script for running a standard MD simulation using HyRes II.  

Kye references for HyRes and HyRes II models:

Liu and Chen (2017). "HyRes: a coarse-grained model for multi-scale enhanced sampling of disordered protein conformations." Physical Chemistry Chemical Physics 19(48): 32421-32432. (http://pubs.rsc.org/en/content/articlehtml/2017/CP/C7CP06736D)

Zhang, Liu and Chen, "Towards Accurate Coarse-Grained Simulations of Disordered Proteins and Their Dynamic Interactions" (under review)

