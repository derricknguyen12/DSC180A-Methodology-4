---
layout: default
title: SDG&E Capstone
---

# Derrick Nguyen

**Email:** dtn020@ucsd.edu

**Section:** San Diego Gas & Electric (SDG&E) - B19
**Mentor:** Phi Nguyen

---

**1. What is the most interesting topic covered in your domain this quarter?**  
One of the most interesting topics that was covered this quarter was analyzing operational efficiency at SDG&E using historical scheduling and task data, particularly the Click system. The Click data provides detailed records of task assignments, planned versus actual durations, and crew activities, which allowed us to explore patterns in work completion and identify inconsistencies in reported task times. I found it fascinating how much insight you can gain into human behavior and operational bottlenecks just by analyzing task timestamps, durations, and crew assignments. Specifically, we investigated “gaming the system,” where crews may report durations inaccurately, and used Click data to detect these anomalies. This not only highlighted the challenges in predicting realistic task durations but also informed ways to optimize scheduling, making operations more efficient and reliable for both crews and customers.

**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**  
For my Quarter 2 project, I would like to investigate the phenomenon of “gaming the system” within SDG&E’s scheduling data. Gaming occurs when crews report inaccurate task durations or manipulate task records, which can distort the effectiveness of scheduling algorithms and obscure true operational efficiency. Using both Click and Geocall data, I would analyze discrepancies between planned versus actual task times, looking for patterns or outliers that indicate intentional or systematic misreporting. The investigation could involve building a classification model to identify which tasks or crews are likely gaming the system, and quantifying how these behaviors impact scheduling accuracy and resource allocation. Ultimately, this study could provide actionable insights for improving schedule reliability, minimizing idle time, and ensuring that field operations reflect actual work performed.

**3. What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**  
One potential change I would make to the Quarter 1 approach is to incorporate more advanced anomaly detection techniques when identifying “gaming the system” in the scheduling data. In the current project, we primarily focused on simple comparisons between planned and actual task durations to flag outliers. For Quarter 2, I would explore machine learning–based methods, such as clustering or isolation forests, to automatically detect unusual patterns in crew performance across different task types. This would allow us to better account for nuances like task complexity, crew experience, and travel time, rather than relying solely on fixed thresholds. By doing so, the analysis would be more robust and provide a clearer understanding of which deviations are due to human error versus intentional misreporting.

**4. What other techniques would you be interested in using in your project?**  
For my project, I would be interested in using machine learning techniques to detect anomalies and optimize scheduling. Specifically, I could apply classification models to predict whether a task has been “gamed” based on features like planned vs. actual duration, task type, crew experience, and district. Additionally, unsupervised techniques such as clustering or isolation forests could help identify unusual patterns in task durations that may indicate misreporting or inefficiencies. I’m also interested in exploring regression models to better predict realistic task durations, accounting for factors like travel time, task complexity, and crew skill level, which could inform more accurate and feasible scheduling decisions.
