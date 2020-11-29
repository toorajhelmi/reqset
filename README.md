# Code and Data for paper: [Parsing Natural-Language based Software Requirements into Code Segments](https://toorajhelmi.github.io/home/publication/parsing)

## Data

All the data files are placed under data folder:

| File                    | Mode       | Use                                       |
|-------------------------|------------|-------------------------------------------|
| Reqset-train.csv        | Plain Text | Parse to generate training dataset        |
| Reqset-test.csv         | Plain Text | Parse to generate testing dataset         |
| Reqset-train-tagged.csv | Parsed     | Dataset to use for training               |
| Reqset-test-tagged.csv  | Parsed     | Dataset to use for testing                |
| Reqset-comb-tagged.csv  | Parsed     | Dataset to split for training and testing |


## Code
Code is placed inder code folder. There are two notebooks:

- ReqCRF.ipynb: Contains code for BILSTM-CRF model
- ReqBERT.ipynb: Contains code for fine-tuned BERT model


For any questions or comments reach out to: thelmi@usc.edu