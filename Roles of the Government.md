import os

# Create the directory
os.mkdir("South Africa Government Roles & Responsibilities")

# Create the subdirectories
os.mkdir("South Africa Government Roles & Responsibilities/Economy")
os.mkdir("South Africa Government Roles & Responsibilities/Education")
os.mkdir("South Africa Government Roles & Responsibilities/Health & Social Services")
os.mkdir("South Africa Government Roles & Responsibilities/Law & Justice")
os.mkdir("South Africa Government Roles & Responsibilities/Security")

# Create the files
# Economy
economy_file = open("South Africa Government Roles & Responsibilities/Economy/Roles_and_Responsibilities.txt","w")
economy_file.write("The government of South Africa is responsible for the overall management of the economy. This includes the regulation of economic activity, the provision of public goods and services, the promotion of economic growth, the control of inflation, the protection of consumers and the protection of the environment.")
economy_file.close()

# Education
education_file = open("South Africa Government Roles & Responsibilities/Education/Roles_and_Responsibilities.txt","w")
education_file.write("The government of South Africa is responsible for providing access to quality education for all citizens. This includes the regulation of schools and universities, the allocation of resources to education, the provision of scholarships and financial aid, and the development of policies to improve educational quality and outcomes.")
education_file.close()

# Health & Social Services
health_file = open("South Africa Government Roles & Responsibilities/Health & Social Services/Roles_and_Responsibilities.txt","w")
health_file.write("The government of South Africa is responsible for providing access to health and social services for all citizens. This includes the regulation of healthcare providers, the allocation of resources to healthcare, the provision of social security benefits, and the development of policies to improve healthcare quality and access.")
health_file.close()

# Law & Justice
law_file = open("South Africa Government Roles & Responsibilities/Law & Justice/Roles_and_Responsibilities.txt","w")
law_file.write("The government of South Africa is responsible for providing access to justice for all citizens. This includes the regulation of legal services, the enforcement of laws, the protection of human rights, and the development of policies to improve access to justice.")
law_file.close()

# Security
security_file = open("South Africa Government Roles & Responsibilities/Security/Roles_and_Responsibilities.txt","w")
security_file.write("The government of South Africa is responsible for providing security for its citizens. This includes the protection of the country from external threats, the regulation of law enforcement activities, the maintenance of national defense forces, and the development of policies to protect the nation.")
security_file.close()
