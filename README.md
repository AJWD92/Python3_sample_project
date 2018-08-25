# Python3_sample_project
#Var set for description of lovely loveseat
lovely_loveseat_description = """Lovely Loveseat. Tufted polyester blend on wood. 32 inches high x 30 inches deep. Red or white."""
#Var set for price of lovely loveseat
lovely_loveseat_price = 254.00
#Var for description of stylish sette
stylish_sette_description = """Stylish Sette. Faux leather on birch. 29.50 inches high x 54.75 inches wide x 28 inches deep. Black."""
#Var for price of stylish sette
stylish_sette_price = 180.50
#Var for luxurious lamp description
luxurious_lamp_description = """Luxurious Lamp. Glass and iron. 36 inches tall. Brown with cream shade."""
#Var for price of luxurious lamp
luxurious_lamp_price = 52.15
#Var to calculate sales tax on items
sales_tax = .088
#Var for customer one total from items purchased
customer_one_total = 306.15
#Var for customer ones itemization
customer_one_itemization = ""
#Var adding lovely love seat description to customer one itemization
customer_one_itemization += lovely_loveseat_description
#Var adding luxurious lamp price to customer one total
customer_one_total += luxurious_lamp_price
#Var adding luxurious lamp description to customer one itemization
customer_one_itemization += luxurious_lamp_description
#Var for calculating sales tax to customer one total
customer_one_tax = customer_one_total * sales_tax
#Var for adding sales tax to ending total of customer one
customer_one_total += customer_one_tax
#Prints str "Customer One Items:"
print("Customer One Items:")
#Prints custome_one_itemization list below previous str
print(customer_one_itemization)
#Prints str "Customer One Total:"
print("Customer One Total:")
#Prints customer_one_total below previous str
print(customer_one_total)
#Creates Var for customer_two_total
customer_two_total = 0
#Var for customer two itemization
customer_two_itemization = ""
#Var to add stylish sette price to customer two total
customer_two_total += stylish_sette_price
#Var adding description of stylish sette to customer_two_itemization
customer_two_itemization += stylish_sette_description
#Var adding luxrious lamp to customer two total
customer_two_total += luxurious_lamp_price
#Var adding luxurious lamp description to customer two itemization
customer_two_itemization += luxurious_lamp_description
#Var to calculate customer two sales tax
customer_two_tax = customer_two_total * sales_tax
#Var adding sales tax to customer two total
customer_two_total += customer_two_tax
#Prints str "Customer Two Items:"
print("Customer Two Items:")
#Prints var customer_two_itemization below previous str
print(customer_two_itemization)
#Prints str "Customer Two Total:"
print("Customer Two Total:")
#Prints var customer_two_total below previous str
print(customer_two_total)
