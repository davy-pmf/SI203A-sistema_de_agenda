### Sistema de Agenda (CLI) - Tema: Corinthians 🦅

Um sistema de gerenciamento de contatos via terminal desenvolvido na linguagem C, focado na manipulação segura e persistência de dados locais. 

Este projeto foi desenvolvido em um grupo de 3 pessoas para a disciplina de **Algoritmos e Programação de Computadores II** na Unicamp. O objetivo principal da disciplina era o domínio de operações de I/O e manipulação de arquivos. O tema "Agenda" (com a brincadeira do elenco do Corinthians) foi definido por sorteio.

### Minhas Contribuições (Destaques)
* **Arquitetura de Dados:** Desenvolvi o módulo de atualização de registros. 
* **Segurança (Staging):** Arquitetou-se uma solução de transação manual utilizando arquivos temporários para garantir a integridade total dos dados durante a reescrita, evitando corrupção em caso de falhas.
* **Versionamento Colaborativo:** Atuei ativamente no fluxo do projeto utilizando o Git, com branches isoladas por funcionalidade e integração segura via Pull Requests.

### 💻 Tecnologias Utilizadas
* **Linguagem:** C
* **Conceitos:** Manipulação de Arquivos (File I/O), Estruturas de Dados, CLI.
* **Versionamento:** Git e GitHub.

### 🔧 Como Executar
Para compilar e rodar o projeto localmente, utilize um compilador C (como o GCC) no terminal:

```bash
# Compilando os arquivos
gcc main.c agenda.c -o agenda

# Executando o sistema
./agenda
