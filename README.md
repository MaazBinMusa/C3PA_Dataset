# Documentation
This is the dataset for the paper "C3PA: An Open Dataset of Expert-Annotated and Regulation-Aware Privacy Policies to Enable Scalable Regulatory Compliance Audits" that is published in EMNLP 2024 conference.

## Annotation
The annotations folder has two subfolders; "DB" and "WS". Each folder contains the annotations for the dataset. The annotations are in the form of individial CSV files with the following columns:

- RANumb: The person number who annotated the policy.
- Text: The text span that is annotated.
- Label: The label of the text span.

## Crawl
The crawl folder also has two subfolders; "DB" and "WS". Each folder contains the privacy policy crawler data for the dataset. The crawled data is in the form of CSV files with the following columns:

- Link: The URL of the privacy policy.
- IsHomepage: Whether the link is the homepage of the website.
- Textmatch_P: Set of regulation specific primary keywords that are matched in the policy.
- Textmatch_S: Set of regulation specific secondary keywords that are matched in the policy.
- Textmatch_PP: Set of generic primary keywords that are matched in the policy.
- Link_Match: Set of regulation specific and generic keywords that are matched in the URL.

## Htmls
The Htmls folder has two subfolders; "DB" and "WS". Each folder contains the HTML files of the privacy policies. The HTML files are named as numbers e.g., 1.html and they correspond to rownumber+1 in crawl data (2nd row) and annotation data 1.csv.

## Citation
If you use this dataset, please cite the following paper:

```
@inproceedings{c3pa,
  title={C3PA: An Open Dataset of Expert-Annotated and Regulation-Aware Privacy Policies to Enable Scalable Regulatory Compliance Audits},
  author={Maaz Bin Musa, Steven M. Winston, Garrison Allen, Jacob Schiller, Kevin Moore, Sean Quick, Johnathan Melvin,Padmini Srinivasan, Mihailis E. Diamantis, Rishab Nithyanand},
  booktitle={Empirical Methods in Natural Language Processing},
  year={2024}
}
```
