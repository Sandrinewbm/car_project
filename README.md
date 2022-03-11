# creating the car class
class Car:
    # initializer / attributes
    def __init__(self, color, type, year):
        self.color = color
        self.type = type
        self.year = year

    # method for displaying the car infromation
    def displayInformation(self):
        print("\nThis is a newly created car, and it has the following infromation....")
        print("This is a", self.color, self.type, "car, from the year",self.year,"" .format(self.color, self.type, self.year))

# instantiating 3 car models objects of the car class / and calling the method which displays the car infromation
# first car model object
car_one = Car('red', 'Toyota Corola seden', '1999')
car_one.displayInformation()
print("Here is the first car model.")

# second car model object
car_two = Car('white', 'Toyota Hillux pick-up', '2010')
car_two.displayInformation()
print("Here is the second car model.")

# third car model object
car_three = Car('blue', 'Honda CRV cross-over', '2007')
car_three.displayInformation()
print("Here is the third car model.")
