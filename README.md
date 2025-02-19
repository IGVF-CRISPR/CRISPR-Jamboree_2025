# CRISPR-Jamboree_2025
4th IGVF CRISPR-Jamboree

The users will log in in to the Jupyter hub infrastructure at (private address for now) and log in using the password and user will be provided during the jamboree.

Inside each machine the user will find an environment reserved for their specific tasks :

### Benchmark Tasks:


Inside Jupyterhub, the user will find the following notebook: 
		-Setup.ipynb
		-RunTask.ipynb


1) Run first Setup.ipynb to download the MuDatas and install Perturbo


2) RunTask.ipynb will allow the execution of the pipeline from a specific checkpoint (guide inference, hashing, or inference step);
   The user can run one of the two datasets (WTC11 and H9 and the final results with the AUROC and AUPRC will be generated, informing how well the pipeline can predict the minimal control set. 

The execution should not take longer than 16 minutes (small pairs to test H9 or WTC11) and should be used to observe the performance of a specific tool.

The default nextflow will run the H9 dataset. To run the WTC11 dataset just uncomment the line. 





