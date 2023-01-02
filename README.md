# CoFFee: A Co-occurrence and Frequency-Based Approach to Schema Mining

Please note that this is research code. It is not very clean, and not well documented.

### folders

* datas -> type = dict : set of entity schema (extracted from DBpedia)
* output -> type = list (pickle) : list of attributes selected by coffee (output from CoFFee_pipeline.ipynb)
* schema_reference -> type = csv : attribute mapping between infobox and entity schema (used in experiment 2)

### source code:

* CoFFee_pipeline.ipynb -> main pipeline
* experiments.ipynb -> experiments code


## Citation
Neto, E. C., Moreira, J., Barbosa, L., & Salgado, A. C. (2022, September). CoFFee: A Co-occurrence and Frequency-Based Approach to Schema Mining. In Anais do XXXVII Simpósio Brasileiro de Bancos de Dados (pp. 52-64). SBC.

@inproceedings{neto2022coffee,
  title={CoFFee: A Co-occurrence and Frequency-Based Approach to Schema Mining},
  author={Neto, Everaldo Costa and Moreira, Johny and Barbosa, Luciano and Salgado, Ana Carolina},
  booktitle={Anais do XXXVII Simp{\'o}sio Brasileiro de Bancos de Dados},
  pages={52--64},
  year={2022},
  organization={SBC}
}
