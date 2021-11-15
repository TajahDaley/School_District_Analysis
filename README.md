# School_District_Analysis
The purpose of this Analysis was to look at the 15 different schools and see how they compare with each other along the lines of academics between grades, budgets, and passing scores. We looked at many things as we compared the different schools. As we were going through the process of breaking down the information and forming the multiple data frames needed everything seemed smooth until we finished, and it was noticed that the 9th grade Thomas High School statistics was altered and we needed to remove this from our data. Let's take a deeper look at some of the changes.

# Results
As we were editing the code to filter out the 9th grade Thomas High School information there were quite a few changes, and you could see some of them impacted the school greatly.

![image](https://user-images.githubusercontent.com/92553694/141719970-3047acd4-fc56-44eb-8d08-b57c44391766.png)


  1) looking at the image the % percent passing reading, math and overall, you can see are drastically lower than the other schools. That's because the altered data was removed leaving a lower percentage of kids passing than other schools. 
  2) since altering the code to remove the grades for the 9th grade at Thomas High School. if someone wanted to look at the average scores, they would now look like this. This will easily raise eyebrows during the next board meeting.
 
 ![image](https://user-images.githubusercontent.com/92553694/141720129-245d6317-3834-49c5-a91f-b7a918f8a884.png)
  
  3) There was a small change when looking at the two school types (Charter and District) with having to change the data the difference was very slight but still noticeable. 
  
  4) Another change that was noticed was when looking at Thomas High School without taking out the 9th graders the % of passing math, reading, and both negatively affected the school greatly. 
  
  5) To make things look a little bit clearer we need to adjust the code to not have 9th graders in it so that we don't have to look at "NaN" or any other missing values. 
  6) Although a chunk of Thomas High School's data needed to be nulled it still turned out to be a top 5 school which goes to show that the other grades are doing really well and are able to hold the school up. 
  7) The budgeting for the school should barely any difference with a extremely low change which will be barely noticed. Meaning without the data for the 9th grade the budgeting is still roughly the same 

# Summary
With this big mishap at the Thomas School there were many changes some that have already been discussed. With the Statistics needing to be removed a lot of the Data frames will look slightly different. As stated earlier the budgeting portion of the Analysis was barely affected by the altering of the information making this easier to look over. But with Missing information if wanting to compare the grades between the different schools grades(9th-12th) will be very hard because of the now missing information. Also looking at the percentages of the kids passing math or passing reading between the schools Thomas High School will show poor grades because of the NaN information. Hopefully Thomas High School can fix the issue with forging the data and giving clean data so that we can clearly analyze the data for them.
