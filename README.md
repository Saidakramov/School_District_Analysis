# School_District_Analysis
## Overview of the school district analysis.
  This analysis aimed to determine the effect of corrupted data on the whole DataFrame. I was informed that Maria and her supervisor detected academic dishonesty regarding Thomas High School's 9th-grade math and reading scores. Therefore, I was tasked to eliminate the corrupted elements in the data and report their effects on the results. 

## Results: 
- How is the district summary affected?
  - Original data district_summary_df :
<img width="926" alt="original district data" src="https://user-images.githubusercontent.com/89552059/179434542-0515cade-d9b3-4cea-80c4-066ec6c00964.png">
   - New district summary df: 
<img width="930" alt="new district data" src="https://user-images.githubusercontent.com/89552059/179434591-d571cdec-26e6-4921-9537-4ba70beebe0e.png">
  Total scores slightly decreased. 

- How is the school summary affected?

  - Original School Summary:
 <img width="977" alt="ths_original" src="https://user-images.githubusercontent.com/89552059/179436825-90fcfff4-a6a1-420c-8880-e25a4021192e.png">
  
  - New School Summary:
<img width="973" alt="ths_new" src="https://user-images.githubusercontent.com/89552059/179436863-a1127583-efe2-413f-af75-7294c91b80f5.png">

As we can see from the data, Thomas High School increased its scores significantly.

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
    - Original top 5 list:
    <img width="972" alt="top5_old" src="https://user-images.githubusercontent.com/89552059/179436963-88aa1e7d-e1a7-4674-a4be-6491804c47b5.png">
    
    - New top 5 list:
<img width="980" alt="Top5" src="https://user-images.githubusercontent.com/89552059/179434703-d7cfd098-425d-40ae-a2a9-793242ebe1fc.png">

Thomas High School remained at the same rank, even though their average scores slightly changed. 

- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade
    - Original math and reading scores:
    <img width="298" alt="math_score_old" src="https://user-images.githubusercontent.com/89552059/179437468-6789e021-faf1-4dce-a383-bb068770a9a2.png">
    <img width="298" alt="reading_score_old" src="https://user-images.githubusercontent.com/89552059/179437506-f3a3eb06-075e-43c1-af22-1b4bf954eba8.png">
    
    - New math and reading scores:
    <img width="304" alt="math_score_new" src="https://user-images.githubusercontent.com/89552059/179437613-fc37d3c6-db4c-4907-a1cc-00ad7c5035f9.png">
    <img width="298" alt="reading_score_new" src="https://user-images.githubusercontent.com/89552059/179437640-37297be5-787c-4d55-94ab-ba5214b7e43c.png">
As we can see, the only differences are between 9ths grade at Thomas High School, where scores are replaced with NaN values.
    
  - Scores by school spending
    - Original School Spending:
    <img width="826" alt="spending_old" src="https://user-images.githubusercontent.com/89552059/179437939-c4d1cae8-db4f-4803-a5a7-bba7b45953ff.png">
     
    - New School Spending:
    
<img width="824" alt="spending_new" src="https://user-images.githubusercontent.com/89552059/179437973-c9ff8a27-5ebe-4e56-9cfb-2c35322191d0.png">

Spending differs very insignificantly for the $630-640 group.
  
  - Scores by school size
    - Original School Size:
    <img width="736" alt="School_type_old" src="https://user-images.githubusercontent.com/89552059/179438223-5355fbc9-35a5-40ce-88f0-8282bbad0247.png">
     
    - New School Size:
    <img width="711" alt="School_type_new" src="https://user-images.githubusercontent.com/89552059/179438261-fbd18d2a-7730-4563-93cf-e1d7d47c9c32.png">

According to the provided files we can notice a slight difference between the Medium(1000-2000) groups.
  - Scores by school type
    - Original School Type:
    <img width="736" alt="School_type_old" src="https://user-images.githubusercontent.com/89552059/179438465-8a98f921-4114-488a-9c89-99194eb7eb45.png">
     
    - New School Type:
    <img width="711" alt="School_type_new" src="https://user-images.githubusercontent.com/89552059/179438492-475f7a28-c04a-4c26-a747-ea1b7095b891.png">

Once again, there is an insignificant change in the Charter group.

# Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
We can notice four changes in district summary, school summary, top school ranking, and math and reading scores. District summary, top school ranking, and math and reading scores showed a minimal difference. However, the school summary shows that Thomas high School increased its rating from 67% to 93% on passing math percentage, from 70% to 97% on passing reading percentage, and from 65% to 91% on overall passing percentage. 
