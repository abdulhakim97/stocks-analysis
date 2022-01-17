# stocks-analysis

#Overview of Project 
#Explain the purpose of this analysis:
	The purpose of this analysis was to make the code more efficient by looping their all of the same data while making new edits of the code to get a faster and more efficient results. This allows the code to be much more readable and help future developers to write better code for group projects and allows the program to require less steps and less memory.  

#Results: 
With the first logical code the overall run time of the 2018 execution was so much slower than the new refraction code. 

<img width="143" alt="image" src="https://user-images.githubusercontent.com/96555487/149686590-e9ce5362-8217-4317-badc-6637dd03be5a.png">

With the updated code the overall run time of the execution was so much faster, in fact there was a notable difference of lag between them.

<img width="126" alt="image" src="https://user-images.githubusercontent.com/96555487/149686610-be6fd008-fc4c-4124-9cdb-bc36c47b6fc7.png">

The difference of code was the new variables and for loops being run in the new refraction code. The first variable made was the tickerIndex in which we set it to zero in order to use it for 4 different arrays in the later steps. Another major difference was the 4 different arrays that held specific data type. This gave the code less memory to use which helped the program run much faster.

<img width="419" alt="image" src="https://user-images.githubusercontent.com/96555487/149686662-6af945e5-5277-4169-b6c2-9a71bda8859d.png">

The same was done with the tickerVolume in order to initialize it for the dataset. The main difference between the two code is how the tickerIndex is being used as the variable for the rest of the iteration in order to quickly access the other arrays. The if-then conditional is relatively the same for both code.  

#Summary:
One of the major advantages of refactoring the code is how much faster the program will run compare to when it’s not. In fact, after doing several run tests you could initial tell how much faster refracting the code is. On top of that refactoring code is so much easier to read than unedited version. This could be helpful in group or team coding project where you would need to read a code and it has less steps to read overall than its counterpart. A disadvantage of refactoring code is that you could potentially mess up the entire macro and end up having a huge bugging problem if not done correctly, this could be a much bigger headache then it initially is. 
This applied to the original VBA script since when it was first presented there was bit of a huge bugging issue and error that I couldn’t put my finger on and even though it was cleaner to read writing the code was a bit more difficult to come up with than the example since it required a lot more iteration knowledge. 
