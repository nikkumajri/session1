continents = ["asia", "europe", "northamerica", "southamerica", "africa", "australia", "antartica"]

for continent in continents:
    print(f"i like {continent}!")

code 2 
continents = ["asia", "europe", "northamerica", "southamerica", "africa", "australia", "antartica"]

for continent in continents:
    print(f"i like {continent}!")
code 4 
# topic: sentinels (loop termination with a specific value)
number = 0
while number != -1:  #assiniogn the value as starting 1
    number = int(input("enter a number (or -1 to quiet): "))
    if number != -1:
        print(f"you entered: {number}")
