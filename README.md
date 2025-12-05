# SEAHateCheck Dataset

Warning: This repository contains hateful language. 

This repository contains the full set of template based test cases, Gold Label test cases and Silver Label test cases that are curated for Indonesia, the Philippines, Thailand and Vietnam, in Indonesian, Tagalog, Thai and Vietnamese respectively. 

Silver Label test cases for Singapore and Malaysia is also available here; for Gold Label test cases, please refer to [SGHateCheck's github repository](https://github.com/Social-AI-Studio/SGHateCheck).

## Contents
1. [/dataset](#dataset) 
1. [/benchmarking](#benchmarking)
1. [Citation](#citation)

## Dataset

Headers prefixed with ```p_``` are related to placeholders, ```c_``` to test cases and ```t_``` to templates. 

### ```dataset/gold_label_all```
Gold Label test cases are based on templates from [HateCheck (Röttger et al., ACL-IJCNLP 2021)](https://github.com/paul-rottger/hatecheck-data) translated by machine and native speakers into the various Southeast Asian Languages. Test cases made by combining the translated templates with placeholders selected by cultural experts to better reflect the socio-legal perspective of the countries.

### ```dataset/gold_label_annotated```

A sample of the Gold Label test cases were further verified by 3 native speaking annotators. ```count``` prefix and suffix shows the cumulative annotations for the particular test case. 

### ```dataset/silver_label_all```

To further localise the test cases, the Silver Label set was created by generating test cases using LLMs, with multi-shot prompts created using examples from the gold test cases. 

### ```dataset/silver_label_all```
Just as before, a sample of the Silver Label test cases were further verified by 3 native speaking annotators. ```count``` prefix and suffix shows the cumulative annotations for the particular test case. 

## Benchmarking

For ease of analysis, figures and tables used in the paper to showcase the benchmarking results can be found in ```benchmarking/```

## Citation

TBC