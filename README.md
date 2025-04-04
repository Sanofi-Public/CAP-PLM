# CAP-PLM

This repository contains some tutorial notebooks on how to train the models and make the figures for the associated manuscript.

For questions on the codebase, please raise an issue on this repository. Any questions for the manuscript itself should be emailed to gmu@sanofi.com.

## Local Installation

All of the notebooks are run using python 3.7. After ensuring python is in your system, other python dependencies are necessary for this project. To install the packages to run the notebooks, please use the following script after cloning this repository into your working directory:
```
pip install -r requirements.txt
```
All notebooks were run utilizing a m6i.32xlarge AWS instance, but one can use a smaller number of CPUs at the cost of reducing training speed if need be. A GPU is not required for any of the notebooks in this repository.

One can train their own model using the provided input data in Model_Training.ipynb, and the CAP-PLM Figures Manuscript.ipynb notebook was used to generate the figures in the linked manuscript. 

## References
[One-Hot augmentation](https://www.nature.com/articles/s41587-021-01146-5)

[Wu et al. (2000) validation data](https://journals.asm.org/doi/10.1128/jvi.74.18.8635-8647.2000?url_ver=Z39.88-2003&rfr_id=ori:rid:crossref.org&rfr_dat=cr_pub%20%200pubmed)

[Bryant et al. (2021) validation data](https://www.nature.com/articles/s41587-020-00793-4)

