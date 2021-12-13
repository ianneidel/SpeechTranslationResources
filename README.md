# Speech Translation Resources
This page contains a curated list of papers and resources for Speech Translation, with a focus on end-to-end systems. This list should be considered as a starting point for anyone with an interest in Speech Translation, not a definitive guide.

## Papers
###Overview
**Speech Translation and the End-to-End Promise: Taking Stock of Where We Are**; ACL 2020; [Paper](https://arxiv.org/pdf/2004.06358.pdf)

### Speech-to-text Translation
**Multilingual Speech Translation with Efficient Finetuning of Pretrained Models**; ACL 2020; [Paper](https://arxiv.org/abs/2010.12829)

**AdaST: Dynamically Adapting Encoder States in the Decoder for End-to-End Speech-to-Text Translation**; ACL 2021; [Paper](https://aclanthology.org/2021.findings-acl.224.pdf)

**Cascade versus Direct Speech Translation: Do the Differences Still Make a Difference?**; ACL 2021; [Paper](https://arxiv.org/pdf/2106.01045.pdf)

**Gender in Danger? Evaluating Speech Translation Technology on the MuST-SHE Corpus**; ACL 2020; [Paper](https://aclanthology.org/2020.acl-main.619/)

**Highland Puebla Nahuatl–Spanish Speech Translation Corpus for Endangered Language Documentation**; ACL 2021; [Paper](https://aclanthology.org/2021.americasnlp-1.7.pdf)

**Self-Training for End-to-End Speech Translation**; Interspeech 2020; [Paper](https://arxiv.org/abs/2006.02490)

**Towards Unsupervised Speech-to-text Translation**; ICASSP 2019; [Paper](https://arxiv.org/pdf/1811.01307.pdf)

**Fluent Translations from Disfluent Speech in End-to-End Speech Translation**; NAACL 2019; [Paper](https://arxiv.org/pdf/1906.00556.pdf)

**Bridging the Gap between Pre-Training and Fine-Tuning for End-to-End Speech Translation**; AAAI 2020; [Paper](https://arxiv.org/pdf/1909.07575.pdf)

**Fused Acoustic and Text Encoding for Multimodal Bilingual Pretraining and Speech Translation**; ICML 2021; [Paper](https://arxiv.org/abs/2102.05766)



### Speech-to-speech Translation
**Direct speech-to-speech translation with a sequence-to-sequence model** (Translatotron 1); Interspeech 2019; [Paper](https://arxiv.org/abs/1904.06037) [Google AI blog post](https://ai.googleblog.com/2019/05/introducing-translatotron-end-to-end.html); [Google Research Audio Samples](https://google-research.github.io/lingvo-lab/translatotron/)

**Translatotron 2: Robust direct speech-to-speech translation**; 2021 on ArXiV; [Paper](https://arxiv.org/abs/2107.08661); [Google Research Audio Samples](https://google-research.github.io/lingvo-lab/translatotron2/)

**Assessing Evaluation Metrics for Speech-to-Speech Translation**; 2021 ASRU; [Paper](https://arxiv.org/abs/2110.13877)

**Transformer-based Direct Speech-to-speech Translation with Transcoder**; 2021 SLT; [Paper](https://ahcweb01.naist.jp/papers/conference/2021/202101_SLT_takatomo-k/202101_SLT_takatomo-k.paper.pdf)

**Direct speech-to-speech translation with discrete units**; 2021 on ArXiV; [Paper](https://arxiv.org/abs/2107.05604)

**Direct simultaneous speech to speech translation**; 2021 on ArXiV; [Paper](https://arxiv.org/abs/2106.06636)

**Speech-to-speech Translation between Untranscribed Unknown Languages**; 2019 ASRU; [Paper](https://arxiv.org/pdf/1910.00795.pdf)




## Datasets
###CoVoST:
All data at [Facebook Research Github Repo](https://github.com/facebookresearch/covost)

**CoVoST 2**: 21 X->En, 15 En->X speech-to-text language pairs; 2880 hours; [Paper](https://arxiv.org/abs/2007.10310); [MetaAI Announcement](https://ai.facebook.com/blog/covost-v2-expanding-the-largest-most-diverse-multilingual-speech-to-text-translation-data-set/); [HuggingFace Dataset](https://huggingface.co/datasets/covost2)

**CoVoST 1**: 11 X->En speech-to-text language pairs; 700 hours; [Paper](https://arxiv.org/abs/2002.01320)

### Other speech-to-text datasets:
**MTedX**: 11 languages into some of En, Es, Fr, It, Pt; 765 hours; [Paper](https://arxiv.org/pdf/2102.01757.pdf); [Dataset](https://www.openslr.org/100)

**Europarl-ST**: A Multilingual Corpus For Speech Translation Of Parliamentary Debates; with v1.1 all pairs of 9 European Languages = 72 directions; 1642 hours; [Paper](https://arxiv.org/abs/1911.03167); [Dataset](https://www.mllp.upv.es/europarl-st/)

**MaSS** (Multilingual corpus of Sentence-aligned Spoken utterances): 8 languages => 56 directions; 172 hours; [Paper](https://arxiv.org/pdf/1907.12895.pdf); [Datset](https://github.com/getalp/mass-dataset)

**BSTC** (Baidu Speech Translation Corpus): 50 hours Zh->En; [Paper](https://arxiv.org/abs/2104.03575); [Baidu page](https://ai.baidu.com/broad/introduction?dataset=bstc)

**Fisher** and Callhome Spanish-English Speech Translation: 160 hours Es->En; [Paper](https://www.cs.jhu.edu/~post/papers/post2013improved.pdf); [Dataset](https://catalog.ldc.upenn.edu/LDC2014T23)

### Speech-to-speech datasets:
**MaSS** (Multilingual corpus of Sentence-aligned Spoken utterances): 8,130 parallel spoken utterances across 8 languages (56 language pairs); also provides text; [Paper](https://arxiv.org/pdf/1907.12895.pdf); [Datset](https://github.com/getalp/mass-dataset)

Most speech-to-speech datasets, however, are largely produced through speech synthesis of speech-to-text translation datasets such as the Fisher, Conversational, or CoVoST 2 dataset (as is done for Translatotron).


## Other Resources
See [End-to-End Speech Translation Progress](https://github.com/kahne/SpeechTransProgress) for more papers and datasets by Changhan Wang.

See [Awesome speech translation](https://github.com/dqqcasia/awesome-speech-translation#dataset) for a very comprehensive set of papers (including Pipeline ST, streaming ST, and other ST problems) compiled by the Chinese Academy of Sciences & ByteDance AI Lab.

See [ST Tutorial](https://st-tutorial.github.io/) for a great introduction to Speech Translation with slides and resources, which were presented as at EACL 2021.


##### If there are any suggestions, errors caught, or anything else, feel free to submit a pull request!


