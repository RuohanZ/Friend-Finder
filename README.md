# Friend Finder - Node and Express Servers

###https://morning-inlet-37669.herokuapp.com/

### Compatibility based application

* The application will take in results from users' surveys then compare their results against all other users who have completed it. The application will then display the name of the user with the best match overall.

* The survey has 10 questions, answers to the survey questions are on a scale of 1-5 based on how much the user agrees or disagrees.


## Technical details
* Compatibility will be determined based on the following.
* Convert each user's results into a simple array of numbers (ex: [5, 1, 4, 4, 5, 1, 2, 5, 4, 1]).
	* With that done, compare the difference between current user's scores against those from other users, question by question.    Add up the differences to calculate the totalDifference.
		* Example: 
			* User 1: [5, 1, 4, 4, 5, 1, 2, 5, 4, 1]
			* User 2: [3, 2, 6, 4, 5, 1, 2, 5, 4, 1]
			* Total Difference: 2 + 1 + 2 = 5

	* The person with the closest match will be the one with the "least" amount of difference.

* Once the closest match has been determined, it will display the name of the best match back to the user in the form of a modal pop-up. 

