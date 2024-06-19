# Teste Prático

## Descrição do Projeto

Este projeto é um teste prático de programação em Java, solicitado como teste técnico de uma empresa, para avaliar habilidades de desenvolvimento. O objetivo é criar um sistema que gerencie uma lista de funcionários de uma indústria, implementando diversas funcionalidades relacionadas ao gerenciamento de dados dos funcionários.

## Estrutura do Projeto

O projeto consiste nas seguintes classes:

1. **Pessoa**: Classe base com os atributos `nome` (String) e `dataNascimento` (LocalDate).
2. **Funcionario**: Classe que estende a classe Pessoa, com os atributos adicionais `salario` (BigDecimal) e `funcao` (String).
3. **Principal**: Classe principal para execução das ações solicitadas.

## Funcionalidades

A classe Principal deve executar as seguintes ações:

1. **Inserir funcionários**: Inserir todos os funcionários na mesma ordem e com as mesmas informações fornecidas.
2. **Remover funcionário**: Remover o funcionário “João” da lista.
3. **Imprimir todos os funcionários**: Exibir todas as informações dos funcionários com:
    - Data no formato `dd/MM/yyyy`.
    - Valores numéricos formatados com separador de milhar como ponto e decimal como vírgula.
4. **Atualizar salário**: Aumentar o salário de todos os funcionários em 10%.
5. **Agrupar por função**: Agrupar os funcionários por função em um mapa (`Map`), onde a chave é a função e o valor é a lista de funcionários.
6. **Imprimir agrupados por função**: Exibir os funcionários agrupados por função.
7. **Aniversariantes dos meses 10 e 12**: Imprimir os funcionários que fazem aniversário nos meses de outubro e dezembro.
8. **Funcionário mais velho**: Imprimir o funcionário com a maior idade, exibindo nome e idade.
9. **Ordem alfabética**: Imprimir a lista de funcionários em ordem alfabética.
10. **Total de salários**: Imprimir o total dos salários dos funcionários.
11. **Salários mínimos**: Imprimir quantos salários mínimos cada funcionário ganha, considerando que o salário mínimo é R$ 1212,00.

## Requisitos

- Utilização da linguagem Java orientado ao objeto.
- Uso de classes e herança.
- Manipulação de listas e mapas.
- Formatação de datas e números.
- Ordenação e filtragem de listas.

## Ferramentas Utilizadas

- Visual Studio Code.
- Java Development Kit (JDK).

## Instruções para Execução

1. Clone ou baixe o repositório do projeto.
2. Importe o projeto em sua IDE de preferência.
3. Compile e execute a classe `Principal`.

## Compilação no terminal

PS C:\Users\junio\OneDrive\Área de Trabalho\Projeto-Java> cd src
PS C:\Users\junio\OneDrive\Área de Trabalho\Projeto-Java\src> javac Principal.java
>> 
Note: Principal.java uses or overrides a deprecated API.
Note: Recompile with -Xlint:deprecation for details.
PS C:\Users\junio\OneDrive\Área de Trabalho\Projeto-Java\src> java Principal
Maria, 18/10/2000, 2.009,44, Operador
Caio, 02/05/1961, 9.836,14, Coordenador
Miguel, 14/10/1988, 19.119,88, Diretor
Alice, 05/01/1995, 2.234,68, Recepcionista
Heitor, 19/11/1999, 1.582,72, Operador
Arthur, 31/03/1993, 4.071,84, Contador
Laura, 08/07/1994, 3.017,45, Gerente
Heloísa, 24/05/2003, 1.606,85, Eletricista
Helena, 02/09/1996, 2.799,93, Gerente
Função: Operador
 - Maria
 - Heitor
Função: Eletricista
 - Heloísa
Função: Recepcionista
 - Alice
Função: Diretor
 - Miguel
Função: Gerente
 - Laura
 - Helena
Função: Coordenador
 - Caio
Função: Contador
 - Arthur
Funcionários que fazem aniversário em outubro e dezembro:
Maria
Miguel
Funcionário mais velho: Caio - Idade: 63 anos
Funcionários por ordem alfabética:
Alice
Arthur
Caio
Heitor
Helena
Heloísa
Laura
Maria
Miguel
Total dos salários: 50.906,82
Salários mínimos que cada funcionário ganha:
Maria: 1.82 salários mínimos
Caio: 8.93 salários mínimos
Miguel: 17.35 salários mínimos
Alice: 2.03 salários mínimos
Heitor: 1.44 salários mínimos
Arthur: 3.70 salários mínimos
Laura: 2.74 salários mínimos
Heloísa: 1.46 salários mínimos
Helena: 2.54 salários mínimos
PS C:\Users\junio\OneDrive\Área de Trabalho\Projeto-Java\src> 

## Contato

[![WhatsApp](https://img.shields.io/badge/WhatsApp-Chat%20Now-green?logo=whatsapp)](https://wa.me/5561992953065) (61) 99295-3065
---

**Nota**: Certifique-se de que seu código está bem documentado e organizado, facilitando a compreensão e a avaliação do seu projeto pela equipe técnica.
