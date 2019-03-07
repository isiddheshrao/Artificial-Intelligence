Name:Siddhesh Rajesh Rao
UTA ID:	1001666614
Net ID:	sxr6615
Language: Python 2.4 (Runs on Omega)

Task 1:
Code Structure:	
Import Observations, Check length and sequence. Compute probability loop based on
given prior h probabilities and probabilities of cherries and lime.
write to result file "result.txt" after every observation in the observation sequence

Execution:
python compute_a_posteriori.py observations
Example: 
python compute_a_posteriori.py CCLLCLCL


Task 2:
Code Structure:	Import Arguments. Initialize Combinations and truth value dictionary of 
given arguments. "Class BayesianNetwork" consists of functions to calculate probability (computeProbability()) and total probability (Total_prob())
Given probability values are stored in variables in "__init__"
Result is printed for the provided arguments

Execution:
python bnet.py [arguments]
python bnet.py query1 query2.. given observation1..
(You can only provide a maximum of 6 arguments)
Example: 
python bnet.py At Bf given Mt
python bnet.py Bt Af Mf Jt Et