tipo = input("(-,+,*,/)\nqual função vc deseja fazer ? \n")

primeiro_numero = int(input("qual o primeiro numero da função ? \n"))
segundo_numero = int(input("qual o segundo numero da função ? \n"))

if tipo == "+":
  final = primeiro_numero + segundo_numero
  
elif tipo == "-":
  final = primeiro_numero - segundo_numero

elif tipo == "/":
  final = primeiro_numero / segundo_numero

elif tipo == "*":
  final = primeiro_numero * segundo_numero


print("O resultado é ",final)