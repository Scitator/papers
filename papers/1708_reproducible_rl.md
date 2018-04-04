# [Reproducibility of Benchmarked Deep Reinforcement Learning Tasks for Continuous Control](https://arxiv.org/abs/1708.04133)

##### TLDR

**Reproducibility** *refers to the* **ability of a researcher to duplicate the results of a prior study** *using the same materials as were used by the original investigator. (...) Reproducibility is a minimum necessary condition for a finding to be believable and informative.* The paper about the most important issue of the DL/RL field.

- Really interesting to see the gap between reproduced results and published one
- Looks like we need also a code review for the accepted papers.
- New DL field challenge - **reproducibility**:
  - NIPS 2017 - https://nurture.ai/nips-challenge/
  - ICLR 2018 - http://www.cs.mcgill.ca/~jpineau/ICLR2018-ReproducibilityChallenge.html

##### Highlights

Main aspects of reproducibility  (top 5):

- code 
- dependencies (DL framework version, for example)
- availability of datasets (NDA problem, etc) and simulators ($500 for MuJoCo) 
- experimental setup setting (train/test split, random seeds, etc)
- computation resources (the story of Google and 5k gpus)

How to measure RL agent performance?

- ~~Run N experiments, take K best - you are done~~ (but it is how it works now)
- Run N*100 experiments and measure reward mean and std (for each environment)

##### Afterworlds

Things to think about:

- Does Google have `from tensorflow.private import rl_golden_seeds`?
- How can TRPO'15 implementation be better then TRPO'17 one?

##### Interesting links

Video: https://vimeo.com/252185490

Presentation: https://drive.google.com/file/d/1ANKnC-EFDbbPr04xHl7LmEBtD6dKw4vK/view

Review (in russian): https://www.youtube.com/watch?v=FVX7qLe-fZ8