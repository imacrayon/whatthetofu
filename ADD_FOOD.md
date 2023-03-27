Add restaurant recommendations to this file so we can put them on the website. Please include the restaurant's **name**, **category**, **website**, and any hot tips you might have regarding vegan options.

## Add recommendations below this line:

By MD SHAHIL:-Shahil093

* To add restaurant recommendations to a file *

filename = "restaurant_recommendations.txt"

# Get user input for restaurant information
name = input("Enter the restaurant's name: ")
category = input("Enter the restaurant's category: ")
website = input("Enter the restaurant's website: ")
hot_tip = input("Enter any hot tips for vegan options: ")

# Format the restaurant information
restaurant_info = f"{name} - Category: {category} - Website: {website} - Hot Tip: {hot_tip}"

# Write the restaurant information to the file
with open(filename, "a") as file:
    file.write(restaurant_info + "\n")
    
print(f"{name} has been added to {filename}!")

