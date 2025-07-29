# 🚀 Desafio de Projeto: Programação Orientada a Objetos (POO)

- Este repositório contém a implementação de um desafio de Programação Orientada a Objetos proposto no Bootcamp da DIO (Digital Innovation One) do Bootcamp GFT Start #7 - Java.


## 🧠 Objetivo
Aplicar os principais pilares da POO em Java através da modelagem de um sistema de formação de desenvolvedores, com foco em conceitos como:

- Herança

- Abstração

- Encapsulamento

- Polimorfismo

## 🏗️ Entidades Modeladas
- Dev: representa o desenvolvedor participante.

- Bootcamp: representa um programa de formação com diversos conteúdos.

- Conteúdo (abstrato): superclasse para os tipos de conteúdo oferecidos no bootcamp.

  - Curso

  - Mentoria

## 📚 Tecnologias
- Java 21+

- Paradigma POO

## 📁 Estrutura do Projeto
- Organizado em pacotes separados para facilitar a leitura e a manutenção do código.


## ⚙️ Como Executar
### ✅ Pré-requisitos
- Java 21+

- Maven instalado e configurado na máquina

- IDE de sua preferência (IntelliJ, VS Code, Eclipse, etc.)


### 🚀 Passos para execução


1. Clone este repositório:

```bash
git clone https://github.com/fabianoqss/desafio-poo-dio.git
```

2. Acesse a pasta do projeto:

```bash
cd desafio-poo-dio
```

3. Compile o projeto com Maven:

```bash
mvn compile
```

4. Execute a aplicação (certifique-se de que a classe Main está com o método main() configurado corretamente):
```bash
mvn exec:java -Dexec.mainClass="br.com.seupacote.Main"
```