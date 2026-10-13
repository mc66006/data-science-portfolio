# [Your Name] | Data Science Portfolio

Hello! I am a CISC7204 student building practical skills in data analysis and visualization. I enjoy turning a clear question into a reproducible analysis and communicating both the result and its limitations.

## Technical skills

Python · pandas · NumPy · Matplotlib · Jupyter Notebook · GitHub

## Project showcase

### Study Time, Tutoring, and Course Scores

**Research question:** In a hypothetical student sample, how is focused weekly study time associated with final course scores, and how do scores compare between students with and without tutoring?

![Scatterplot of simulated study hours and final course scores](images/study-hours-vs-score.png)

In this simulated example, scores increase more quickly up to about 15 study hours per week and then rise more slowly. The tutoring group is generated with a higher score pattern at the same study time. These patterns are built into synthetic data and do not show that studying or tutoring causes higher scores. The score ceiling also compresses high scores.

![Boxplot comparing simulated score distributions for tutoring and no-tutoring groups](images/score-distribution-by-tutoring.png)

The second figure compares the score distributions by tutoring status. It provides a group-level view of spread and overlap, complementing the study-hours scatterplot. Since tutoring status and its score offset were specified when generating the data, the difference is illustrative rather than evidence of a real tutoring benefit.

![Binned score comparison showing tutoring differences](images/binned-score-comparison.png)

Peer feedback noted that the 0-100 score ceiling compresses the high-hour observations near the top of the chart. I addressed this with a high-hour diagnostic: its top panel compares binned group means with descriptive 95% confidence intervals on a clearly labeled, zoomed 85-100 axis; its lower panel shows the percentage of observations capped at 100, with sample counts annotated. This helps inspect differences while making the ceiling effect and small-bin uncertainty visible.

- **Project repository:** [Study Time, Tutoring, and Course Scores](https://github.com/mc66006/data-science-project)
- **Status:** Completed (simulation-based demonstration)

## Contact

For course-related discussion, please use the contact method approved for our class. This public page intentionally omits personal contact details.
