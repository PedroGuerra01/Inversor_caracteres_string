def inverter_string(string):
    inverted = ""
    for i in range(len(string)-1, -1, -1):  # Percorre a string de trás para frente
        inverted += string[i]  # Adiciona o caractere atual ao novo string invertido

    return inverted


# Exemplo de string a ser invertida
string_original = "Ola, TARGET!"

# Chama a função para inverter a string
string_invertida = inverter_string(string_original)

# Imprime o resultado
print("String original:", string_original)
print("String invertida:", string_invertida)

Resultado:
Ola, TARGET!
!TEGRAT, alO
