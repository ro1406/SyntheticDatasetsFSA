# SyntheticDatasetsFSA
Synthetic Datasets for benchmarking feature selection algorithms as from the paper Development of Synthetic Data Benchmarks for Evaluating Feature Selection Algorithms from ISMODE2 2022.

<h2>Dataset summary:</h2>

|Dataset|Relevant Features|Redundant Features|Irrelevant Features|Instances|Target Variable Equation|Inspiration|
|---|---|---|---|---|---|---|
|Trignometric|2|5|50|200|F₂> 2sin(F₁) - 2|Multi-Layer Perceptron|
|Hypersphere|3|20|100|400|900>F₁²+F₂²+F₃²|SVM|
|10-class Multi-cut|6|20|100|500|F₁-2F₂+ 5F₃− 4F₄+ 8F₅− 7F₆|Decision Tree|
|Yin-Yang|2|10|75|600|Generated from image|Art|


<h2>Cite this work:</h2>

```
@Article{synthetic_data_1,
AUTHOR = {Mitra, Rohan and Ali, Eyad and Varam, Dara and Sulieman, Hana and Kamalov, Firuz},
TITLE = {Variable Selection in Data Analysis: A Synthetic Data Toolkit},
JOURNAL = {Mathematics},
VOLUME = {12},
YEAR = {2024},
NUMBER = {4},
ARTICLE-NUMBER = {570},
URL = {https://www.mdpi.com/2227-7390/12/4/570},
ISSN = {2227-7390},
DOI = {10.3390/math12040570}
}

@INPROCEEDINGS{synthetic_data_2,
  author={Mitra, Rohan and Varam, Dara and Ali, Eyad and Sulieman, Hana and Kamalov, Firuz},
  booktitle={2022 2nd International Seminar on Machine Learning, Optimization, and Data Science (ISMODE)}, 
  title={Development of Synthetic Data Benchmarks for Evaluating Feature Selection Algorithms}, 
  year={2022},
  volume={},
  number={},
  pages={47-52},
  keywords={Seminars;Measurement;Machine learning algorithms;Codes;Benchmark testing;Feature extraction;Standards;synthetic data generation;data science;data;feature selection;bench-marking},
  doi={10.1109/ISMODE56940.2022.10180928}}
```

