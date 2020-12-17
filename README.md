# Bootstrapping-for-the-best-regression
This was a class project for a university course I attend. 
The professor created a 2 variable data with 1000 0000 data points, the variables were linearly related Y = alpha + beta*x + error
I used bootstrapping to find the best approximations of alpha, beta which minimize error term ‘error’. Since I do not have the who data, I won’t be able to know the error ( I believe the professor will evaluate my solution by comparing my result to the true line.)
boot() - boot() function from boot R package was used for creating samples. lm() - lm() function from stats package was used to fit linear models. pam()- PAM clustering (with 1 cluster center) was used to find the mediods of x,y variables separately.

Comments
•	The sampling method used in Bootstrap 2020 Student.R was replaced by boot() function as recommended.
•	PAM clustering with 1 center returns the medoid of the data. SInce the data is almost perfectly gaussian, I believe the mean can be a better measure of center.
•	boot package does a much faster sampling.

References
[1] AM 2020 Topic 3.2 Bootstrapping ok at moodle page for the course ‘Advanced Microeconomics’ at UW. 
[2] https://www.statmethods.net/advstats/bootstrapping.html 
[3] Sample code ‘Bootstrap 2020 Student’ at moodle page for the course ‘Advanced Microeconomics’ at UW.

