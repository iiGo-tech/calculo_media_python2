# ***Calculadora de Média de Alunos Python***

Um programa simples em python que tem como objetivo calcular
a média de um aluno, baseado em duas notas.

## ***Tecnologias Usadas***

- Python v. 3.14.4

## ***Como executar?***

Usar uma IDE de sua preferencia, ou um compilador online.
Exemplo: (onecompiler.com/python) Copie o código e então execute.
```
def calcular_media(nota1, nota2):
    return (nota1 + nota2) / 2
    
print("=== Sistema de Notas do Aluno ===")
    
n1 = float(input("Digite a primeira nota: "))
n2 = float(input("Digite a segunda nota: "))
    
media = calcular_media(n1, n2)
    
print(f"A média final é: {media:.2f}")
    
if media >= 7.0:
    print("Status: APROVADO!")
        
else:
    print("Status: REPROVAO!")
```

##### *Autor - Igor Brito Ferreira*

###### Meios de Contato https://www.linkedin.com/in/igor-brito-8aa357248
