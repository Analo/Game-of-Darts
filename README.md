# Question One: Darts Function

Let us play a game of darts. Shall we? You know darts? I bet you do! Either way, I shall give you a very simple explanation. Darts is a fame where players throw darts to a target. The target is often circular and in this case, it will be circular as well. In our particular instance of the game, the target rewards with 4 different amounts of points, depending on where the dart lands.

If the dart lands outside the target, player earns no points (0 points),:( 
If the dart lands in the outer circle of the target, player earns 1 point, 
If the dart lands in the middle circle of the target, player earns 5 points, 
If the dart lands in the inner circle of the target, player earns 10 points,:D

The outer circle has a radius of 10 units(This is equivalent to the total radius of the entire target), the middle circle a radius of 5 units, and the inner circle a radius of 1. Of course, they are all entered to the same point (That is, the circles are concentric) defined by the coordinates (0,0)

Your job...err...task, is to write a function(let us call it score) that given a point in the target (defined by its real cartesian coordinates x and y), returns the correct amount earned by a dart landing in that point.

Example:
>>> score(0, 10) 1
X coordinate here is 0, while Y coordinate is 10, score is 1 

                                                  <<< END OF QUESTION >>>
-------------------------------------------------------------------------------------------------------------------------------------
SOLUTION:

## Setting Up the Environment

Step1: Install python on your machine depending on the Operating System you are using. https://www.python.org/downloads/
                  --Used Version: 3.7.7 ---

Step2: Install Pytest. https://docs.pytest.org/en/latest/getting-started.html
                   --Used Version: 5.4.1 ---


Step3: Download  this repository on your local environment.

## Running the Test

To run the tests you need to pass the name of the testsuite file to pytest. As shown below.

To run the tests, run `pytest score_test.py`

Alternatively, you can tell Python to run the pytest module:
`python -m pytest score_test.py`

You can also run score.py module using python  to see the results of  dart landing in different points .

   >>> score (0,10)
   >>> 1
   >>> score (0,5)
   >>> 5
   >>> score (0,1)
   >>> 10


