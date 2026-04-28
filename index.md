---
# Do not edit the text between these lines!
layout: default
---

# Overview
This project analyzes student survey data from COMP110 to understand course difficulty and learning support needs.

<!-- This is a comment. Below, you'll see code for inserting an image. To make this image appear, update <custom-path>. To add an image, save it inside the imgs folder of this repository. -->
<img src="/comp110ex9/static/imgs/logo.png" alt="Image of Comp110 rainbow logo." width="500"/>

## Analysis

I explored whether students would benefit from practice problems released after each lecture instead of only a couple days before exams.

## Findings

From the survey data, a noticeable number of students reported moderate to high difficulty in COMP110, with many responses clustering around values 5–7. This suggests that a significant portion of students find the course challenging.

The relationship between difficulty and understanding shows that students who report higher difficulty often report lower understanding, indicating that difficulty may be impacting how well students grasp course material. Additionally, prior programming experience appears to influence how difficult students perceive the course to be, with less experienced students generally reporting higher difficulty.

## Visualizations

The following plots were created to support this analysis:

- Distribution of course difficulty (histogram)
- Understanding vs difficulty (boxplot)
- Prior experience vs difficulty (boxplot)

<img src="/comp110ex9/static/imgs/histo.png" width="500"/>
<img src="/comp110ex9/static/imgs/plot1.png" width="500"/>
<img src="/comp110ex9/static/imgs/plot2.png" width="500"/>

## Conclusion

Overall, the results support the idea that students would benefit from more frequent practice opportunities. Releasing practice problems after each lecture could help students reinforce material while it is still fresh, potentially improving understanding and reducing last-minute studying.

However, this approach may increase workload for both students and course staff, so it would need to be balanced carefully. A possible improvement would be to align practice problems directly with lecture topics and gradually increase difficulty to better support learning progression.