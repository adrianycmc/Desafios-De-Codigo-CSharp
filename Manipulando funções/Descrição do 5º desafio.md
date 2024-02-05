## **Descrição**

Vamos desenvolver uma ferramenta para calcular a pegada de carbono de uma pessoa, dessa forma, crie **variáveis** como `nome`, `quilometrosPorDia`, `horasDeEletronicos`, `refeicoesComCarne` para armazenar as respectivas entradas do usuário. Para o cálculo da pegada, crie uma função CalcularPegadaDeCarbono que opera através da utilização de fatores de emissão específicos para cada atividade que contribui para a pegada de carbono, sendo eles:

`quilometrosPorDia:` fator de 0.2, é a média estimada das emissões de carbono associadas a veículos motorizados ao longo de um ano.

`horasDeEletronicos,` fator de 0.1, é a pegada de carbono relacionada ao consumo elétrico desses dispositivos.

`refeicoesComCarne,` fator de 0.5, é utilizado para representar as emissões associadas à produção de carne.

A pegada de carbono do usuário é calculada a partir de três fatores: transporte (quilômetros diários × 365 × 0.2), eletrônicos (horas diárias × 0.1) e consumo de carne (refeições com carne por dia × 0.5). A soma desses valores fornece a pegada de carbono total, abrangendo diversas fontes de emissões.

## **Entrada**

Como entrada será recebido o `nome`(string), `quilometrosPorDia`(double), `horasDeEletronicos`(int) e `refeicoesComCarne`(int).

## **Saída**

Exiba a pegada de carbono calculada com base nas informações fornecidas pelo usuário.

## **Exemplos**

A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.

| Entrada | Saída |
| --- | --- |
| Joao 212 | Joao, sua pegada de carbono e de 147.1 toneladas de CO2 por ano. |
| Ana 6190 | Ana, sua pegada de carbono e de 439.9 toneladas de CO2 por ano. |
| Pedro 10183 | Pedro, sua pegada de carbono e de 733.3 toneladas de CO2 por ano. |

**Curiosidades do desafio:**

A pegada de carbono é uma medida da quantidade de dióxido de carbono (CO2) e outros gases de efeito estufa liberados na atmosfera devido às atividades diárias.
