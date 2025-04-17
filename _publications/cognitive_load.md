---
title: "Understanding  Cognitive Load in Virtual Reality (VR) Environments: A Machine Learning Approach"
collection: publications
category: presentations
permalink: /publication/motor_imagery
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2025-5-9 
venue: '7th International Digital Culture & AudioVisual Challenges Conference - Corfu, Greece' 
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
# paperurl: 'http://academicpages.github.io/files/paper1.pdf'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
<a href="https://avarts.ionio.gr/dcac/2025/en/dates/" target="_blank" style="display: inline-block; padding: 6px 12px; background-color: #566883; color: white; text-decoration: none; border-radius: 4px;">LINK</a>

**Abstract**  
*Introduction* :  
 Virtual Reality (VR) has become a prominent tool in education, training, and gaming due to its immersive capabilities. In education, VR enhances cognitive processes and knowledge retention by offering immersive learning experiences. Similarly, the gaming industry has increasingly adopted VR to meet the growing demand for interactive and realistic environments. VR is also widely used in training simulations, where it replicates real-world scenarios effectively[1]. However, despite its advantages, evidence suggests that VR environments can elevate cognitive load—the mental effort required to process information in working memory[2]. The high cognitive load associated with VR can negatively impact learning outcomes, performance, and user comfort, leading to challenges like performance decline and cybersickness.  


*Objective :*  
In our research, we propose a method for measuring cognitive load in VR through specialized brain games designed to progressively increase mental effort. These games provide a controlled environment to dynamically assess cognitive load using machine-learning techniques. As a first step, we investigated cognitive load differences between VR and desktop gameplay using  Form Fusion reasoning game adapted from Neuronation mobile application. In this game, users merge displayed shapes using arithmetic operations, engaging their logical thinking abilities.  By analyzing response times and performance metrics, our preliminary results indicate that participants had longer response times in VR, suggesting a higher cognitive load compared to desktop gameplay.  

*Experiment and Methods :*  
The study involved a VR adaptation of the Form Fusion reasoning game, which consists of 15 levels of increasing difficulty to progressively elevate cognitive load. At each level, users are presented with shapes to merge and four possible options representing the final merged shape. The user must select the correct option. The game was played using the HTC VIVE headset with Tobii eye-tracking technology. Participants used VR controllers with ray interaction to select answers by hovering over an option for one second to confirm. Unity Game Engine was used for game development.
The study recruited six participants (three male, three female), aged between 24 and 30, with varying levels of VR experience. Before starting, participants provided consent agreeing to participate voluntarily and for anonymous data collection. They were introduced to the VR equipment and completed a training session on the mobile app to familiarize themselves with the game. The experiment began with eye calibration using Tobii Mirrors software. The calibration process involved guiding participants in correctly positioning their headsets, adjusting the interpupillary distance (IPD) for visual clarity, and performing a five-point calibration to ensure accurate eye-tracking data. During gameplay, data was recorded in a CSV file, including eye-tracking metrics (fixation counts, fixation duration, blinks, and saccades), response times, and performance accuracy.
Performance metrics were used as labels, where incorrect answers signified high cognitive load, and correct answers indicated low cognitive load. Machine learning models, including logistic regression, decision trees, and SVM, were used to predict user performance in a binary classification problem. 

*Results and Conclusion :*  
Analysis of the response times revealed that participants took longer on levels 2, 9, and 1. We hypothesize that this observation can be attributed to specific characteristics of these levels. Levels 2 and 9 required users to perform subtraction operations, which likely increased cognitive load. Level 1, being the introductory level, required participants to familiarize themselves with the VR environment, potentially contributing to longer response times. Additionally, levels 6 and 8 had the lowest accuracy rates, possibly due to the inclusion of both addition and subtraction operations, which made them more challenging. The machine learning models demonstrated accuracy rates ranging from 72% to 77%, with SVM achieving the highest accuracy. However, the reliability of these models is questioned due to class imbalance in the dataset which may have caused the models to be biased toward predicting the majority class, potentially overestimating their performance.

*Future Work :*  
Future research will address class imbalance by incorporating more participants and increasing the difficulty of the game levels to create a more balanced dataset. A larger dataset is crucial for obtaining more reliable results. For accurate data labeling, ground truth methods, such as measuring pupil diameter and analyzing, will be used. This will contribute to a better understanding of cognitive load and engagement during gameplay, providing a more comprehensive view of the factors influencing cognitive load and performance in VR environments.  
 

*References:*   
[1]Akdere M., Jiang Y.,Acheson K.,2023,Human Resource Development Quarterly,34,437  
[2]Zhang L., Liu G., 2023, IEEE 12th International Conference on Educational and Information Technology(ICEIT).pp48–52