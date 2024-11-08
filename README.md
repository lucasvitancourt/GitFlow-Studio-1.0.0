#  GitFlow-Studio-1.0.0 - Aplicativo para Facilitar o Uso do Git e Git Flow

Electron Git Flow é uma aplicação desktop desenvolvida para simplificar o uso dos comandos mais comuns do Git e Git Flow. Ele foi projetado com foco em desenvolvedores que desejam uma interface gráfica intuitiva para realizar operações de versionamento sem precisar recorrer diretamente ao terminal.

## 📘 Sobre o Projeto

Git e Git Flow são ferramentas essenciais para o controle de versão e gerenciamento de branches em projetos de software. No entanto, especialmente para quem está começando, alguns comandos podem ser complicados e exigem familiaridade com o terminal. O **GitFlow-Studio** fornece uma interface gráfica que permite:

- Executar comandos básicos do Git, como `git add`, `git commit`, `git push` e `git pull`, de forma prática e acessível.
- Gerenciar branches com Git Flow, possibilitando criar e finalizar branches de feature de maneira simples.

Este aplicativo é ideal para desenvolvedores que desejam economizar tempo e minimizar erros ao trabalhar com repositórios Git, ou para aqueles que estão iniciando e querem aprender Git Flow com uma abordagem mais amigável.

## 🎯 Funcionalidades Principais

### Git Commands

- **Inicializar Repositório** (`git init`): Crie um repositório Git dentro do diretório atual.
- **Adicionar Arquivos ao Staging** (`git add`, `git add .`): Inclua arquivos para o próximo commit.
- **Commitar Alterações** (`git commit`): Salve as mudanças com uma mensagem de commit.
- **Status do Repositório** (`git status`): Visualize o status atual do repositório.
- **Adicionar Remoto** (`git remote add`): Conecte-se a um repositório remoto.
- **Push e Pull** (`git push`, `git pull`): Envie e receba mudanças do repositório remoto.
- **Rebase** (`git rebase`): Altere a base da branch para facilitar a colaboração.

### Git Flow Commands

- **Inicializar Git Flow** (`git flow init`): Configure o fluxo Git Flow no repositório atual.
- **Feature Start e Finish** (`git flow feature start`, `git flow feature finish`): Crie e finalize branches de feature para novas funcionalidades, permitindo uma melhor organização do código.

## 📐 Design e Interface

O design do aplicativo é escuro, inspirado nas cores e estilo do GitHub, para proporcionar uma experiência de usuário agradável e moderna. A interface é organizada em abas que agrupam os comandos de acordo com sua função:

1. **Git** - Para operações comuns de Git.
2. **Git Flow** - Para gerenciar branches de feature e inicializar o fluxo Git Flow.
3. **Configurações** - Para ajustar preferências e informações do repositório.

## 🛠️ Tecnologia Utilizada

- **Electron** - Para construir a interface desktop.
- **JavaScript** - Lógica de execução dos comandos e manipulação do DOM.
- **Node.js** - Para integração com comandos Git via linha de comando.
- **CSS** - Design e estilização da interface.

## 🚀 Instalação

Para instalar e utilizar o aplicativo, siga os passos abaixo:

1. **Baixe o Executável**: O aplicativo está disponível em formato `.exe` para sistemas Windows.
2. **Execute o Aplicativo**: Dê um duplo clique no arquivo `.exe` para abrir o Electron Git Flow.
3. **Navegue pela Interface**: Use as abas para realizar os comandos de Git e Git Flow que desejar.

## 📈 Benefícios de Usar o Electron Git Flow

- **Simplificação do Processo de Controle de Versão**: A interface gráfica permite realizar tarefas comuns sem precisar lembrar a sintaxe exata de cada comando.
- **Ideal para Iniciantes e Desenvolvedores**: Quem está aprendendo Git Flow pode se familiarizar com o processo sem se preocupar com erros de terminal, enquanto desenvolvedores experientes podem economizar tempo.
- **Organização e Fluxo Padronizado**: Com o suporte ao Git Flow, é fácil gerenciar branches de desenvolvimento e manter o projeto organizado.

## ⚠️ Observações e Avisos

- **Compatibilidade**: O aplicativo está disponível em formato `.exe` para Windows. Em breve, outras versões podem ser disponibilizadas para macOS e Linux.
- **Requisitos**: Necessário ter Git instalado e configurado no sistema para que o Electron Git Flow funcione corretamente.
- **Limitações**: Este aplicativo é uma interface gráfica para comandos básicos; ele não substitui o terminal em operações avançadas ou complexas de Git.


**GitFlow-Studio** é uma ferramenta projetada para tornar o desenvolvimento mais produtivo e eficiente, removendo barreiras e simplificando a curva de aprendizado do Git e Git Flow. Aproveite e otimize seu fluxo de trabalho com essa solução prática e acessível!

