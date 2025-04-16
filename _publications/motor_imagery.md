---
title: "Motor Imagery ECoG Signal Classification With Optimal Selection Of Minimum Electrodes"
collection: publications
category: presentations
permalink: /publication/motor_imagery
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2022-9-28  
venue: 'Neuromatch 5.0 Conference'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
# paperurl: 'http://academicpages.github.io/files/paper1.pdf'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---


<a href="https://doi.org/10.57736/nmc-ae69-494c" target="_blank" style="display: inline-block; padding: 6px 12px; background-color: #566883; color: white; text-decoration: none; border-radius: 4px;">DOI</a>



**Abstract**  
The motor imagery-based Brain-Computer Interface (BCI) converts the motor intention into a control signal by categorizing the electrophysiological patterns of various imaginative activities using ECoG, which has a broader frequency range and more excellent input quality than EEG. Nevertheless, because ECoG is an invasive method, it would be helpful to create an ECoG bidirectional classifier that minimizes the number of implanted electrodes. The current work aims to create a classifier for ECoG signals that can achieve high accuracy with a small number of electrodes. We utilized the ECoG datasets from Miller 2019, which were captured in a clinical environment while seven patients performed motor and imaging tasks with their hands and tongues. We began by removing artifacts from the data before applying a bandpass filter with a frequency range of 8–30 Hz and a notch filter at 60–120–180–240–250 Hz. We then separate the signals into multiple epochs representing the numerous imaging trials used in the experiment. In addition to the entropy, mean, and standard deviation statistical characteristics, we also employed readiness potential (RP) and event-related desynchronization (ERD) as features. We employed support vector machines (SVM) and k Nearest Neighbor (kNN) classifiers for classification. For the recordings, a total of 46 channels were utilized. Compared to other channel combinations, channel numbers 36 and 44, which are situated in the frontal and parietal lobes, respectively, achieved superior classification accuracy. The outcomes demonstrated that KNN performed better than SVM and attained average accuracy of 75.0 and 73.3, respectively. A significant step in creating an ECoG-based BCI will be creating a classification system for various visual signals. Additionally, fewer electrodes will lessen how intrusive future BCI applications are.