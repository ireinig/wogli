# wogli
This repository contains the datasets published with the following paper:

Reinig, Ines and Markert, Katja (2023). Can current NLI systems handle German word order? Investigating language model performance on a new German challenge set of minimal pairs. Proceedings of the 15th International Conference on Computational Semantics (IWCS). Nancy, France: Association for Computational Linguistics. In press.

## Citation

If you use this dataset, please cite our paper:
```
@misc{reinig2023current,
      title={Can current NLI systems handle German word order? Investigating language model performance on a new German challenge set of minimal pairs}, 
      author={Ines Reinig and Katja Markert},
      year={2023},
      eprint={2306.04523},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```

## Datasets

The compressed folder `dataset.zip` contains all WOGLI datasets in tabular format:
- `dataset/wogli.csv`: the WOGLI dataset
- `dataset/generalization/` contains the four generalization sets presented in the paper: WOGLI-p-subject, WOGLI-dative, WOGLI-ditransitive, WOGLI-OS-hard (NE).

The dataset is encrypted to protect it from crawling. The encryption key is: dofwym-coqjo6-ryhkYm

Labels are defined as follows: `1` stands for non-entailment and `2` for entailment.

## Supplementary material

Verb and nouns lists can be found in the folder `supplementary-material/`.

## License
<a rel="license" href="http://creativecommons.org/licenses/by-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nd/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nd/4.0/">Creative Commons Attribution-NoDerivatives 4.0 International License</a>.
