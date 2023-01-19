import os

# create directory
os.mkdir('ConstitutionIntroduction')

# change directory
os.chdir('ConstitutionIntroduction')

# create files
open('Introduction.txt', 'w')
open('History.txt', 'w')
open('Impact.txt', 'w')

# write introduction
with open('Introduction.txt', 'w') as f:
    f.write('The Constitution of South Africa is the supreme law of the country. It establishes the system of government and the rights of citizens and all people within South Africa. It also provides the framework for the government to ensure the protection and promotion of the rights of all South Africans.')

# write history
with open('History.txt', 'w') as f:
    f.write('The South African Constitution was written in 1996, following the end of apartheid. The Constitution was drawn up by the Convention for a Democratic South Africa (CODESA). It was adopted by the South African Parliament in December 1996 and came into effect on 4 February 1997.')

# write impact
with open('Impact.txt', 'w') as f:
    f.write('The Constitution of South Africa has been instrumental in transforming South Africa from a country of inequality and injustice to one of democracy and human rights. It has provided a framework for the protection and promotion of the rights of all South Africans, and has enabled the country to become a beacon of hope for many around the world.')
