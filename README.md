# Workshop on Bayesian Inference

This repository contains materials for my workshop on Bayesian inference held at SWPA 2019 in Albuquerque, NM.. 

## Materials
- Workshop slides ([pdf](bayesWorkshop.pdf))
- [JASP software](http://jasp-stats.org)

## Data sets 
Each of the datasets below is formatted in CSV (comma separated value) format, which is the format required for JASP. You will want to download the files somewhere on your computer. Windows users should "right-click" on the CSV link. Mac users should "ctrl+click" on the CSV link.

- *anagram task* ([csv](https://raw.githubusercontent.com/tomfaulkenberry/bayesWorkshop/master/datasets/anagrams.csv))
  - these data are from an experiment in which subjects were presented with six anagrams (e.g., "RIACH") and asked to verbally unscramble the word. Subjects were randomly assigned to receive either an Organized list containing anagrams from the same category (`listType` = or), or an Unrelated list containing anagrams from six different categories (`listType` = un). Mean solution time (in seconds) for the six anagrams is recorded in `meanTime`.
  
- *kitchen roll experiment* ([csv](https://raw.githubusercontent.com/tomfaulkenberry/bayesWorkshop/master/datasets/kitchen_rolls.csv))
  - these data are from a [paper](https://www.frontiersin.org/articles/10.3389/fpsyg.2015.00494/full) by Wagenmakers et al. (2015), who performed a confirmatory replication of the "kitchen roll" experiment of Topolinski and Sparenberg (2012). In their original study, Topolinski and Sparenberg claimed that clockwise movements of kitchen rolls can induce psychological states of temporal progression and an orientation toward the future and novelty. Specifically, participants who turned kitchen rolls *clockwise* reported more "openness to experience" than participants who turned the kitchen rolls *counterclockwise*. The simplified Wagenmakers dataset here contains two variables: `mean_NEO`, which reflects the mean score on a 12 item subscale of the Neuroticism-Extraversion-Openness Personality Inventory (Costa & McCrae, 1992); and `Rotation`, indicating whether participants were instructed to turn the kitchen rolls *clockwise* or *counterclockwise*.

- *memory task* ([csv](https://raw.githubusercontent.com/tomfaulkenberry/bayesWorkshop/master/datasets/recall.csv))
  - these data are from an experiment in which subjects are asked to recall a list of 24 visually-presented words. Subjects were randomly assigned to one of four conditions given by the factorial combination of two variables: (1) `encodingCue`, denoting whether subjects were also given an extra verbal cue word presented simultaneously with each target (e.g., the experimenter says "desk" while visually showing the target word "CHAIR"); and (2) `retrievalCue`, denoting whether cue words were shown on the answer sheet subjects used during the recall phase.
  
- *mental arithmetic task* ([csv](https://raw.githubusercontent.com/tomfaulkenberry/bayesWorkshop/master/datasets/mental_arithmetic.csv))
  - these data are from an experiment in which subjects were asked to complete as many simple addition problems as possible in 20 seconds. The number of correctly completed problems is recorded as `numCompleted`. Each participant completed two sheets of problems in counterbalanced order; one sheet contained *large* problems (i.e., the sum was 10 or larger), and one sheet contained *small* problems (i.e., the sum was less than 10). Further, participants were randomly assigned to receive problems presented in either *digit* format (e.g., 2 + 7) or *word* format (e.g., "two + seven").

## Example writeups
Examples of how to write the results of the analyses from the workshop can be found [here](writeups.pdf).
