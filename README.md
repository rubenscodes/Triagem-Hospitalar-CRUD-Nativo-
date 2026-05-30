# 🏥 Sistema de Triagem Hospitalar (CRUD Nativo)

Um sistema desktop para gerenciamento e triagem de fluxo de pacientes em hospitais. O projeto utiliza interface gráfica amigável em caixas de diálogo e persistência de dados local de forma nativa.

---

## 🚀 Funcionalidades

O sistema conta com um fluxo completo de **CRUD** através de um menu interativo:
- **Cadastrar Paciente (Create):** Captura nome, CPF, idade, sintomas e define o nível de prioridade (1 a 5), salvando diretamente no arquivo de texto.
- **Visualizar Triagem (Read):** Processa a base de dados local e formata um relatório em texto limpo com todos os pacientes ativos na fila.
- **Atualizar Dados (Update):** Filtra o paciente pelo CPF e permite a reedição dinâmica de qualquer dado inserido na triagem.
- **Remover/Alta (Delete):** Remove o registro do paciente da lista persistida assim que ele recebe atendimento médico ou alta.

---

## 🛠️ Tecnologias e Arquitetura

- **Linguagem:** Java 8+
- **Interface Gráfica:** `javax.swing.JOptionPane`
- **Persistência:** Manipulação nativa de arquivo delimitado por vírgula (`.csv`) via streams (`BufferedReader` / `BufferedWriter`).
- **Dependências:** Nenhuma. O projeto roda de forma 100% nativa sem necessidade de Maven, Gradle ou Jars externos.

---

## 💻 Como rodar o projeto

1. Baixe ou clone este repositório na sua máquina:
   ```bash
   git clone [https://github.com/SEU_USUARIO/MeuProjetoHostpital.git](https://github.com/SEU_USUARIO/MeuProjetoHostpital.git)
