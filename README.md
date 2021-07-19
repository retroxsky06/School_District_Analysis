# School_District_Analysis

## Overview of the School District Analysis
The purpose of this project is to analyze data for a School District, such as student funding and student standardized test scores, to provide insight on performance trends that may inform discussion at the District level. Additionally, to uphold state-testing standards, a second analysis was conducted due to evidence of academic dishonesty at a specific high school.

## Software
Python 3.8, Anaconda, Jupyter Notebook

## Results
Due to evidence of academic dishonesty by ninth graders at Thomas High School, the school district analysis was conducted twice.  The frist analysis utilized the entire data that was provided, while the second analysis omitted ninth grade students' math and reading scores from Thomas High School (THS).  Ninth graders from THS had their scores replaced with NaN.  The following DataFrames represent summaries for the District and School after replacing THS ninth graders with NaN.

### District Summary
![District Summary](District%20Summary%20.png)

#### District Summary Results
    - The overall passing percentage had decreased by .1%
    - The reading passing percentage had decreased by .3%
    - The math passing percentage had decreased by .2%
    
### School Summary after replacing THS ninth
![School Summary](School%20Summary%20.png)

#### School Summary Results
    - The overall passing percentage had fallen to 65% compared to the intial value of 90% in the first  
      analysis.
    - The reading passing percentage had fallen to 70% compared to the intial value of 97% in the first analysis.
    - The math passing percentage had fallen to 67% compared to the intial value of 93% in the first analysis.
    
Using bulleted lists and images of DataFrames as support, address the following questions.
- How is the district summary affected?
- How is the school summary affected?
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- How does replacing the ninth-grade scores affect the following:
    - Math and reading scores by grade
    - Scores by school spending
    - Scores by school size
    - Scores by school type

District Summary
- overall passing: 0.1% decrease
- .3 % decrease om reading passing
- -,1 decrase average math
- .2 decrease math passing overall
School Summary


## Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.



