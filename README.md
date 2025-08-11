# HermesXZ 🏛️🚀

> Your open-source desktop tool to automatically transcribe and translate videos with the power of the Google Gemini API.

<p align="center">
  <img src="https://img.shields.io/badge/python-3.9+-blue.svg" alt="Python Version">
  <a href="https://github.com/your-username/hermesxz/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT">
  </a>
  <a href="https://github.com/your-username/hermesxz/issues">
    <img src="https://img.shields.io/github/issues/your-username/hermesxz" alt="Issues">
  </a>
  <img src="https://img.shields.io/badge/status-in--development-orange" alt="Status">
</p>

---

## Languages

[English 🇺🇸](#english) | [Português (Brasil) 🇧🇷](#portugues-brasil)

---

## English

### 📋 Table of Contents
- [HermesXZ 🏛️🚀](#hermesxz-️)
  - [Languages](#languages)
  - [English](#english)
    - [📋 Table of Contents](#-table-of-contents)
    - [About the Project](#about-the-project)
    - [Key Features](#key-features)
    - [For End-Users](#for-end-users)
    - [Roadmap](#roadmap)
    - [Getting Started (for Developers)](#getting-started-for-developers)
    - [Usage](#usage)
    - [Contributing](#contributing)
    - [License](#license)
---

### About the Project
HermesXZ is an open-source desktop application designed to automate the process of transcribing and translating videos. Leveraging the power of the Google Gemini API, the tool aims to provide accurate and flexible subtitles, which can either be embedded directly into the video (hardsubs) or generated as separate `.srt` files.

### Key Features
✅ **Versatile Input**: Process single video files or entire directories.
✅ **Audio Extraction**: Automatically separates the audio track for analysis.
✅ **Smart Language Detection**: Identifies the original audio language using the Gemini API.
✅ **High-Quality Transcription and Translation**: Converts speech to text and translates it into your chosen language.
✅ **Dual Output Options**:
  - **Embedded Subtitles (Hardsub)**: Creates a new video file with the subtitles burned in and a language suffix (e.g., `video_en.mp4`).
  - **SRT File**: Generates a separate `.srt` subtitle file (IT WILL NOT EMBED THE SUBTITLES, ONLY CREATE A FILE).

### For End-Users
This section is for those who just want to use the program.

**1. Installation**
- Go to the **Releases** section on the project's GitHub page.
- Download the file for your operating system (`HermesXZ.exe` for Windows, `HermesXZ.dmg` for macOS, etc.).
- Run the file. No further installation is needed!

**2. First Use**
- The first time you open HermesXZ, it will ask for your Google Gemini API key.
- Simply paste the key into the provided field to get started. The program will offer to save the key securely so you don't have to enter it again.

### Roadmap
The project is being developed in phases:
- **Phase 1: Back-end MVP (✅ Completed)**
  - Main command-line script with all processing functionalities.
- **Phase 2: GUI Development (⏳ In Progress)**
  - Development of a modern and intuitive user interface using web technologies (**Tauri**).
- **Phase 3: Integration and Packaging**
  - Full integration of the front-end and back-end, followed by end-to-end testing.
  - Creation of distributable executables for Windows, macOS, and Linux.
- **Phase 4: Post-Launch**
  - Gathering community feedback, fixing bugs, and implementing new features.

### Getting Started (for Developers)
Follow the steps below to set up the project locally.

**1. Prerequisites**
- Python 3.9+
- Git

**2. Clone the Repository**
```bash
git clone https://github.com/your-username/hermesxz.git
cd hermesxz
```

**3. Create a Virtual Environment and Install Dependencies**
```bash
# Create the environment
python -m venv venv

# Activate it
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

# Install the required packages
pip install -r requirements.txt
```

**4. Configure Your API Key**
The script requires a Google Gemini API key.
- You can get a key from the Google AI Studio.
- The script will prompt you to enter the key on the first run and will offer to save it securely for future use. Alternatively, you can set it as an environment variable named `GEMINI_API_KEY`.

### Usage
Currently, the script is operated via the command line.

**To process a single video file:**
```bash
python main.py --video "path/to/your/video.mp4" --lang "English"
```

**To process all videos in a directory:**
```bash
python main.py --dir "path/to/your/folder" --lang "Portuguese"
```

### Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

Feel free to fork the repository, create a *feature branch*, and submit a *pull request*. You can also open an *issue* with the "enhancement" tag.

### License
Distributed under the MIT License. See the `LICENSE` file for more information.

---
## Portugues (Brasil)

### 📋 Índice
- [HermesXZ 🏛️🚀](#hermesxz-️)
  - [Idiomas / Languages](#idiomas--languages)
  - [Portugues (Brasil)](#portugues-brasil)
    - [📋 Índice](#-índice)
    - [Sobre o Projeto](#sobre-o-projeto)
    - [Principais Funcionalidades](#principais-funcionalidades)
    - [Para Usuários Finais](#para-usuários-finais)
    - [Roteiro (Roadmap)](#roteiro-roadmap)
    - [Como Começar (para Desenvolvedores)](#como-começar-para-desenvolvedores)
    - [Como Usar](#como-usar)
    - [Como Contribuir](#como-contribuir)
    - [Licença](#licença)
---

### Sobre o Projeto
HermesXZ é uma aplicação de desktop open-source projetada para automatizar o processo de transcrição e tradução de vídeos. Utilizando o poder da API do Google Gemini, a ferramenta visa fornecer legendas precisas e flexíveis, que podem ser embutidas diretamente no vídeo (hardsubs) ou geradas como arquivos `.srt` separados.

### Principais Funcionalidades
✅ **Entrada Versátil**: Processe arquivos de vídeo individuais ou diretórios completos.
✅ **Extração de Áudio**: Separa automaticamente a faixa de áudio para análise.
✅ **Detecção Inteligente de Idioma**: Identifica o idioma original do áudio usando a API Gemini.
✅ **Transcrição e Tradução de Alta Qualidade**: Converte a fala em texto e o traduz para o idioma de sua escolha.
✅ **Duas Opções de Saída**:
  - **Legendas Embutidas (Hardsub)**: Cria um novo arquivo de vídeo com as legendas gravadas e um sufixo de idioma (ex: `video_en.mp4`).
  - **Arquivo SRT**: Gera um arquivo de legenda `.srt` separado(NÃO IRA IMBUTIR A LEGENDA, APENAS CRIAR UM ARQUIVO).


### Para Usuários Finais
Esta seção é para quem deseja apenas usar o programa.

**1. Instalação**
- Vá para a seção **Releases** na página do GitHub do projeto.
- Baixe o arquivo para o seu sistema operacional (`HermesXZ.exe` para Windows, `HermesXZ.dmg` para macOS, etc.).
- Execute o arquivo. Não é necessário instalar mais nada!

**2. Primeiro Uso**
- Na primeira vez que você abrir o HermesXZ, ele solicitará sua chave da API do Google Gemini.
- Basta colar a chave no campo indicado para começar a usar. O programa oferecerá a opção de salvar a chave de forma segura para que você não precise digitá-la novamente.

### Roteiro (Roadmap)
O projeto está sendo desenvolvido em fases:
- **Fase 1: MVP do Back-end (✅ Concluída)**
  - Script principal de linha de comando com todas as funcionalidades de processamento.
- **Fase 2: Desenvolvimento da GUI (⏳ Em Andamento)**
  - Desenvolvimento de uma interface de usuário moderna e intuitiva com tecnologias web (**Tauri**).
- **Fase 3: Integração e Empacotamento**
  - Integração completa do front-end e back-end, seguida de testes ponta a ponta.
  - Criação de executáveis distribuíveis para Windows, macOS e Linux.
- **Fase 4: Pós-Lançamento**
  - Coleta de feedback da comunidade, correção de bugs e implementação de novas funcionalidades.

### Como Começar (para Desenvolvedores)
Siga os passos abaixo para configurar o projeto localmente.

**1. Pré-requisitos**
- Python 3.9+
- Git

**2. Clone o Repositório**
```bash
git clone https://github.com/your-username/hermesxz.git
cd hermesxz
```

**3. Crie um Ambiente Virtual e Instale as Dependências**
```bash
# Crie o ambiente
python -m venv venv

# Ative-o
# No Windows:
venv\Scripts\activate
# No macOS/Linux:
source venv/bin/activate

# Instale os pacotes necessários
pip install -r requirements.txt
```

**4. Configure sua Chave de API**
O script requer uma chave de API do Google Gemini.
- Você pode obter uma chave no Google AI Studio.
- O script solicitará que você insira a chave na primeira execução e oferecerá a opção de salvá-la de forma segura para usos futuros. Alternativamente, você pode configurá-la como uma variável de ambiente chamada `GEMINI_API_KEY`.

### Como Usar
Atualmente, o script é operado via linha de comando.

**Para processar um único arquivo de vídeo:**
```bash
python main.py --video "caminho/para/seu/video.mp4" --lang "Inglês"
```

**Para processar todos os vídeos em um diretório:**
```
python main.py --dir "caminho/para/sua/pasta" --lang "Português"
```

### Como Contribuir
Contribuições são o que tornam a comunidade de código aberto um lugar incrível para aprender, inspirar e criar. Qualquer contribuição que você fizer será **muito bem-vinda**.

Sinta-se à vontade para fazer um fork do repositório, criar uma *feature branch* e enviar um *pull request*. Você também pode abrir uma *issue* com a tag "enhancement".

### Licença
Distribuído sob a Licença MIT. Veja o arquivo `LICENSE` para mais informações.