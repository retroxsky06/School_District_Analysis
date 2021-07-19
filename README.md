# School_District_Analysis

## Overview of the School District Analysis
The purpose of this project is to analyze data for a School District, such as student funding and student standardized test scores, to provide insight on performance trends that may inform discussion at the District level. Additionally, to uphold state-testing standards, a second analysis was conducted due to evidence of academic dishonesty at a specific high school.

## Software
Python 3.8, Anaconda, Jupyter Notebook

## Results
Due to evidence of academic dishonesty by ninth graders at Thomas High School (THS), the school district analysis was conducted twice.  The frist analysis utilized the entire data that was provided, while the second analysis omitted ninth grade students' math and reading scores from THS.  Ninth graders from THS had their scores replaced with NaN.  The following DataFrames represent summaries for the District and School after replacing THS ninth graders with NaN.

### District Summary
![District Summary](District%20Summary%20THS.png)

#### District Summary Results
- The overall passing percentage had decreased by 0.1%.
- The reading passing percentage had decreased by 0.3%.
- The math passing percentage had decreased by 0.2%.
    
### School Summary 
![School Summary](School%20Summary%20THS.png)

#### School Summary Results
- The overall passing percentage had fallen to 65% compared to the intial value of 90% in the first analysis.
- The reading passing percentage had fallen to 70% compared to the intial value of 97% in the first analysis.
- The math passing percentage had fallen to 67% compared to the intial value of 93% in the first analysis.
    
Additional finds of replaced ninth grade values with NaN:
- For the spending range of $630-644 per student, the overall passing percentage decreased by 0.1%.
- Despite the ninth grade values being ommitted, schoool rankings did not change.  THS was found to retain their number two ranking in performance in the school district among their tenth to twelfth graders.

### Scores by School Spending
![Spending Summary](Spending%20Summary.png)
Through the above DataFrame, it is revealed that average scores and passing percentages do not increase as spending per student increases.  This may infer that other factors other than funding may be occurring and may need further examination.

### Charter vs District Schools
![ChartervsDistrict](Charter%20vs%20District.png)
This analysis highlights that the Charter schools within the school district generally performed better than District Schools. As seen above, Charter schools have a 36% higher overall passing percentage in comparison to District Schools. The top five schools with the highest overall passing scores were Charter Schools, compared to the bottom five that were all District schools. Replacing the ninth-grade scores with NaN did not have an impact on these values.

## Summary
As the District's School Board was unable to determine the extent of the academic dishonesty, the entire ninth grade class of Thomas High School had their math and reading scores omitted from the results.

Replacing the ninth grade students' scores with NaN had altered Thomas High School's average scores and overall passing percentage as they had decreased significantly.  Furthermore, the math and reading scores, and overall passing percentage of the School Distract as a whole decreased.  In spite of the expunged ninth grade math and reading scores, Thomas High School presered their placement as number two in the District.

