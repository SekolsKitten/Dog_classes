#create a dog class
class dog:
  #class attributes
    species = "Canis familiaris"
    
#Inatializer / Constructer
    def __init__(self, name, age, breed):
        self.name = name
        self.age = age
        self.breed = breed

    #Methods (AKA Functions inside of a class)
    def bark(self):
        return f"{self.name} says Woof!"
    
    def zoomie(self):
        return f"{self.name} runs in circles like there crazy."
    
    def dog_math(self, num1, num2):
        answer = num1 + num2 
        return f"{num1} + {num2} = snack time for {self.name}, and {answer} for hoomans."
    
dog1 = dog("Buddy", 5 ,"Golden Retriver")
dog2 = dog("Max", 2 ,"Pitbull")

print(dog1.name)
print(dog1.age)
print(dog1.breed)
print(dog1.bark())
print(dog2.name)
print(dog2.age)
print(dog2.breed)
print(dog2.bark())


class GermanShepherd(dog):
    def guard(self):
        return f"{self.name} is guarding!"

gs_dog = GermanShepherd("Prowler", 6 , "German Shepherd")
print(gs_dog.name)
print(gs_dog.age)
print(gs_dog.breed)
print(gs_dog.guard())
