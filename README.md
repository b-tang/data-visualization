# Data Visualization
Analyzes EEG data to identify neural markers of student confusion.

## Presentation
You can watch my presentation at: [Data and Analysis](https://youtu.be/zc-GnnFezZY)

## Motivation
Accurately identifying student confusion is crucial for educators to tailor content delivery and ensure maximum comprehension. Current methods rely on students requesting help and teachers sensing confusion, which are often unreliable and leave some students behind, affecting academic performance. Neural activity across EEG bands (delta to low gamma) has been linked to cognitive events, and early studies suggest a correlation between these bands and confusion levels. If confirmed, this could enable the development of systems to monitor and quantify student confusion, improving classroom feedback and enhancing learning outcomes.

## Approach
The dataset includes 12,000 EEG data points from the frontal cortex of ten subjects as they watched videos on confusing and straightforward topics, with confusion levels rated on a 1–7 scale. The team plans to analyze correlations between EEG bands and confusion, measure R-values to assess predictive power, and explore the influence of demographics and inter-band relationships over time, aiming to visually clarify how EEG bands relate to confusion levels.

## Milestones
**Preliminary Design**: The initial dashboard will display core information on student confusion correlates, mainly scatter plots of EEG bands and confusion levels, along with demographic relationships to confusion.

**Final Design**: The final version will add filtering options for EEG band variation by student, heatmaps showing the relationship between two bands with confusion levels, and bar charts indicating feature correlation with confusion based on R-values. A comparison of machine learning algorithms predicting confusion from EEG bands will be included, if time allows.

**Approach**: We will start by creating the preliminary charts and conduct a literature review to identify neural correlates and underlying neurophysiological relationships.

## Extensions
Beyond this course, the project can be extended by:  
1. Comparing metrics of reconstructed EEG signals (e.g., fractal dimensionality, area under the curve) with confusion levels for more detailed insights.  

2. Analyzing data from more participants, as a sample size of ten is too small for robust conclusions.
  
3. Designing an experimental setup where the technology used for videos does not interfere with EEG impedance, as proximity to devices can introduce noise and affect results.

## Tools
Tableau will be used for data visualization. MATLAB will be used for data cleaning and signal
reconstruction.

## References
[1] T. Xu, J. Wang, G. Zhang, L. Zhang, and Y. Zhou, “Confused or not: decoding brain activity and
recognizing confusion in reasoning learning using EEG,” Journal of Neural Engineering, vol. 20, no.
2, Mar. 2023, doi: https://doi.org/10.1088/1741-2552/acbfe0.

[2] “Confused student EEG brainwave data,” www.kaggle.com.
https://www.kaggle.com/datasets/wanghaohan/confused-eeg (accessed Mar. 19, 2024).

[3] J. Z. Liu, Q. Yang, Bra. Yao, R. W. Brown, and G. H. Yue, “Linear correlation between fractal
dimension of EEG signal and handgrip force,” Biological Cybernetics, vol. 93, no. 2, pp. 131–140, Jul.
2005, doi: https://doi.org/10.1007/s00422-005-0561-3.
