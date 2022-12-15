# [Unifying Vision, Text, and Layout for Universal Document Processing](https://arxiv.org/pdf/2212.02623)
[Zineng Tang](https://zinengtang.github.io/),
[Ziyi Yang](https://ziyi-yang.github.io/),
[Guoxin Wang](https://www.guoxwang.com/),
[Yuwei Fang](https://www.microsoft.com/en-us/research/people/yuwfan/),
[Yang Liu](https://nlp-yang.github.io/),
[Chenguang Zhu](https://cs.stanford.edu/people/cgzhu/),
[Michael Zeng](https://www.microsoft.com/en-us/research/people/nzeng/),
[Cha Zhang](https://www.microsoft.com/en-us/research/people/chazhang/),
[Mohit Bansal](https://www.cs.unc.edu/~mbansal/)
              
## Code Release [Here](https://github.com/zinengtang/i-Code/tree/main/i-Code-Doc)

Code is rehosted at part of [the i-code project](https://github.com/zinengtang/i-Code/tree/main/i-Code-Doc)

## Open Source Checklist:

- [x] Release Model (Encoder + Text decoder)
- [ ] Release Most Scripts
- [ ] Vision Decoder / Weights (Due to fake document generation ethical consideration, we plan to release this functionality as an Azure API)
- [ ] Demos


## Introduction 

UDOP unifies vision, text, and layout through vision-text-layout Transformer and unified generative pretraining tasks including
vision task, text task, layout task, and mixed task. We show the task prompts (left) and task targets (right) for all self-supervised objectives
(joint text-layout reconstruction, visual text recognition, layout modeling, and masked autoencoding) and two example supervised objectives
(question answering and layout analysis).

<p align="center">
  <img align="middle" width="800" src="udop.png"/>
</p>

