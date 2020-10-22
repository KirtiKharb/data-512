## A2: Bias in Data

The goal of this assignment is to identify what, if any, sources of bias may exist in the Wikipedia Talk corpus datasets, and to develop testable hypotheses about how these biases might impact the behavior of machine learning models trained on the data, when those models are used for research purposes or to power data-driven applications.

### Data
All the raw data is stored under [data/raw](./data/raw) and the cleaned data is stored under [data/clean](./data/clean). The raw data contains Toxicity and Personal Attacks datasets as downloaded from [Figshare](https://figshare.com/projects/Wikipedia_Talk/16731) in their respective sub-folders [Toxicity](./data/raw/Toxicity) and [Personal_Attacks](./data/raw/Personal_Attacks). All generated figures from the code are under [Figures](./Figures).

#### Source
The data is collected from [Figshare](https://figshare.com/projects/Wikipedia_Talk/16731). 
- [Toxicity datasets](https://figshare.com/articles/dataset/Wikipedia_Talk_Labels_Toxicity/4563973)

- [Personal Attacks datasets](https://figshare.com/articles/dataset/Wikipedia_Talk_Labels_Personal_Attacks/4054689)

#### Useful Links
Dataset description and schema can be found [here](https://meta.wikimedia.org/wiki/Research:Detox/Data_Release).

Overview of the research project can be found [here](https://meta.wikimedia.org/wiki/Research:Detox).

Overview of Google’s Conversation AI project is located [here](https://conversationai.github.io/).

Documentation of Perspective API can be found [here](https://github.com/conversationai/perspectiveapi/blob/master/2-api/methods.md).

### Terms of Use

#### Data Citations
The source data is taken from [Figshare](https://figshare.com/projects/Wikipedia_Talk/16731). These datasets are released under a [CC0 public domain dedication](https://wiki.creativecommons.org/wiki/CC0).
- The Personal attack dataset is cited as:
Wulczyn, Ellery; Thain, Nithum; Dixon, Lucas (2017): Wikipedia Talk Labels: Personal Attacks. figshare. Dataset. https://doi.org/10.6084/m9.figshare.4054689.v6.
- The Toxicity dataset is cited as:
Thain, Nithum; Dixon, Lucas; Wulczyn, Ellery (2017): Wikipedia Talk Labels: Toxicity. figshare. Dataset. https://doi.org/10.6084/m9.figshare.4563973.v2.

#### Code License
The code is available under [MIT License](./LICENSE).
