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
```bibtex
@inproceedings{Mitra_2022, doi = {10.1109/ismode56940.2022.10180928}, url = {https://doi.org/10.1109%2Fismode56940.2022.10180928}, year = 2022, month = {dec}, publisher = {{IEEE}}, author = {Rohan Mitra and Dara Varam and Eyad Ali and Hana Sulieman and Firuz Kamalov}, title = {Development of Synthetic Data Benchmarks for Evaluating Feature Selection Algorithms}, booktitle = {2022 2nd International Seminar on Machine Learning, Optimization, and Data Science ({ISMODE})}}
```
