# CMPE 255 Short Story: Automated Feature Engineering for Tabular Data

**Student:** Salih Eren Yuzbasioglu  
**Course:** CMPE 255 — Data Mining, Fall 2026  
**Assignment:** Individual short story / research-paper review  
**Status:** Medium article and YouTube recording linked below. SlideShare publication and final submission checks remain pending.

## Overview

This short story examines how reinforcement learning and generative methods automate feature selection and feature generation for tabular data. It focuses on the reviewed architectures, practical tradeoffs, evaluation design, and limitations.

The topic connects to data preprocessing, feature engineering, dimensionality reduction through feature selection, and model evaluation. This repository is a paper-review assignment, not the separate group final project. It does not claim to reproduce experiments or provide a trained model.

## Main paper

**A Survey on Data-Centric AI: Tabular Learning from Reinforcement Learning and Generative AI Perspective**

Wangyang Ying, Cong Wei, Nanxu Gong, Xinyuan Wang, Haoyue Bai, Arun Vignesh Malarkkan, Sixun Dong, Dongjie Wang, Denghui Zhang, and Yanjie Fu.

- Year: 2025
- Version used: arXiv:2502.08828v2, February 16, 2025
- [Paper record](https://arxiv.org/abs/2502.08828v2)
- [Full PDF](https://arxiv.org/pdf/2502.08828v2)
- [Readable HTML](https://arxiv.org/html/2502.08828v2)
- Publication status used here: arXiv survey; no conference acceptance is claimed.

The title was not present in the spreadsheet copy supplied for preparation. This does not establish instructor approval or guarantee that the live spreadsheet has not changed.

## Deliverables

| Deliverable | Link / status |
|---|---|
| Medium article | [Better Features Before Bigger Models](https://medium.com/@he0kami326412/better-features-before-bigger-models-how-ai-can-improve-the-data-it-learns-from-1db4003a32ae) |
| Presentation video | [Watch on YouTube](https://youtu.be/9PddKqeEpas) |
| PowerPoint slides | [Download PPTX](CMPE255_Feature_Engineering.pptx) |
| PDF slides | [View PDF](CMPE255_Feature_Engineering.pdf) |
| SlideShare presentation | Pending — add the published SlideShare URL |

The slide links expect both files in the same GitHub directory as this README. The YouTube link provides access to the recording. The rubric also asks for the video in the GitHub directory; upload the recording there or confirm that a linked YouTube recording is acceptable.

## Topics covered

- Feature selection versus feature generation.
- RL states, actions, rewards, and single-agent/multi-agent search.
- Cascaded feature generation.
- Encoder–decoder–evaluator architectures and continuous-space search.
- RL/generative combinations and LLM-assisted transformations.
- Predictive quality, search cost, inference cost, and stability.
- Proposed ablations and protection against data leakage.

The evaluation suggestions are proposals, not completed experiments. The survey is not presented as a source of new benchmark scores.

## Supporting survey

Dongjie Wang et al. (2025), [Towards Data-Centric AI: A Comprehensive Survey of Traditional, Reinforcement, and Generative Approaches for Tabular Data Transformation](https://arxiv.org/abs/2501.10555).

This provides context on traditional feature selection and generation. Its overlap in authors and topic with the main survey means it is not independent experimental corroboration.

## Figure attribution

The slides reproduce cropped portions of Figures 2 and 3 from Ying et al., arXiv:2502.08828v2, PDF pages 3–4. Source paper license: [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/). Credit: Wangyang Ying et al. (2025). The figures are source material, not original student drawings. Retain figure credits when reusing the slides.

## Preparation disclosure

AI assistance was used to prepare the initial article draft, narration, and slides. The course rubric requires the published article to be written without AI. The author is responsible for ensuring that the final submission complies with the instructor's policy. The links above were supplied by the student; this README does not certify video duration, topic approval, or rubric compliance.

## Final submission checklist

- [ ] Confirm paper eligibility and topic approval in the spreadsheet.
- [x] Add the Medium article link.
- [x] Add the YouTube presentation link.
- [ ] Upload the PPTX and PDF beside this README.
- [ ] Publish the slides on SlideShare and add its URL above.
- [ ] Verify that the recording lasts 10–15 minutes and includes the slides.
- [ ] Upload the video to the repository, or confirm acceptance of the YouTube link.
- [ ] Verify the final article complies with the instructor's writing policy.
- [ ] Check every public link without signing in.
- [ ] Add this public GitHub directory URL to the class spreadsheet.
- [ ] Submit the same GitHub directory URL in Canvas.
