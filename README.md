# Teste Prático - Iniflex

## Descrição do Projeto

Este projeto é um teste prático de programação em Java, solicitado pela empresa Iniflex, para avaliar habilidades de desenvolvimento. O objetivo é criar um sistema que gerencie uma lista de funcionários de uma indústria, implementando diversas funcionalidades relacionadas ao gerenciamento de dados dos funcionários.

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

- Utilização da linguagem Java.
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

## Considerações Finais

- Se não souber como resolver algum requisito, comente no código explicando a dificuldade e passe para o próximo item.
- Após finalizar o desenvolvimento, exporte o projeto e envie o link conforme solicitado.

Boa sorte e esperamos que você demonstre todo o seu conhecimento e criatividade neste teste.

## Contato

Em caso de dúvidas, entre em contato com o time técnico da Iniflex.

---

**Nota**: Certifique-se de que seu código está bem documentado e organizado, facilitando a compreensão e a avaliação do seu projeto pela equipe técnica.
