# Analyzing and Simulating User Utterance Reformulation in Conversational Recommender Systems

This repository provides resources developed within the following article:

> Zhang, Wang, Balog. **Analyzing and Simulating User Utterance Reformulation in Conversational Recommender Systems.** In: Proceedings of the 45th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR '22), ACM, 2022. 

## Summary

User simulation has been a cost-effective technique for evaluating conversational recommender systems.  However, building a human-like simulator is still an open challenge.  In this work, we focus on how users reformulate their utterances when a conversational agent fails to understand them.  First, we perform a user study, involving five conversational agents across different domains, to identify common reformulation types and their transition relationships.  A common pattern that emerges is that persistent users would first try to rephrase, then simplify, before giving up.  Next, to incorporate the observed reformulation behavior in a user simulator, we introduce the task of reformulation sequence generation: to generate a sequence of reformulated utterances with a given intent (rephrase or simplify).  We develop methods by extending transformer models guided by the reformulation type and perform further filtering based on estimated reading difficulty.  We demonstrate the effectiveness of our approach using both automatic and human evaluation.


## Contents

A temporary version can be downloaded from [here](https://drive.google.com/file/d/1FdBM-XYWoRBhe4oLkQws-2-G5yFxVywD/view?usp=sharing).


## Citation

If you use the resources presented in this repository, please cite:

```
@inproceedings{Zhang:2022:SIGIR,
  author =    {Zhang, Shuo and Wang, Mu-Chun and Balog, Krisztian},
  title =     {Analyzing and Simulating User Utterance Reformulation in Conversational Recommender Systems},
  booktitle = {Proceedings of the 45th International ACM SIGIR Conference on Research and Development in Information Retrieval},
  series =    {SIGIR '22},
  year =      {2022},
  doi =       {10.1145/3477495.3531936},
  publisher = {ACM}
}
```

## Contact

Should you have any questions, please contact Shuo Zhang (szhang611@bloomberg.net).
