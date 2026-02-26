#Captain Cook Robot bartender
#WelcomeCustomer
print("Goodday and welcome to captain cook")
name=input("We would like to know your name \n")
#Dictionary containning orders (can be updated)
menu = {
    "Meatpie": 6,
    "Chicken": 4,
    "Friedrice": 8,
    "Jollofrice": 7,
    
}
print ("Here is is todays menu : Meatpie, Jollofrice, Chicken, Friedrice\n ENSURE THE FIRST LETTER OF YOUR ORDER IS CAPITAL")
order = input("What would you like today?\n")
if order in menu:
    price = menu[order] 
else:
    print("That is not available today ") 
    sys.exit()
try:
    quantity=int(input("How many of that would you like? \n"))
except ValueError :
    print("Please enter a number")
    sys.exit
bill= price * quantity
print (f"Okay {name} that would be {bill} dollars")
print("My master is Blessed join us letstake over")
