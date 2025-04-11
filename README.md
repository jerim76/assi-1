# assi-1class Superhero:
    def __init__(self, name, power, city):
        self.name = name
        self.power = power
        self.city = city

    def show_identity(self):
        print(f"I am {self.name}, protector of {self.city}!")

    def use_power(self):
        print(f"{self.name} uses {self.power}!")

# Inherited class
class FlyingHero(Superhero):
    def __init__(self, name, power, city, flight_speed):
        super().__init__(name, power, city)
        self.flight_speed = flight_speed

    def fly(self):
        print(f"{self.name} is flying at {self.flight_speed} km/h!")

# Example usage
hero1 = Superhero("ShadowKnight", "Invisibility", "Neo City")
hero1.show_identity()
hero1.use_power()

hero2 = FlyingHero("SkyBlaze", "Firestorm", "Sky Havclass Vehicle:
    def move(self):
        raise NotImplementedError("Subclasses should implement this!")

class Car(Vehicle):
    def move(self):
        print("Driving 🚗")

class Plane(Vehicle):
    def move(self):
        print("Flying ✈️")

class Boat(Vehicle):
    def move(self):
        print("Sailing 🚤")

# Function to demonstrate polymorphism
def travel(vehicle):
    vehicle.move()

# Example usage
car = Car()
plane = Plane()
boat = Boat()

travel(car)
travel(plane)
travel(boat)
en", 300)
hero2.show_identity()
hero2.use_power()
hero2.fly()

Assignme2 


