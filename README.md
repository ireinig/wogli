# wogli
This repository contains the datasets published with the following paper:

[Can current NLI systems handle German word order? Investigating language model performance on a new German challenge set of minimal pairs](https://aclanthology.org/2023.iwcs-1.1) (Reinig & Markert, IWCS 2023)

## Citation

If you use this dataset, please cite our paper:
```
@inproceedings{reinig-markert-2023-current,
    title = "Can current {NLI} systems handle {G}erman word order? Investigating language model performance on a new {G}erman challenge set of minimal pairs",
    author = "Reinig, Ines  and
      Markert, Katja",
    editor = "Amblard, Maxime  and
      Breitholtz, Ellen",
    booktitle = "Proceedings of the 15th International Conference on Computational Semantics",
    month = jun,
    year = "2023",
    address = "Nancy, France",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.iwcs-1.1",
    pages = "1--15",
    abstract = "Compared to English, German word order is freer and therefore poses additional challenges for natural language inference (NLI). We create WOGLI (Word Order in German Language Inference), the first adversarial NLI dataset for German word order that has the following properties: (i) each premise has an entailed and a non-entailed hypothesis; (ii) premise and hypotheses differ only in word order and necessary morphological changes to mark case and number. In particular, each premise and its two hypotheses contain exactly the same lemmata. Our adversarial examples require the model to use morphological markers in order to recognise or reject entailment. We show that current German autoencoding models fine-tuned on translated NLI data can struggle on this challenge set, reflecting the fact that translated NLI datasets will not mirror all necessary language phenomena in the target language. We also examine performance after data augmentation as well as on related word order phenomena derived from WOGLI. Our datasets are publically available at https://github.com/ireinig/wogli.",
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
