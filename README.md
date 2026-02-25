# Projeto Dados de Atletas

Aplicação desenvolvida em **JavaScript** utilizando **Programação Orientada a Objetos (POO)** para calcular informações e parâmetros de atletas.

---

## Sobre o Projeto

Este projeto simula o sistema de avaliação de atletas em uma competição, permitindo:

- Cadastro de informações do atleta
- Cálculo da categoria por idade
- Cálculo do IMC
- Cálculo da média válida das notas
- Exibição organizada das informações no console

---

## Conceitos Aplicados

- Classes e Métodos
- Encapsulamento
- Manipulação de Arrays
- Estruturas Condicionais
- Cálculo Matemático
- Organização de Código em JavaScript

---

## Regras de Negócio

### Categoria por idade

| Idade | Categoria |
|-------|-----------|
| 9 a 11 anos | Infantil |
| 12 e 13 anos | Juvenil |
| 14 e 15 anos | Intermediário |
| 16 a 30 anos | Adulto |
| Outras idades | Sem categoria |

---

### Cálculo do IMC

Fórmula utilizada:

```
IMC = peso / (altura x altura)
```

---

### 📊 Cálculo da Média Válida

- O atleta recebe 5 notas.
- A maior e a menor nota são descartadas.
- A média é calculada com as 3 notas restantes.

---

## Tecnologias Utilizadas

- JavaScript
- Node.js (execução via terminal)

---

## Estrutura do Projeto

```
dados-atletas/
│
├── dados-atletas.js
└── README.md
```

---

## Como Executar o Projeto

### Clone o repositório

```bash
git clone https://github.com/seuusuario/dados-atletas.git
```

### Acesse a pasta do projeto

```bash
cd dados-atletas
```

### Execute o arquivo

```bash
node dados-atletas.js
```

---

## Exemplo de Saída

```
Nome: Cesar Abascal
Idade: 30
Peso: 80
Altura: 1.7
Notas: 10,9.34,8.42,10,7.88
Categoria: Adulto
IMC: 27.68166089965398
Média válida: 9.253333333333334
```

---

## Objetivo

Este projeto foi desenvolvido como parte de um desafio prático para consolidar conhecimentos em:

- Programação Orientada a Objetos
- Lógica de programação
- Manipulação de dados
- Boas práticas em JavaScript

---

## Autor
Weslley Felipe

---

## Observação

Projeto desenvolvido para fins educacionais e prática de desenvolvimento em JavaScript.
