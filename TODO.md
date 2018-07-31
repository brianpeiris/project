Implement these commands:

	# Create an issue and add it to the given column, opening an editor 
	project issue add alpha todo 
	# Create an issue and add it to the given column, using the given message string
	project issue add alpha todo -m 

	# Move and issue in a column
	project issue move alpha todo 33 bottom
	project issue move alpha todo 33 top
	project issue move alpha todo 33 after 22
	project issue move alpha todo 33 before 22

	# Remove an issue from a column
	project issue remove alpha todo 33

	# List all issues in a colum
	project issue list alpha todo
