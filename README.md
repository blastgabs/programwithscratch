# Programando com Scratch
Trabalho da Disciplina Programação de Computadores - Professora Kadidja

Gabriela Sidrin de Souza, 3° período

# Introdução

Scratch é uma linguagem de programação visual, criada pelo MIT, que permite criar histórias interativas, jogos e animações de forma fácil e intuitiva, especialmente para crianças e iniciantes, através de blocos de código que são arrastados e soltos. 

Neste trabalho analisaremos as ideias apresentadas nas referêcias citadas, buscando compreender a influência da programação no dia a dia e sua presença em diferentes campos. 

Para isso, usaremos um programa trabalhado anteriormente em sala de aula como base. Demonstrando de forma simples noções fundamentais, como exemplo de variáveis, funções e cálculos, que se encaixam na criação de soluções úteis.

Agora, vamos refazer o seguinte programa já trabalhado em sala usando Scratch:

```
salbruto=(float(input("Informe o valor do salário bruto: ")))
valorhoraextra=(float(input("Informe o valor da hora extra: ")))
horastrabalhadas=(float(input("Informe a quantidade de horas trabalhadas: ")))
ganhoextra=valorhoraextra*horastrabalhadas
salfinal=salbruto+ganhoextra
print(f"O salário final é: {salfinal:.2f}")
```

# Instruções

Abra o site https://scratch.mit.edu/ (https://scratch.mit.edu/projects/1146678346/)

Abra um documento em branco na opção create

1. Criação das Variáveis

Crie as variáveis Salário Bruto, Valor Hora Extra, Horas Trabalhadas, Ganho Extra e Salário Final e as jogue na parte em branco.

2. Interação com o Usuário e Entrada de dados

Use a opção de criar blocos de perguntar e esperar para coletar as entradas do usuário, como o salário bruto, valor da hora extra e o número de horas extras trabalhadas

```
perguntar [Qual é o seu salário bruto?] e esperar
definir [Salário Bruto v] para (resposta)

perguntar [Qual é o valor da hora extra?] e esperar
definir [Valor Hora Extra v] para (resposta)

perguntar [Quantas horas extras você trabalhou?] e esperar
definir [Horas Trabalhadas v] para (resposta)
```

3. Processamento de dados

Use blocos matemáticos para fazer os cálculos do ganho extra e do salário final 

```
definir [Ganho Extra v] para ((Valor Hora Extra) * (Horas Trabalhadas))

definir [Salário Final v] para ((Salário Bruto) + (Ganho Extra))
```

4. Output (Exibição do Resultado)

Printe o salário final com o valor das horas extras adicionadas

```
dizer (junte [O salário final é: ] (Salário Final)) por 2 segundos
```

https://scratch.mit.edu/projects/1146514902

# Referências

- PAUL, Barry; GRIFFTHS, David. Use a cabeça! Programação. 1. ed. Rio de Janeiro: Atla Books Editora, 2010.
- CS50: Introduction to Computer Science | Harvard University
- Programação Orientada a Objetos | Fundação Bradesco

