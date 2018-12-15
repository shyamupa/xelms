Code for the EMNLP paper, "The Importance of Joint Multilingual Supervision for Cross-Lingual Entity Linking".

### Preprocessing Wikipedia for Candidate Generation
First, preprocess the Wikipedia dump for the languages you care about using the [wikidump_preprocessing](https://github.com/shyamupa/wikidump_preprocessing) code here.  

### Setting up Candidate Generation
The code for performing candidate generation is available at [wiki_candgen](https://github.com/shyamupa/wiki_candgen). It uses the resources generated using the [wikidump_preprocessing](https://github.com/shyamupa/wikidump_preprocessing) repo. 

TODO: Add code for running the model. 

```
@inproceedings{UGR18,
  author = {Upadhyay, Shyam and Gupta, Nitish and Roth, Dan},
  title = {Joint Multilingual Supervision for Cross-lingual Entity Linking},
  booktitle = {EMNLP},
  year = {2018}
}```
