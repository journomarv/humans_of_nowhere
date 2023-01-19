# Importing the necessary libraries
import os
import re

# Setting the directory path
directory_path = 'Constitution_Summary'

# Creating a new directory
os.mkdir(directory_path)

# Setting the file path
file_path = os.path.join(directory_path, 'Constitution_Summary.txt')

# Opening the file
f = open(file_path, 'w+')

# Writing the content to the file
f.write('# Constitution of South Africa Summary\n\n')
f.write('The Constitution of South Africa is the supreme law of the country. It sets out the fundamental rights of all people in South Africa and enshrines the values of human dignity, equality, and freedom. It also outlines the structure and functions of the government, and the roles of citizens.\n\n')
f.write('The Constitution is important to South Africans as it protects their rights, freedoms, and interests, and provides the foundation for a just and equitable society. It is a reminder of the values of the country and serves as a beacon for how South Africans should live and how the government should act.\n\n')
f.write('The Constitution is a living document that is constantly evolving as South Africa's society and government changes. As South Africans, it is our duty to stay informed and be aware of our rights and responsibilities under the Constitution.\n')

# Closing the file
f.close()
