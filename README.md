<img src="https://gkiril.github.io/minie/images/minie_logo.png" align="right" width="150" />

# MinScIE: Citation-centered Open Information Extraction

An Open Information Extraction (OIE) system which provides structured knowledge enriched with semantic information about citations. This system is based upon the OIE system [MinIE](https://github.com/gkiril/minie). 

## Open Information Extraction (OIE)
Open Information Extraction (OIE) systems aim to extract unseen relations and their arguments from unstructured text in unsupervised manner. In its simplest form, given a natural language sentence, they extract information in the form of a triple, consisted of subject (S), relation (R) and object (O). 

Suppose we have the following input sentence:
```
AMD, which is based in U.S., is a technology company.
```

An OIE system aims to make the following extractions: 

```
("AMD"; "is based in"; "U.S.")
("AMD"; "is"; "technology company")
```

## Demo

For the demos, please refer to the classes `tests.minie.Demo.java` and `tests.minie.DetectCitationDemo.java`.

## Citing
If you use MinScIE in your work, please cite our paper:

```
@inproceedings{lauscher2019minscie,
  title={MinScIE: Citation-centered Open Information Extraction},
  author={Lauscher, Anne and Song, Yide and Gashteovski, Kiril},
  booktitle={Proceedings of ACM/IEEE Joint Conference on Digital Libraries},
  year={2019}
}
```
