# Subjectivity Classification for Brasilian Portuguese using BERTimbau
This notebook contains the Artificial Neural Network implemented for experimentation of BERTimbau on the stored datasets. To reproduce the experiment, enter the CSPortuguês.ipynb file and load the Google Colab notebook. Run all cells, preferably using GPU environment. It is possible to choose corpus (preprocessed or not ) by changing the 'end' dictionary key to the suitable choice.

The utilized annotation for the three original datasets in portuguese was the ones made by Belisario et al (for book and electronic reviews) and Moraes et al (for Computer-BR, as made available in [OPINANDO project](https://sites.google.com/icmc.usp.br/opinando/)).

For the three first datasets, see the OPINANDO project (https://sites.google.com/icmc.usp.br/opinando/)
For Czechsubj and SetFit, the annotation was translated along with the corpora, following, then, the strategy adopted by their authors. For czechsubj, see
@article{pib2022czechsubj,
    title={Czech Dataset for Cross-lingual Subjectivity Classification},
    author={Pavel Přibáň and Josef Steinberger},
    year={2022},
    eprint={2204.13915},
    archivePrefix={arXiv},
    primaryClass={cs.CL}
}.

For Setfit, see https://huggingface.co/datasets/SetFit/subj/tree/main.




