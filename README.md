# School_District_Analysis

## Overview of the school district analysis
This analysis is mainly to give Maria---a chief data scientist insights about performance trends and patterns on student funding and students' standardized test. The data was aggregated and tables of key metrics based on different parameters were showcased. The result of this analysis will assist the school board and superintendent in making decisions regarding the school budgets and priorities.

After evidence of academic dishonesty was discovered for the reading and math grades of Thomas High School ninth graders. Math and reading scores of Thomas High School were replaced with NaNs in order to uphold the state-testing standards. School district analysis was repeated while keeping the rest of the data intact. The key school district metrics were compared to see how the changes made affect the results. 

## Results

### How is the district summary affected?

Observing the two outputs of district summary, we can see that Average Math Score, % Passing Math, % Passing Reading and % Overall Pass all dropped. % Overall Pass has the largest decrease of 0.3%. 

Original Result

![Old_district_summary](https://user-images.githubusercontent.com/84931545/126057916-6c0fbb2c-39e9-4d48-81c7-f8832215b204.PNG)

New Result

![New_district_summary](https://user-images.githubusercontent.com/84931545/126057919-1a99d4a3-d45b-4048-acb9-ec0388ee624b.PNG)


### How is the school summary affected?

The only change is within Thomas High Schools statistics. 
% Passing Math, % Passing Reading and % Overall Passing increased dramatically.
% Passing Math increased from 66.911315% to 93.272171%, % Passing Reading increased from 69.663609% to 97.308869% and % Overall Passing increased from 65.076453% to 90.948012%. 

Original school summary 

![Old_school_summary](https://user-images.githubusercontent.com/84931545/126058116-7833cea8-bcac-4b83-801f-5b4dfc47572d.PNG)

New school summary

![New_school_summary](https://user-images.githubusercontent.com/84931545/126058119-cc0388c4-acc8-461b-a0dd-8c83bfa1ae2f.PNG)



### How does replacing the ninth graders' math and reading score affect Thomas Hich School's performance relative to the other schools?

Originally Thomas High School is not one of the top 5 schools; Replacing the ninth grades' math and reading score make Thomas High School become one of the top five schools. It is the second best school based on % Overall Passing. 

Original Top 5 schools based on % Overall Passing

![Original_top_5](https://user-images.githubusercontent.com/84931545/126057932-6d515e9a-b2a3-4c33-b5e7-a9efd26b96d0.PNG)

New Top 5 schools based on % Overall Passing

![New_top_5](https://user-images.githubusercontent.com/84931545/126057936-2e6fd2f4-af50-47e0-9d78-defd72372e66.PNG)


### How does replacing the ninth-grade scores affect the following

#### Math and reading scores by grade.

The only thing that is changed on both math and reading scores by grade is the output on the Thomas High School '9th' column is now 'nan'.

Original Math score by grade
    
![Old_by_math_grade](https://user-images.githubusercontent.com/84931545/126057944-450c83c9-a72b-46c0-aa8c-14fb92330821.PNG)

New Math score by grade

![New_by_math_grade](https://user-images.githubusercontent.com/84931545/126057951-66f25ee7-e7dc-4d16-86ae-ff1627c4e08b.PNG)

Original Reading score by grade
    
![old_by_reading](https://user-images.githubusercontent.com/84931545/126057965-25c8fd48-73a9-4e40-93dd-bc2f697798e4.PNG)

New Reading score by grade

![new_by_reading](https://user-images.githubusercontent.com/84931545/126057973-e6386b91-64c9-43cc-95a6-fe5e910db431.PNG)


#### Scores by school spending

For the $630-$644 spending ranges (Per Student), % Passing Math increased from 67% to 73%, % Passing Reading increased from 77% to 84%, and % Overall Passing increased from 56% to 63%. 

Original school spending
    
![old_school_spending](https://user-images.githubusercontent.com/84931545/126057983-c4fc6925-da0a-4709-ac29-e724284e6c7d.PNG)
    
New school spending

![new_school_spending](https://user-images.githubusercontent.com/84931545/126057987-84bc77aa-f122-431a-a9fc-24f7a9f3c409.PNG)

#### Scores by school size

For School Size Medium(1000-2000), % Passing Math increased from 88% to 94%, % Passing Reading increased from 91% to 97%, and % Overall Passing increased from 85% to 91%.

Original school Size
    
![Original_school_size](https://user-images.githubusercontent.com/84931545/126057989-81d68166-2c4e-4435-8841-c6f0b175100d.PNG)

New school Size
    
![New_school_size](https://user-images.githubusercontent.com/84931545/126057995-1d6f2ce8-c0d2-4e4c-822f-2f974f31b665.PNG)

    
#### Scores by school type

Charter school type is affected by the change since Thomas High School's school type is Charter. % Passing Math increased from 90% to 94%; % Passing Reading increased from 93% to 97%; % Overall Passing increased from 87% to 90%.

Original scores by school type
    
![Original_school_type](https://user-images.githubusercontent.com/84931545/126058026-b548868e-a8f4-4a1f-984b-e7a1a10aa925.PNG)

New scores by school type
    
![New_school_type](https://user-images.githubusercontent.com/84931545/126058033-38ef6f3c-3bd8-496d-9f4e-fbd21b4ac84e.PNG)


## Summary
