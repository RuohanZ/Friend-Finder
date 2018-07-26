# Friend Finder - Node and Express Servers

### Compatibility based application

* The application will take in results from users' surveys then compare their results against all other users who have completed it. The application will then display the name of the user with the best match overall.

* The survey has 10 questions, answers to the survey questions are on a scale of 1-5 based on how much the user agrees or disagrees.


## Technical details
* Compatibility will be determined based on the following.
*Convert each user's results into a simple array of numbers (ex: [5, 1, 4, 4, 5, 1, 2, 5, 4, 1]).
*With that done, compare the difference between current user's scores against those from other users, question by question.    Add up the differences to calculate the totalDifference.
*Example:
*User 1: [5, 1, 4, 4, 5, 1, 2, 5, 4, 1]
*User 2: [3, 2, 6, 4, 5, 1, 2, 5, 4, 1]
*Total Difference: 2 + 1 + 2 = 5
*Remember to use the absolute value of the differences. Put another way: no negative solutions! Your app should calculate both *5-3 and 3-5 as 2, and so on.
*The closest match will be the user with the least amount of difference.
