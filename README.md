# EDArtifacts_Detection

EDArtifact_Detection is a reporitory that can be used for iddentifying artifacts in elecrodermal activity signals collected in the wild over long periods of time. 

If you use the scripts in this repo please cite paper [1]:

[1] S. Gashi, E. Di Lascio, B. Stancu, V. Das Swain, V. Mishra, M. Gjoreski, S. Santini: "Detection of Artifacts in Ambulatory Electrodermal Activity Data". In: Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies (PACM IMWUT), Vol. 4, Issue 2, June 2020. 31 pages.

The paper is available at https://dl.acm.org/doi/10.1145/3397316.

Please do not hesitate to contact us at silvia.santini@usi.ch if you have any questions in general or experience issues with the tool.

The repository conntains the following items:
- *EDArtifacts_Detection.ipynb*: is a jupyter notebook script that contains 
- *SA_Detection.sav*: which contains the trained model for identifying shape artifacts in EDA. 
- *Data*: contains a sample EDA signal which is used to show how the script works.
- *cvxEDA*: to decompos the EDA signal into the phasic and tonic component.

