# TemperaturaCalculadora
print("Bem Vindo ao Conversor de Temperaturas!!\n")

medida = input("Qual medida você deseja usar?: ")

if medida.upper() == "CELSIUS":
    print("Medida selecionada: CELSIUS")
    
elif medida.upper() == "KELVIN":
    print("Medida selecionada: KELVIN")
    
elif medida.upper() == "FARENHEIT":
    print("Medida selecionada: FARENHEIT") 
else:
    print("INSIRA UM VALOR VÁLIDO!!!")
print("\n")

qntd = float(input("Quanto equivale essa medida?: "))

print("Sua medida é de:", qntd, "°", medida.upper())
print("\n")

medida2 = input("Para qual medida você deseja converter?: ")

if medida2.upper() == "CELSIUS":
    print("Medida selecionada: CELSIUS")

elif medida2.upper() == "KELVIN":
    print("Medida selecionada: KELVIN")

elif medida2.upper() == "FARENHEIT":
    print("Medida selecionada: FARENHEIT")

else:
    print("INSIRA UM VALOR VÁLIDO!!")
print("\n") 

if medida.upper() == "CELSIUS" and medida2.upper() == "KELVIN":
    resultadoCxK = qntd + 273.15
    print("Sua medida em", medida2, "é de:", resultadoCxK, "°", medida2)

elif medida.upper() == "KELVIN" and medida2.upper() == "CELSIUS":
    resultadoKxC = qntd - 273.15
    print("Sua medida em", medida2, "é de:", resultadoKxC, "°", medida2)

else:
    print("MAURICIO")
