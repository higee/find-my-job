### Find My Job 
---
#### Brief Introduction
* "Is data scientist right career path for me?" was the start of this project. (hopefully)
* I thought I could find core comepetencies by analyzing job descriptions for data scientist on LinkedIn.
* I gathered data('key qualification' and 'responsibilites') on 'digital marketer' and 'UI/UX designer' in case those two job positions turn out to be better match.
* ...with preprocessing all done, the model is set to answer my question. 
* Then, All I need to do is type my competencies or personality either in words or full sentences, and check recommended job among 'data scientist', 'digital marketer', and 'UI/UX designer'!

#### Limits and Learnings 
* Considering the fact that 'Find My Job' was my ever first data-analysis project, it was great experience to go through whole process. However, there was a large question mark over the project itself. I wasn't sure whether 'find my job' is an adequate, appropriate topic for machine learning problem. This was ironically due to (way) too high classification score. Theoretically, the ceiling of the performance (as far as I know) cannot outperform that of human classifier. 
* My conclusion was the model used here oversimplified the problem. It scans the input text data and find words that are in their 'bag of words' (if not, they are all ignored) and calculate the probability of belong to either class0, 1, or 2. 
* And also, pipeline or gridsearch is an awesome tool in that I could get optimal value with a single code. And I was, to some extent, relying on them before fully understanding their implications on my model! I think the helpfulness goes up in direct proportion to how much I know!
