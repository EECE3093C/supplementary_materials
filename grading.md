# Grading

For EECE3093C grades will be assigned based on your overall, weighted class average using the weighting scheme presented below.

| Category.            | Weight |
|:--------------------:|:------:|
| Assignments, Quizzes | 40%    |
| Team (Lab) Project   | 60%    |
|                      | 100%   |


<br/>

## Team Project Grade

The progress of the team will be evaluated at the end of each development iteration. In order to ensure continuous progress throughout the semester, the grading for the project will be based on the following weighting scheme.


| Iteration   | Due Date                  | Weight, $w_i$ |
|:-----------:|:-------------------------:|:------:|
| Iteration 1 | February 15, 2023 @ 11:59 |  0%    |
| Iteration 2 | March 1, 2023 @ 11:59     | 10%    |
| Iteration 3 | March 29, 2023 @ 11:59    | 20%    |
| Iteration 4 | April 12, 2023 @ 11:59    | 35%    |
| Iteration 5 | April 27, 2023 @ 11:59    | 35%    |
|             |                           | 100%   |


During our class discussions, we have established that the layered approach to software engineering comprises of four layers: quality, process, methods, and tools. These layers will be utilized as assessment categories when evaluating each development iteration, with equal weightage assigned to each category.


| Category | Weight |
|:--------:|:------:|
| Quality  | 25%    |
| Process  | 25%    |
| Methods  | 25%    |
| Tools    | 25%    |
|          | 100%   |


Multiple criteria within each category will be evaluated on a 5-point Likert scale, ranging from -2 to 2, and the overall category score will be determined by taking the average of all the criteria scores in that category. The team iteration grade, $G_i$, will be calculated as follows:

- Let $Q_i$, $P_i$, $M_i$, and $T_i$ denote the scores for the quality, process, methods, and tools categories respectively, for the i-th iteration.
- Let $q_{ij}$, $p_{ij}$, $m_{ij}$, and $t_{ij}$ denote the score for the $j$-th criterion in the quality, process, methods, and tools categories respectively, for the i-th iteration.  The score for the $j$-th criterion in any category can range from $-2$ to $2$.
- The overall score for category $P$, $Q$, $M$, or $T$ for the i-th iteration is the average of the scores for all $n$ criteria in that category:

  - $Q_i = \frac{1}{n} \sum\limits_{j=1}^{n} q_{ij}$
  - $P_i = \frac{1}{n} \sum\limits_{j=1}^{n} p_{ij}$
  - $M_i = \frac{1}{n} \sum\limits_{j=1}^{n} m_{ij}$
  - $T_i = \frac{1}{n} \sum\limits_{j=1}^{n} t_{ij}$

The overall team iteration grade, $G_i$, is calculated as the weighted average of the scores for all four categories, multiplied by the iteration weight, $w_i$.  Since the categories are equally weighted, each category contributes $\frac{1}{4}$ to the overall iteration grade:

$$G_i = w_i \cdot \frac{1}{4}(P_i + Q_i + M_i + T_i)$$

Or:

$$G_i = w_i \cdot \frac{1}{4}\left(\dfrac{1}{n}\sum\limits_{j=1}^{n}q_{ij}\right) + w_i \cdot \frac{1}{4}\left(\dfrac{1}{n}\sum\limits_{j=1}^{n}p_{ij}\right) + w_i \cdot \frac{1}{4}\left(\dfrac{1}{n}\sum\limits_{j=1}^{n}m_{ij}\right) + w_i \cdot \frac{1}{4}\left(\dfrac{1}{n}\sum\limits_{j=1}^{n}t_{ij}\right)$$

<br/>

## Student Project Grade 

At the end of each development iteration, each student's contribution to the project will be evaluated by both peers and instructors. Based on this evaluation, each student will receive an iteration contribution factor denoted by $w_{i,cf}$, which will range between 0.7 and 1.1.

The student iteration grade, $g_i$, is the overall team iteration grade, $G_i$, multiplied by the student's iteration contribution factor, $w_{i,cf}$:

$$g_i = w_{i,cf} \cdot G_i$$

<br/>

#### Student Project Semester Grade 

The student's overall semester grade for the project, $g$, is the sumation of all iteration grades:

$$g = \sum\limits_{i=1}^{m}g_i$$

or, 

$$g = \sum\limits_{i=1}^{m}(w_{i,cf} \cdot G_i)$$

expanded futher,

$$g = \sum\limits_{i=1}^{m}\left( w_{i,cf} \cdot w_i \cdot \frac{1}{4}\left(\dfrac{1}{n}\sum\limits_{j=1}^{n}q_{ij}\right) + w_{i,cf} \cdot w_i \cdot \frac{1}{4}\left(\dfrac{1}{n}\sum\limits_{j=1}^{n}p_{ij}\right) + w_{i,cf} \cdot w_i \cdot \frac{1}{4}\left(\dfrac{1}{n}\sum\limits_{j=1}^{n}m_{ij}\right) + w_{i,cf} \cdot w_i \cdot \frac{1}{4}\left(\dfrac{1}{n}\sum\limits_{j=1}^{n}t_{ij}\right) \right)$$


<br/>

## The 5-Point Scale

Project assessments as well as individaul assessments will uses a 5-point Likert-type scale.  The table below is provided to help with your interpretation of the scale, and how it will translate into your academic grade.

| Scale, $s_5$ | Interpretation #1 | Interpretation #2 | Interpretation #3 | Individual Contribution Factor | Academic Scale, $s_a$ | 
|:--:|:--:|:--:|:--:|:--:|:--:|
| 2 | Almost Always | Very Good | Excellent | 1.1 | 100 |
| 1 | Often | Good | Above Average | 1.0 | 90 |
| 0 | Sometimes | Fair | Average | 0.9 | 80 |
|-1 | Seldom | Poor | Below Average | 0.8 | 70 |
|-2 | Almost Never | Very Poor | Poor | 0.7 | 60 |


#### Conversion to Academic Scale

The scores from the 5-point scale, $s_5$, are mapped to the academic scale, $s_a$, using a conversion formula that restricts the mapped scores to a range between 60 and 100, rather than utilizing the full 100-point scale. The conversion formula is as follows:

$$s_a = 60 + (10 \cdot (s_5 + 2))$$



