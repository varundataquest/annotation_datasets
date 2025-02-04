| Year | Reference | Task | Dataset: Has indiv.<sup>[1](#datasymbols)</sup> | Attributes | # annots/<br/>instance | # rows. |  Score | Metric |
|:----- |:----- |:----- |:----- |:----- |:----- |:----- |:----- |:----- |
| 2022 | [ArMIS - The Arabic Misogyny and Sexism Corpus with Annotator Subjective Disagreements](http://www.lrec-conf.org/proceedings/lrec2022/pdf/2022.lrec-1.244.pdf) (Dina Almanea and Massimo Poesio) | Hate speech identification | [ArMIS](https://le-wi-di.github.io/) | :family_man_woman_girl_boy: | 3 | 964 | 0.525 | Fleiss' Kappa |
| 2021 | [Whose Opinions Matter? Perspective-aware Models to Identify Opinions of Hate Speech Victims in Abusive Language Detection](https://arxiv.org/abs/2106.15896) (Sohail Akhtar, Valerio Basile, Viviana Patti) | Hate speech identification | [HS-Brexit](https://le-wi-di.github.io/) | :family_man_woman_girl_boy: | 6 | 1120 | 0.35 | Fleiss' Kappa<sup>[2](#complicatedirr)</sup> |
| 2021 | [ConvAbuse: Data, Analysis, and Benchmarks for Nuanced Abuse Detection in Conversational AI](https://aclanthology.org/2021.emnlp-main.587/) (Amanda Cercas Curry, Gavin Abercrombie, Verena Rieser) | Hate speech identification | [ConvAbuse](https://le-wi-di.github.io/) | :family_man_woman_girl_boy: | 3-8 | 4185 | 0.69 | Alpha |
| 2021 | [Agreeing to Disagree: Annotating Offensive Language Datasets with Annotators’ Disagreement](https://aclanthology.org/2021.emnlp-main.822/) (Elisa Leonardelli, Stefano Menini, Alessio Palmero Aprosio, Marco Guerini, Sara Tonelli) | Hate speech identification | [MD-Agreement](https://le-wi-di.github.io/) | :family_man_woman_girl_boy: | 5 | 10K | 71.172 | Percent agreement<sup>[4](#selfcalculated)</sup> |
| 2021 | [Designing Toxic Content Classification for a Diversity of Perspectives](https://arxiv.org/abs/2106.04511) (Deepak Kumar, Patrick Gage Kelley, Sunny Consolvo, Joshua Mason, Elie Bursztein, Zakir Durumeric, Kurt Thomas, Michael Bailey) (jury learning) |  Hate speech identification | [Dataset](https://data.esrg.stanford.edu/study/toxicity-perspectives): $\square$ | :family_man_woman_girl_boy: | 5 | 107,620 | 65.2-90% | Percent agreement<sup>[2](#complicatedirr)</sup> |
| 2021 | [Did they answer? Subjective acts and intents in conversational discourse](https://aclanthology.org/2021.naacl-main.129/) (Elisa Ferracane, Greg Durrett, Junyi Jessy Li, Katrin Erk) | Sentiment Analysis+Intent Classification | [Dataset](https://github.com/elisaF/subjective_discourse/blob/master/data/gold/) | :family_man_woman_girl_boy: | 3-7 | 1K | Overall (0.494), conversation act (0.652), intent (0.376) | Alpha |
| 2020 | [On Faithfulness and Factuality in Abstractive Summarization](https://aclanthology.org/2020.acl-main.173) (Joshua Maynez, Shashi Narayan, Bernd Bohnet, Ryan McDonald) | Hallucination classification | [Dataset](https://github.com/google-research-datasets/xsum_hallucination_annotations) | :family_man_woman_girl_boy: | 3 |  | 0.61-0.80 | Fleiss' Kappa<sup>[2](#complicatedirr)</sup> |
| 2020 | [On Faithfulness and Factuality in Abstractive Summarization](https://aclanthology.org/2020.acl-main.173) (Joshua Maynez, Shashi Narayan, Bernd Bohnet, Ryan McDonald) | Factuality classification | [Dataset](https://github.com/google-research-datasets/xsum_hallucination_annotations) | :family_man_woman_girl_boy: | 3 |  | 0.81-1.00 | Fleiss' Kappa<sup>[2](#complicatedirr)</sup> |
| 2019 | [Understanding Discourse on Work and Job-Related Well-Being in Public Social Media](https://www.aclweb.org/anthology/P16-1099) (Liu, Tong and Homan, Christopher and Ovesdotter Alm, Cecilia and Lytle, Megan and Marie White, Ann and Kautz, Henry) |  | [Dataset](https://github.com/Homan-Lab/pldl_data/tree/master) | :family_man_woman_girl_boy: |5  | 7M |  | Percent agreement |
| 2019 | [Learning to Predict Population-Level Label Distributions](https://ojs.aaai.org/index.php/HCOMP/article/view/5286/5138) (Tong Liu, Akash Venkatachalam, Pratik Sanjay Bongale, Christopher M. Homan) |  | [Dataset](https://github.com/Homan-Lab/pldl_data/tree/master) | :family_man_woman_girl_boy: | 5 |2000  |0.9-0.59  |  |
| 2018 | [Introducing the gab hate corpus: Defining and applying hate-based rhetoric to social media posts at scale.](https://link.springer.com/article/10.1007/s10579-021-09569-x) (Brendan Kennedy, Mohammad Atari, Aida M. Davani, Leigh Yeh, Ali Omrani, Yehsong Kim, Kris Coombs, et al.) | Hate speech identification | [Dataset](https://osf.io/edua3/) | :family_man_woman_girl_boy: | 3 | 1000 | 0.75 | Kappa |
| 2018 | [Don't Give Me the Details, Just the Summary! Topic-Aware Convolutional Neural Networks for Extreme Summarization](https://arxiv.org/abs/1808.08745) (Shashi Narayan, Shay B. Cohen, Mirella Lapata) |  | [Dataset](https://github.com/EdinburghNLP/XSum/tree/master) | :family_man_woman_girl_boy: |  |  |  |  |
| 2018 | [Quantifying Qualitative Data for Understanding Controversial Issues]() () |  |  |  |  |  |  |  |
| 2018 | [Addressing Age-Related Bias in Sentiment Analysis](https://dl.acm.org/doi/10.1145/3173574.3173986) (Mark Diaz, Isaac Johnson, Amanda Lazar, Anne Marie Piper, and Darren Gergle) | Sentiment Analysis | [Dataset](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/F6EMTS) |  |  |  |  |  |
| 2018 | [A Broad-Coverage Challenge Corpus for Sentence Understanding through Inference](https://cims.nyu.edu/~sbowman/multinli/paper.pdf) (Williams, Adina and Nangia, Nikita and Bowman, Samuel) | Multi-genre NLI | [Dataset](https://cims.nyu.edu/~sbowman/multinli/) | :family_man_woman_girl_boy: |  |  |  |  |
| 2015 | [A large annotated corpus for learning natural language inference](https://nlp.stanford.edu/projects/snli/) (Samuel R. Bowman, Gabor Angeli, Christopher Potts, and Christopher D. Manning) | NLI | [Dataset](https://nlp.stanford.edu/projects/snli/) | :family_man_woman_girl_boy: |  |  |  |  |
| 2014 | [Lexical Acquisition for Opinion Inference: A Sense-Level Lexicon of Benefactive and Malefactive Events](https://aclanthology.org/W14-2618.pdf) (Yoonjung Choi, Lingjia Deng, and Janyce Wiebe) | WSD for sentiment analysis | [Dataset](http://mpqa.cs.pitt.edu/corpora/gfbf/) | $\triangle$ |  |  | 0.84 | Percent agreement|
|"|"|"|"|"|"|"|0.75 | Kappa|
| 2018 | [DART: A Large Dataset of Dialectal Arabic Tweets](https://aclanthology.org/L18-1579.pdf) (Israa Alsarsour, Esraa Mohamed, Reem Suwaileh, Tamer Elsayed) |  | |  |  |  |  |  |
| 2013 | [Evaluation datasets for Twitter sentiment analysis: a survey and a new dataset, the STS-Gold](https://oro.open.ac.uk/40660/) (Saif, Hassan; Fernández, Miriam; He, Yulan and Alani, Harith ) |  | |  |  |  |  |  |
| 2022 | [ArMIS - The Arabic Misogyny and Sexism Corpus with Annotator Subjective Disagreements](https://aclanthology.org/2022.lrec-1.244/) (Saif, Hassan; Fernández, Miriam; He, Yulan and Alani, Harith ) |  | |  |  |  |  |  |
| 2013 | [SemEval-2023 Task 11: Learning With Disagreements (LeWiDi)](https://arxiv.org/abs/2304.14803) (Elisa Leonardelli, Alexandra Uma, Gavin Abercrombie, Dina Almanea, Valerio Basile, Tommaso Fornaciari, Barbara Plank, Verena Rieser, Massimo Poesio ) |  | |:family_man_woman_girl_boy:  |  |  |  |  |
| 2023 | [xiacui at SemEval-2023 Task 11: Learning a Model in Mixed-Annotator Datasets Using Annotator Ranking Scores as Training Weights](https://aclanthology.org/2023.semeval-1.148/) (Elisa Leonardelli, Alexandra Uma, Gavin Abercrombie, Dina Almanea, Valerio Basile, Tommaso Fornaciari, Barbara Plank, Verena Rieser, Massimo Poesio ) |  | |:family_man_woman_girl_boy:  |  |  |  |  |
| 2023 | [A Dataset for Physical and Abstract Plausibility and Sources of Human Disagreement](https://aclanthology.org/2023.law-1.4.pdf) (Annerose Eichel, Sabine Schulte im Walde ) |  | |:family_man_woman_girl_boy:  |  |  |  |  |
| 2023 | [Assessing Inter-Annotator Agreement for Medical Image Segmentation](https://ieeexplore.ieee.org/abstract/document/10054393) (Feng Yang; Ghada Zamzmi; Sandeep Angara; Sivaramakrishnan Rajaraman; André Aquilina; Zhiyun Xue; Stefan Jaege et al ) |  | |:family_man_woman_girl_boy:  |  |  |  |  |
| 2023 | [Agreeing to Disagree: Annotating Offensive Language Datasets with Annotators' Disagreement](https://arxiv.org/abs/2109.13563) (Elisa Leonardelli, Stefano Menini, Alessio Palmero Aprosio, Marco Guerini, Sara Tonelli ) |  | |:family_man_woman_girl_boy:  |  |  |  |  |
| 2022 | [Toxicity detection sensitive to conversational context](https://firstmonday.org/ojs/index.php/fm/article/view/12285) (Alexandros Zenos, John Pavlopolous, Ian Androutsopoulos, Lucas Dixon, Jeffrey Sorensen, Leo Laugier) |  | |:family_man_woman_girl_boy:  |  |  |  |  |
| 2022 | [RuSentiTweet: a sentiment analysis dataset of general domain tweets in Russian](https://peerj.com/articles/cs-1039/) (Sergey Smetanin) |  | |:family_man_woman_girl_boy:  |  |  |  |  |
|  |  |  |  |  |  |  |  |  |




* The order of datasets within each year is random
  
<a name="datasymbols">1</a>:
If there is no :family_man_woman_girl_boy: emoji, this dataset contains aggregate level annotations. If there is, it contains annotator-level data as well.<br/>
$\times$ = no data released,<br/>
$\square$ = data can be obtained by reaching out to authors
<br/>

<a name="attributes">2</a>:<br/>
:pencil: = contains annotator instructions<br/>
:family_man_woman_girl_boy: = has annotator-level data<br/>
:computer: = data is crowdsourced as well (not just annotations). For example, having MTurkers write pairs of sentences as opposed to scraping the web<br/>
<br/>
<a name="complicatedirr">3</a>: Refer to the paper for more details. The interrater agreement is reported per subset and/or using several metrics.
<a name="selfcalculated">4</a>: Calculated using information given in paper/from dataset.

Papers talking about calculation methods (todo: organize this table)
- J. Richard Landis and Gary G. Koch. 1977. The measurement of observer agreement for categorical data.
Biometrics, 33(1):159–174.
- https://aclanthology.org/Q14-1025/#:~:text=The%20annotation%20model%20provides%20far,cost%20of%20the%20conventional%20approach.
- https://pubmed.ncbi.nlm.nih.gov/18482474/

Not label annotations but contains input from individual annotators (todo: organize into table)
- https://aclanthology.org/Q14-1006.pdf

- 
