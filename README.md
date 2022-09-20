# Doce-ou-travessura
N = int(input("Digite o número de crianças: "))
M = int(input("Digite o número de chocolates para cada criança: "))
C = int(input("Digite o numero total de barras de chocolate: "))

sobra = int(C - (N*M))

print("\nApós dar " + str(M) + " chocolates para cada criança, o Sr. Prezens ficou com um total de " + str(sobra) + " chocolates.")
