//# porfolio-selection-problem
Design and implement algorithm for optimal portfolio selection considering risk measure, gain measure or combination of them. If two candidates gain same score for any of the above mentioned criteria, consider one with less expected salary and lower age.Parameters to be considered for calculating risk measure, gain
measure:

•	gender
•	age
•	qualification
•	work experience
•	expected salary
•	city
•	etc.


1)  Qualification       		 0.4
2)  Work experience		 0.35	
3)  Salary		           	 0.15
4)  age		           	 0.1



ALGORTIHM :

1) Take the input from file.
2) Calculate the sum of every candidate  priority wise using decided ratio.     
sum[i] +  = (s[i].degree) * 0.4  +  (s[i].expe*0.35) + (s[i].salary*0.15) + 	     	
                  (s[i].age*0.1)
3) Find Optimal sum from all sums by sorting them in descending order.
4) If value of 2 or more sums are same, then compare degree of each   candidate.
           if the degree is same go to step-5.
           else go to step-6.
5) Compare experience of the candidates
          if experience is same ,print both candidates are suitable .
          else print the candidate with more experience .
6) If degree of candidates are different ,print the candidate with higher degree.




