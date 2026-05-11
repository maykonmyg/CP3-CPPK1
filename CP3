temperaturas = [[28, 31, 34, 33], [25, 27, 29, 28], [32, 35, 36, 34], [24, 26, 25, 27]]

maior_criticos = -1
sala_mais_critica = 0

print("Relatório de Temperaturas por Sala:")

for i, sala in enumerate(temperaturas):
    media = sum(sala) / len(sala)
    criticos = sum(1 for t in sala if t >= 33)
    
    print(f"Sala {i}:")
    print(f"Média: {media}°C")
    print(f"Registros críticos: {criticos}")
    if criticos > maior_criticos:
        maior_criticos = criticos
        sala_mais_critica = i


print(f"Maior critico {sala_mais_critica}, com {maior_criticos} ocorrências.")
