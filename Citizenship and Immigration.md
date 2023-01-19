import gym
import numpy as np

env = gym.make("SouthAfricaCitizenship-v0")

def create_directory():
    # Initialize a list to store the rights of citizenship
    rights_of_citizenship = []
    # Iterate through the available actions
    for action in range(env.action_space.n):
        observation, reward, done, info = env.step(action)
        rights_of_citizenship.append(observation)
    # Initialize a list to store the rules for immigration
    rules_for_immigration = []
    # Iterate through the available actions
    for action in range(env.action_space.n):
        observation, reward, done, info = env.step(action)
        rules_for_immigration.append(observation)
    # Create a dictionary to store the directory of rights and rules
    directory = {
        'rights_of_citizenship': rights_of_citizenship,
        'rules_for_immigration': rules_for_immigration
    }
    return directory

# Create the directory of rights and rules
directory = create_directory()

# Print the directory
print(directory)
