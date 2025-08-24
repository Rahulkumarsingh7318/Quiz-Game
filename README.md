# Quiz-Game

print ("Welcome to my computer Quiz!")

playing = input("Do you want to play ?(Yes/No) ")

if playing.lower() != "yes" :
    quit()

print("Okay! Let's play :)")
print("                                               ")
point =0

print("Q1 Which gas is most abundant in Earth’s atmosphere?")
print("a)  Oxygen")
print("b)  Nitrogen")
print("c)  Carbon dioxide")
print("d)  Hydrogen")
answer = input(str("Enter one option :"))
if answer == "b":
    print('Corret Answer!')
    point+=1
else:
    print("Wrong Answer")

print("                                               ")

print("Q2: The Great Wall of China was built mainly to protect against invasions from ?")
print("a) Mongols ")
print("b) Persians  ")
print("c) Romans")
print("d) Turks")
answer = input(str("Enter one option :"))
if answer == "a":
    print('Corret Answer:)')
    point+=1
else:
    print("Wrong Answer:(")

print("                                               ")

print("Q3: The Taj Mahal was built by which Mughal emperor?")
print("a) Babur")
print("b) Akbar")
print("c) Aurangzeb")
print("d) Shah Jahan")
answer = input(str("Enter one option :"))
if answer == "d":
    print('Corret Answer:)')
    point+=1
else:
    print("Wrong Answer:(")

print("                                               ")

print("Q4: Pluto is define as dwarf planet in which year: ")
print("a) 2002")
print("b) 2004")
print("c) 2006")
print("d) 2008")
answer = input(str("Enter one option :"))
if answer == "c":
    print('Corret Answer:)')
    point+=1
else:
    print("Wrong Answer:(")

print("                                               ")

print("Q5: Which sport is known as the king of sports ")
print("a) Cricket")
print("b) Football")
print("c) Basketball")
print("d) Tennis")
answer = input(str("Enter one option :"))
if answer == "b":
    print('Corret Answer:)')
    point+=1
else:
    print("Wrong Answer:(")

print("                                               ")

print("Q6: What is the name of the longest bone in the human body? ")
print("a) Tibia")
print("b) Humerus")
print("c) Femur")
print("d) Patella")
answer = input(str("Enter one option :"))
if answer == "c":
    print('Corret Answer:)')
    point+=1
else:
    print("Wrong Answer:(")

print("                                               ")

print("Q7: Which of the following is the capital city of Mongolia ? ")
print("a) Ulaanbaatar")
print("b) Astana")
print("c) Tashkent")
print("d) Bishkek")
answer = input(str("Enter one option :"))
if answer == "a":
    print('Corret Answer:)')
    point+=1
else:
    print("Wrong Answer:(")

print("                                               ")

print("Q8: Which of the following is the only mammal capbale of true flight? ")
print("a) Flying Squirrel")
print("b) Flying Lemur")
print("c) Sugar glider")
print("d) Bat")
answer = input(str("Enter one option :"))
if answer == "d":
    print('Corret Answer:)')
    point+=1
else:
    print("Wrong Answer:(")  

print("                                               ")

print("Q9: The Nile River flow through how many countries? ")
print("a) 17")
print("b) 15")
print("c) 13")
print("d) 11")
answer = input(str("Enter one option :"))
if answer == "d":
    print('Corret Answer:)')
    point+=1
else:
    print("Wrong Answer:(")

print("                                               ")

print("Q10: In which year did the Indian Space Research Organisation (ISRO) formed ?  ")
print("a) 1971")
print("b) 1969")
print("c) 1965")
print("d) 1963")
answer = input(str("Enter one option :"))
if answer == "b":
    print('Corret Answer:)')
    point+=1
else:
    print("Wrong Answer:(")

print("                                               ")

print("**************************************")
print ("Total Score :",point,"/10")
print("**************************************")
