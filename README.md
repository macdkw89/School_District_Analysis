# School District Analysis


## Overview
The purpose of this analysis was to remove potentially dishonest test scores from the dataset. Once the problematic test scores are removed, we will re-run the analysis code to see how these changes have affected to outcome of the overall analysis.

_______________________
## Results

Below, we have images of the analysis dataframes for THS both before and after the fraudulent scores have been removed

Before:

![before removal](/resources/THS_summary.png)

After:

![after removal](/resources/THS_adjusted_summary.png)

When looking at the results once 9th graders have been removed from the data, we see that Math scores went down slightly, and Reading scores went up slightly. 

_______________________________
### How is the district summary affected?
The district summary was not greatly affected by removing just one grade level from one school in the data. All of the changed values were negated by the formatting and rounding we did later in the analysis. Here are image links to the district summary with the rounding/formatting removed.
[before removal](/resources/district_summary.png) / 
[after removal](/resources/district_adjusted_summary.png)

### How is the school summary affected?
The school summary as a whole was not greatly affected by the data removal. The only changes occured were Thomas High School's scores.

### THS performance relative to other schools
images:

- [before removal](/resources/comparison_before.png)
- [after removal](/resources/comparison_after.png)

When compared to other schools, the results do not change THS's ranking in overall passing percentage. However, before scores were removed, THS was ranked 4th in Math scores, and 5th in Reading scores. After scores were removed, THS moved down to 6th in Math scores but stayed the same in reading. 

### How does replacing 9th grade scores affect...

- Math and reading scores by grade were only affected on the 9th grade column for THS where we added NaNs.

- Scores by school spending, size, and type were all largely unaffected as well. There were minor differences (about +-0.01%) in the bins where THS was placed. 

## Summary
1. The largest and most obvious difference in the updated analysis is that the 9th grade data for THS is replaced with NaNs, which was the entire objective of this revised analysis. 
2. Another change to the data was THS's ranking in math compared to other schools. Before, THS was ranked 4th in math, but moved down to 6th once removed. The ranking for reading stayed the same. 
3. Thomas High Schools overall passing rate went from 90.948012% to 90.630324%, a decrease of 0.317688%.
4. The Overall Passing % in the spending range $630-644 went from 62.857656% to 62.778233%, a decrease of 0.079423%.