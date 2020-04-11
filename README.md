# prostaklasapython
class Person:
    def __init__(self, NAME, SURNAME):
        self.NAME = NAME
        self.SURNAME = SURNAME

    def __init__(self, NAME, SURNAME, AGE, ACHIEVEMENT):
        self.NAME = NAME
        self.SURNAME = SURNAME
        self.AGE = 17
        self.ACHIEVEMENT = ACHIEVEMENT = [0, 1]

    def getName(self):
        self.NAME = input("Podaj imie:")

    def getSurname(self):
        self.SURNAME = input("Podaj nazwisko: ")

    def getAge(self):
        self.AGE = int(input("Podaj wiek: "))

    def addAchievement(self):
        achievement = int(input("Dodaj osiagniecie: "))
        self.ACHIEVEMENT.append(achievement)

    def getAchievement(self):
        list = self.ACHIEVEMENT
        print("Lista osiagniec: ", list)

Osoba1 = Person("JAN", "NOWAK", 17, [0, 1])
print(Osoba1.NAME)
print(Osoba1.SURNAME)
print(Osoba1.AGE)
Osoba1.getAchievement()


Osoba1.getName()
print(Osoba1.NAME)

Osoba1.getSurname()
print(Osoba1.SURNAME)

Osoba1.getAge()
print(Osoba1.AGE)

Osoba1.addAchievement()
Osoba1.addAchievement()

Osoba1.getAchievement()
