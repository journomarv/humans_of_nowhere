import os

# Create a directory 'Sovereign Powers of the State in South Africa'

os.makedirs("Sovereign Powers of the State in South Africa")

# Create a list of the sovereign powers 

sovereign_powers = ["Legislature","Executive","Judiciary","Public Service","Police","Military"]

# Create a file for each sovereign power 

for power in sovereign_powers:
    file = open(os.path.join("Sovereign Powers of the State in South Africa",power + ".txt"), "w")
    file.write("This file contains information about the "+ power + " of South Africa.")
    file.close()
