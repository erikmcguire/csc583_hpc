## CSC 583: Augmenting GPT-2 with Hierarchical Predictive Processing for Story Ending Prediction

- [Notebook](https://colab.research.google.com/drive/1xu4SYsa4hNxO1Nnk7gjzAVKHa_moyzb9)
- [Paper](https://github.com/erikmcguire/predictive_coding/blob/main/csc583-mcguire_erik_pc_v3.pdf)

## Abstract

Hierarchical predictive processing (or predictive coding; PC) is a unifying neurocognitive paradigm and interdisciplinary research program which has been taken up in numerous domains, including computational modeling and subdomains of AI, such as Natural Language Processing (NLP). One type of NLP task in recent years is predicting the endings to brief stories, called the Story Cloze Test (SCT); this is primarily intended to examine the modeling of causal relations. We ask whether we can augment GPT-2, a large pretrained causal language model, with predictive coding in order to improve performance on SCT, formulated as a multiple-choice task. To do so, we add a contrastive PC loss to the conventional language modeling (LM) and multiple choice (MC) losses of the SCT task. This auxiliary loss is based on top-down prediction errors between layers' latent representations of sentences in stories. Results averaged across numerous seeds suggest that PC can be applied to GPT-2 as a substitute for or as a complement to language modeling to improve SCT task performance.
