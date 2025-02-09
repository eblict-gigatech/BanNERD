# BanNERD: A Benchmark Dataset and Context-Driven Approach for Bangla Named Entity Recognition


<div align="center">

![NER](https://img.shields.io/badge/NER-blue)
![Version](https://img.shields.io/badge/Version-1.0.0-blue)
![Data](https://img.shields.io/badge/Data-85K%2B%20Sentences-orange)

</div>

## 📋 Table of Contents

- [Overview](#-overview)
- [Key Features](#key-features)
- [Dataset Statistics](#-dataset-statistics)
- [Core Metrics](#core-metrics)
- [Named Entity Class Distribution](#named-entity-class-distribution)
- [Annotation Guidelines](#annotation-guidelines)
- [Comparison with Existing Datasets](#-comparison-with-existing-datasets)
- [Acknowledgments](#-acknowledgments)
- [Citation](#-citation)


## 📝 Overview

BanNERD is the most extensive human-annotated and validated **Bangla Named Entity Recognition** Dataset to date. With 85,175 meticulously annotated sentences spanning 29 diverse domains, BanNERD sets a new standard for Bangla NER research. The dataset achieved a high Inter-Annotator Agreement (IAA) score of 0.88, demonstrating its exceptional quality and reliability.

This dataset is based on the paper:<br>
```BanNERD: A Benchmark Dataset and Context-Driven Approach for Bangla Named Entity Recognition``` accepted at NACCL 2025 findings.

### Key Features

- 🔍 Over 85,000 expertly annotated sentences
- 🌐 Coverage across 29 diverse domains
- ✅ High IAA score of 0.88
- 👥 Expert linguist-developed annotation guidelines
- 🏷️ 10 comprehensive named entity classes
- 🔄 Rigorous validation through majority voting
- 📊 Consistent outperformance in cross-dataset evaluations

## 📊 Dataset Statistics

### Core Metrics

| Metric | Value |
|--------|-------|
| Total Sentences | 85,175 |
| Total Tokens | 991,441 |
| Unique Tokens | 73,526 |
| Named Entity Tokens | 232,093 |
| Sentence Length Range | 3-20 words |
| Average Sentence Length | 11.55 words |
| Tagging Scheme | BIO |

### Named Entity Class Distribution

| Class | Full Name | Tokens | % | IAA |
|-------|-----------|--------|---|-----|
| PER | Person | 78,657 | 33.89 | 0.96 |
| NUM | Number | 36,776 | 15.85 | 0.906 |
| ORG | Organization | 32,706 | 14.09 | 0.85 |
| D&T | Date & Time | 22,930 | 9.88 | 0.887 |
| LOC | Location | 13,707 | 5.91 | 0.835 |
| GPE | Geo-Political Entity | 13,338 | 5.75 | 0.811 |
| EVENT | Event | 13,203 | 5.69 | 0.824 |
| UNIT | Unit | 8,552 | 3.68 | 0.873 |
| MISC | Miscellaneous | 7,165 | 3.09 | 0.856 |
| T&T | Term & Title | 5,059 | 2.18 | 0.755 |

### Annotation Guidelines
Developed in collaboration with expert linguists, validated by the national linguistics and technical expert committee.

For detailed annotation guidelines, refer to the [Bangla NER Guideline](https://guideline-docs.s3.ap-south-1.amazonaws.com/Named+Entity+Regocnition+in+Bangla.pdf).


## 📈 Comparison with Existing Datasets

| Attribute               | BanNERD | Haque et al. (2023) | Karim et al. (2019) | Malmasi et al. (2022) | Fetahu et al. (2023a) | Mhaske et al. (2023) | Pan et al. (2017) |
|-------------------------|---------|---------------------|---------------------|-----------------------|-----------------------|-----------------------|--------------------|
| **Sentences**          | 85,175  | 22,144              | 71,284              | 149,219               | 30,074                | 967,145               | 12,000            |
| **Tokens**             | 991,441 | 297,418             | 983,663             | 896,116               | 393,509               | 15,419,213            | 51,618            |
| **Unique Tokens**      | 73,526  | 34,237              | 96,155              | 83,986                | 42,619                | 525,515               | 8,191             |
| **Sentence Length**    | [3-20]  | [1-233]             | [5-30]              | [1-35]                | [2-85]                | [1-100]               | [3-62]            |
| **Avg. Sentence Length** | 11.55   | 13.43               | 13.80               | 6.005                 | 13.08                 | 15.94                 | 4.30              |
| **Entities**           | 10      | 8                   | 4                   | 6                     | 34                    | 3                     | 3                 |
| **Tagging Scheme**     | BIO     | BIO                 | BIO                 | BIO                   | BIO                   | BIO                   | BIO               |
| **Number of Tags**     | 21      | 17                  | 9                   | 13                    | 67                    | 7                     | 7                 |


## 🌟 Acknowledgments
We would like to express our gratitude to the **Bangla Syntactic Treebank Corpus With Processing Pipeline and Distribution Platform** project, which is part of the **Enhancement of Bangla Language in ICT through Research & Development** ([EBLICT](http://eblict.gov.bd/)) initiative, supported by the [Bangladesh Computer Council](https://bcc.gov.bd/) under the [ICT Division](https://ictd.gov.bd/) of the Government of Bangladesh. We extend our sincere appreciation to the dedicated development consultant team at [Giga Tech Limited](https://gigatechltd.com/) and the [Dhaka University Linguistics and Communication Department](https://www.du.ac.bd/body/LIN) for their support. Furthermore, we would like to acknowledge the invaluable financial support provided by the People's Republic of Bangladesh, which enabled the successful execution of this research.

## 📚 Citation

If you use BanNERD in your research or applications, please cite our paper:

```bibtex
@inproceedings{
   title={BanNERD: A Benchmark Dataset and Context-Driven Approach for Bangla Named Entity Recognition},
   author={ Md. Motahar Mahtab, Faisal Ahamed Khan, Md. Ekramul Islam,
            Md. Shahad Mahmud Chowdhury, Labib Imam Chowdhury,Sadia Afrin, Hazrat Ali,
            Mohammad Mamun Or Rashid, Nabeel Mohammed, Mohammad Ruhul Amin },
   booktitle={Findings of the Association for Computational Linguistics: NAACL 2025},
   year={2025},
   publisher={Association for Computational Linguistics}
}
