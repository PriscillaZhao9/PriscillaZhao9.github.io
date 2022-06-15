---
title: "Projects (To be continued...)"
permalink: "/about/"

---

## [Model Predictive Curiosity for Self-Supervised Dynamics Models](https://docs.google.com/presentation/d/1GrKsUffJ83J_N0HKwWZoL7CbhvsNI7W8tETBHo0l3gs/edit?usp=sharing)

Our project was interested in learning infant self-play behavior, specifically how they learn about the physical dynamics of objects and environments around them through interaction and observation. We took inspiration from Model Predictive Control (MPC) and designed the model predictive curiosity(MPCu) paradigm. Then we set up NVIDIA’s IsaacGym physical simulation environment and Box2D environment. We generated 50000 training scenarios of a force being applied to a circle adjacent to a tower in a Box2D environment and trained a dynamics model to predict forward motion of circle, and a curiosity model to predict the loss in the dynamics model. We believe our framework MPCu is capable of directly optimizing for high curiosity action values and enriching forces that cause multi-object interactions. 

## [Predicting Stackoverflow Post Answer Votes](https://colab.research.google.com/drive/127JK-GEN4FX56nT9uMnR0G77yAg3wEo_?usp=sharing)

Our project was interested in studying what factors make an answer on Stack Overflow popular.  We used SQL to explore the stackoverflow dataset from BigQuery Public Dataset, analyzed the popularity of stack overflow’s answers based on its votes and other characteristics and then visualized the correlations. We found answer count, comment count and score to be the most influential features of the number of votes. Based on our data explorations, we fitted two models: logistic regression and boosted tree classifier to our data and both models resembled fair performance, boosted tree classifier provided predictions with higher quality in terms of accuracy, precision, and ROC-AUC across all three subsets of data: training, validation and testing. 


## [Investigating the Association Between E-book Interactive Features and Learning Outcomes During Bilingual Shared Reading (AERA Poster)](./aera.pdf)

We conducted a secondary analysis to examine the usage of two interactive e-book features,  Multimedia Dictionary and Story Character Statements, and their association with children’s learning and reading motivation outcomes. We found that Story Character Statement hotspots with content congruent to the storyline are associated with lower story comprehension post-test scores and Multimedia Dictionary with content congruent to the story vocabulary but incongruent to the story associated with higher comprehension and retelling scores. These results challenged previous conclusions in the literature that the content of e-book design features has to align with the storyline to support children’s learning. In summary, our findings provided critical implications for future research on e-book design and learning. 

