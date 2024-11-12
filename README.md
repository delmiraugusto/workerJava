
# Worker Program

Este projeto é um programa Java para gerenciar informações de trabalhadores, seus contratos de trabalho e calcular a renda mensal com base nos contratos registrados.

## Estrutura do Projeto

- `application/WorkerProgram.java`: Contém o programa principal para interação com o usuário e exibição dos dados.
- `entities/Department.java`: Classe que representa o departamento de um trabalhador.
- `entities/HourContract.java`: Classe que representa um contrato por hora.
- `entities/Worker.java`: Classe que representa o trabalhador, contendo seus dados pessoais e a lista de contratos.
- `enums/WorkerLevel.java`: Enumeração para representar o nível do trabalhador (por exemplo, Junior, Mid, Senior).

## Funcionalidades

- Solicita dados do trabalhador, como nome, nível e salário base.
- Solicita dados dos contratos de trabalho, incluindo data, valor por hora e duração.
- Permite calcular a renda do trabalhador para um mês específico com base nos contratos.

## Exemplo de Uso

1. Insira o nome do departamento.
2. Insira o nome, nível e salário base do trabalhador.
3. Informe o número de contratos e, para cada contrato, insira a data, valor por hora e duração.
4. Insira o mês e o ano para calcular a renda do trabalhador no período especificado.

### Exemplo de Saída

```
Enter department's name: Sales
Enter worker data:
Name: John Doe
Level: SENIOR
Base salary: 3000.00
How many contracts to this worker? 2

Enter contract #1 data:
Date (DD/MM/YYYY): 20/08/2023
Value per hour: 50.00
Duration (hours): 20

Enter contract #2 data:
Date (DD/MM/YYYY): 13/08/2023
Value per hour: 60.00
Duration (hours): 15

Enter month and year to calculate income (MM/YYYY): 08/2023

Name: John Doe
Department: Sales
Income for 08/2023: 4100.00
```

## Tecnologias Usadas

- Java
- Pacotes e classes Java para manipulação de datas (`SimpleDateFormat` e `Date`)
- Scanner para entrada de dados do usuário
