##RL_Student_elections.ipynb:

1. Input files: a) Student_elections_input.pb
		b) Student_elections_projects.csv
2. Output files: a) votes.csv
		 b) projects_19.csv
		 c) Output text file
		 *a) and b) will be saved to the same directory as the code
		 Output text files are saved in following the directory: a) Output
		 						     
3. Parameters: Set the budget according to number of projects chosen from the pb file.
4. Rewards: values for calculating categorical cost (find_categorical_cost) and target cost (find_target_cost) are manually taken.
		 						  
		 						  		 	
##function names in iterative.ipynb code:

-firstly import all required libraries (install the ones not present on your system using pip installl <library_name>)
-get_data(data)
-intersector(projects_!,projects_2)
-vote_vector_create(votes,num_projects,ids)
-preprocess(file)
-find_target_cost(string)
-find_normalized_cost(val, mu, sigma)
-find_categorical_cost(string)
-reward_calculator(cat_frac, tar_frac, time_cons, budget, selectivity, popularity)
-max_find_list(dictionary)
-max_find(dictionary)
-min_find(dictionary)
-random_find(dictionary)
-category_combination(categories, list_is)
-target_combination(categories, list_is)
-Q_learn(valid_combinations, voter_list, learning_rate, projects, communication_graph, budget, output_file=sys.stdout, num_iter=100, halfselector = 0, epsilon=0.001, decay = 0.2, is_complete_graph = 0, communicated = min_find, randomised_communication = 0, max_degree = 2, Q_interval = 100, agent_needed = 1)

