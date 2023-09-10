# GSAC: A Gujarati Sentiment Analysis Corpus from Twitter

This repository contains the GSAC dataset described [in this paper](https://aclanthology.org/2023.wassa-1.12/). It contains a total of 6,575 tweets manually annotated by native speakers in three sentiment classes - positive, negative, and neutral. The dataset is split into train, dev, and test splits in a 70-10-20 ratio. For further details, refer to the linked paper.

As per Twitter's privacy policy, only the ID of the tweet and the sentiment labels are available in the dataset. The dataset must first be hydrated using Twitter API to retrieve the full tweet and other information about each individual tweet using the ID.

If you are using this dataset, please cite the following paper -
  
    @inproceedings{gokani-mamidi-2023-gsac,
    title = "{GSAC}: A {G}ujarati Sentiment Analysis Corpus from {T}witter",
    author = "Gokani, Monil  and
      Mamidi, Radhika",
    booktitle = "Proceedings of the 13th Workshop on Computational Approaches to Subjectivity, Sentiment, {\&} Social Media Analysis",
    month = jul,
    year = "2023",
    address = "Toronto, Canada",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.wassa-1.12",
    doi = "10.18653/v1/2023.wassa-1.12",
    pages = "129--137",
    }
  
   
