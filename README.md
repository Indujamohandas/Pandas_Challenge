# Pandas_Challenge
Using Pandas and Jupyter lab,Follwing analysis has been performed from the given CSV file in the resources folder.
District Summary
Perform the necessary calculations and then create a high-level snapshot of the district's key metrics in a DataFrame.
Include the following:
Total number of unique schools
Total students
Total budget
Average math score
Average reading score
% passing math (the percentage of students who passed math)
% passing reading (the percentage of students who passed reading)
% overall passing (the percentage of students who passed math AND reading)
output:
Total Schools	Total Students	Total Budget	Average math score	Average reading score	%passing math	%passing reading	%overall pass
0	15	        39170	            24649428	    78.985371	          81.87784	            74.980853	      85.805463	      65.172326Include the following School Summary:
School name
School type
Total students
Total school budget
Per student budget
Average math score
Average reading score
% passing math (the percentage of students who passed math)
% passing reading (the percentage of students who passed reading)
% overall passing (the percentage of students who passed math AND reading)
Output:
School types	              Total Students	Total Budget	per student budget	Average math score	Average reading score	%passing math	%passing reading	%overall pass
Bailey High School	District	4976	              3124928.0	       628.0	              77.048432	         81.033963	          66.680064	     81.933280	     54.642283
Cabrera High School	Charter	1858	                1081356.0	    582.0	                83.061895        	83.975780	            94.133477      	97.039828	     91.334769
Figueroa High School	District	2949	            1884411.0	      639.0	               76.711767	        81.158020	            65.988471	      80.739234	    53.204476
Ford High School	District	2739	                1763916.0      	644.0	                77.102592	         80.746258	          68.309602	      79.299014	    54.289887
Griffin High School	Charter	1468	                917500.0	      625.0	                 83.351499	        83.816757	           93.392371	    97.138965	    90.599455
Performed highest and lowest performing school based on the %overall pass
calculations to create a DataFrame that lists the average math scoreand reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.
created four bins with reasonable cutoff values to group school spending
Created a DataFrame called size_summary that breaks down school performance based on school size (small, medium, or large).
Used the per_school_summary DataFrame from the previous step to create a new DataFrame called type_summary.




