# Minecraft
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8164641.svg)](https://doi.org/10.5281/zenodo.8164641)
## Downloading the dataset:
The Minecraft dataset can be downloaded from [Zenodo](https://doi.org/10.5281/zenodo.8164641).

## Instructions to generate dataset:

First, clone the repository using
```
git clone --recursive https://github.com/anonymousgn1/Minecraft.git
```

Now download the required libraries using:
```
pip3 install -r requirements.txt
```

Once downloaded all the dependencies, the dataset can be generated by running the following command:

```
python3 main.py projects.csv
```

```projects.csv``` is composed of all open source repositories of multiple languages like C, C++, Java, and Python.

## Extending the dataset
Dataset can be further extended by including different languages. To add languges refer to [tree-sitter](https://github.com/tree-sitter/py-tree-sitter) library and make the necessary changes in [AST.py](https://github.com/anonymousgn1/Minecraft/blob/main/AST.py).

# Citation
If you use this dataset + tool in your research, please cite our ASE 2023 paper in the format specified below:
```@INPROCEEDINGS{10298401,
  author={Avula, Sai Krishna and Vobbilisetti, Venkatesh and Mondal, Shouvick},
  booktitle={2023 38th IEEE/ACM International Conference on Automated Software Engineering (ASE)}, 
  title={Minecraft: Automated Mining of Software Bug Fixes with Precise Code Context}, 
  year={2023},
  volume={},
  number={},
  pages={1969-1979},
  doi={10.1109/ASE56229.2023.00116}}
```
