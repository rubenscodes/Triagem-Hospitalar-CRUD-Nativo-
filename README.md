#  Sistema de Triagem Hospitalar

### Sistema Desktop para Gerenciamento e Triagem de Pacientes

![Java](https://img.shields.io/badge/Java-8%2B-orange?logo=openjdk)
![Interface](https://img.shields.io/badge/Interface-Java%20Swing-blue)
![Persistência](https://img.shields.io/badge/Database-CSV-green)
![Status](https://img.shields.io/badge/Status-Desenvolvido-success)
![Projeto](https://img.shields.io/badge/Projeto-Acadêmico-purple)

---

##  Sobre o projeto

O **Sistema de Triagem Hospitalar** é uma aplicação desktop desenvolvida em Java, com o objetivo de auxiliar no gerenciamento e na organização do fluxo de pacientes em um ambiente hospitalar.

A aplicação permite realizar operações de cadastro, consulta, atualização e remoção de pacientes por meio de uma interface gráfica interativa, utilizando caixas de diálogo para facilitar a interação com o usuário.

O sistema também conta com um mecanismo de persistência de dados em arquivos CSV, permitindo armazenar e recuperar as informações cadastradas sem a necessidade de um banco de dados externo.

O projeto foi desenvolvido como parte das atividades acadêmicas do curso de **Análise e Desenvolvimento de Sistemas (ADS)**, com foco na aplicação prática dos conceitos de programação orientada a objetos, manipulação de arquivos e operações CRUD.

##  Funcionalidades

O sistema possui um fluxo completo de gerenciamento de pacientes baseado nas quatro operações fundamentais do CRUD:

| Operação | Funcionalidade | Descrição |
|---|---|---|
| Create | Cadastrar paciente | Registra nome, CPF, idade, sintomas e prioridade. |
| Read | Visualizar triagem | Apresenta os pacientes cadastrados na fila. |
| Update | Atualizar dados | Permite localizar um paciente pelo CPF e editar suas informações. |
| Delete | Remover paciente | Remove o registro após atendimento ou alta. |

### 📋 Informações dos pacientes

Cada cadastro contém:

- Nome completo;
- CPF;
- Idade;
- Sintomas apresentados;
- Nível de prioridade de atendimento (1 a 5).

###  Classificação de prioridade

O sistema permite definir níveis de prioridade de 1 a 5 para organizar os registros da triagem.

## 🛠️ Tecnologias e ferramentas utilizadas

| Tecnologia | Aplicação |
|---|---|
| Java 8+ | Linguagem principal de desenvolvimento. |
| Java Swing | Construção da interface gráfica. |
| JOptionPane | Caixas de diálogo para interação com o usuário. |
| CSV | Formato utilizado para persistência dos dados. |
| BufferedReader | Leitura dos registros armazenados. |
| BufferedWriter | Escrita e atualização dos registros. |
| Git | Controle de versão do projeto. |
| GitHub | Hospedagem e gerenciamento do código-fonte. |

##  Arquitetura e funcionamento

A aplicação utiliza uma estrutura simples e nativa do Java, sem dependências externas.

A persistência dos dados é realizada por meio de arquivos CSV, permitindo que os registros permaneçam armazenados localmente mesmo após o encerramento da aplicação.

A interface gráfica utiliza `javax.swing.JOptionPane`, proporcionando uma navegação por menus e caixas de diálogo.

### Fluxo de funcionamento

1. O usuário inicia a aplicação.
2. O sistema apresenta um menu de operações.
3. O usuário seleciona a funcionalidade desejada.
4. Os dados são processados e armazenados no arquivo CSV.
5. As informações podem ser consultadas, atualizadas ou removidas.

##  Como executar o projeto

### Pré-requisitos

- Java JDK 8 ou superior;
- IDE de desenvolvimento Java, como Eclipse, IntelliJ IDEA ou VS Code.

### Instalação

**1. Clone o repositório:**

```bash
git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
```

**2. Acesse a pasta do projeto:**

```bash
cd SEU_REPOSITORIO
```

**3. Abra o projeto na sua IDE Java.**

**4. Execute a classe principal (`Main`).**

> Observação: substitua o nome da classe principal conforme a estrutura real do projeto.

## 📚 Conhecimentos aplicados

Durante o desenvolvimento, foram trabalhados conceitos importantes da programação:

- Operações CRUD;
- Programação em Java;
- Interface gráfica com Java Swing;
- Manipulação de arquivos;
- Leitura e escrita de dados;
- Organização e persistência de informações;
- Estruturas condicionais e de repetição;
- Tratamento e validação de dados.

## 🎓 Contexto acadêmico

Projeto desenvolvido no curso de **Análise e Desenvolvimento de Sistemas (ADS)**, com finalidade educacional e aplicação prática dos conhecimentos adquiridos durante a graduação.

A proposta foi desenvolver uma solução funcional utilizando recursos nativos da linguagem Java, explorando conceitos fundamentais da construção de aplicações desktop.

##  Autor

**Rubens Correa da Silva**

Estudante de Análise e Desenvolvimento de Sistemas (ADS).

Interesse em desenvolvimento de software, programação Java, banco de dados e engenharia de software.

---

 Se este projeto despertou seu interesse, fique à vontade para explorar o código-fonte e acompanhar sua evolução.

*Desenvolvido para fins acadêmicos e de aprendizado em desenvolvimento de software.*
