# School_District_Analysis

## Overview of the school district analysis
The school board has actioned the project team regarding the discovery that the grades for Thomas High School were untrusted. This analysis aims to manipulate both subjects'  preserving data integrity. The next task is to analyze the school district data for spending and academic foresees in a real scenario with the correct dataset. This project has a deliverable to track on a district level. Therefore, the project team must resolve any attempt to corrupt data at Thomas High School must be determined to avoid impacts on overall rankings.

Results:
- How is the district summary affected?
  - As shown below, the district summary is not significantly effected by the change. This metric takes into account the entire district, so the removal of one ninth grade class from one school only slighlty reduces the average math score, passing reading rate, passing math rate, and overall passing rate.
  - Before:
  ![alt text](https://github.com/GrahamBSereno/School_District_Analysis/blob/main/Resources/DistrictSummaryBefore.png)
  
  - After:
  ![alt text](https://github.com/GrahamBSereno/School_District_Analysis/blob/main/Resources/DistrictSummaryAfter.png)
  
  
- How is the school summary affected?
  - As shown below, the school summary is not significantly effected by the change. The average math score decreased and average reading score increased. These did not affect overall Thomas High School ranking position.
  - Before:
  ![alt text](https://github.com/GrahamBSereno/School_District_Analysis/blob/main/Resources/schoolsummarybefore.png)
  
  - After:
  ![alt text](https://github.com/GrahamBSereno/School_District_Analysis/blob/main/Resources/schoolsummaryafter.png)

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  - As shown below, the removal of the ninth grade reading scores does not affect overall 2nd place rank
  - Before:
  ![alt text](https://github.com/GrahamBSereno/School_District_Analysis/blob/main/Resources/top5before.png)
  
  - After:
  ![alt text](https://github.com/GrahamBSereno/School_District_Analysis/blob/main/Resources/top5after.png)

- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade - as shown below the 9th grade math and reading scores for Thomas High School are removed.
   - Math Before:
   
   ![alt text](https://github.com/GrahamBSereno/School_District_Analysis/blob/main/Resources/mathbefore.png)
  
   - Math After:
  
  ![alt text](https://github.com/GrahamBSereno/School_District_Analysis/blob/main/Resources/mathafter.png)
  
   - Reading Before:
  
  ![alt text](https://github.com/GrahamBSereno/School_District_Analysis/blob/main/Resources/readingbefore.png)
  
   - Reading After:
   
   ![alt text](https://github.com/GrahamBSereno/School_District_Analysis/blob/main/Resources/readingafter.png)
  
- Scores by school spending - As shown below, scores by spending remained largely unchanged with a slight decrease reading passing and passing overall.
  - Before:
  
  ![alt text](https://github.com/GrahamBSereno/School_District_Analysis/blob/main/Resources/spendingbefore.png)
  
  - After:
 
  ![alt text](https://github.com/GrahamBSereno/School_District_Analysis/blob/main/Resources/spendingafter.png)


- Scores by school size - as shown below, scores by spending changed as the medium (1000-2000) group saw reductions in passing math rate, passing reading rate, and overall passing rate.
  - Before:
  
  ![alt text](https://github.com/GrahamBSereno/School_District_Analysis/blob/main/Resources/sizebefore.png)
  
  - After:
  
  ![alt text](https://github.com/GrahamBSereno/School_District_Analysis/blob/main/Resources/sizeafterwards.png)

- Scores by school type - Charter school passing rates dropped accross math, reading, and overall.

  - Before:
  
  ![alt text](https://github.com/GrahamBSereno/School_District_Analysis/blob/main/Resources/typebefore.png)
  
  - After:
  
  ![alt text](https://github.com/GrahamBSereno/School_District_Analysis/blob/main/Resources/typeafter.png)

## Summary:
The main four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs are:
- From a district summary perspective, slight reductions (<0.05) were seen in average math score, passing reading rate, passing math rate, and overall passing rate.
- Reading passing for the scores by size analysis reduced in the medium (1000-2000) school size bucket by approximately 5%.
- In terms of scores by by shool type, the charter school type saw slight reductions in passing math rate, passing reading rate, and overall passing rate (all approx. 5%)
- In scores by spending, the passing reading, passing math, and overall passing rates dropped significantly in the $630-644 bucket. (all near or above 5% reductions)

