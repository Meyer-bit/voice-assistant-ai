# 🎙 Assistente de Voz com IA (Whisper + ChatGPT + TTS)

## 📌 Visão Geral

Este projeto consiste em um **assistente de voz inteligente** desenvolvido em **Python**, com foco educacional e como **projeto prático para estágio em TI / IA**.

O assistente é capaz de:

- 🎤 Capturar áudio do usuário via navegador  
- 📝 Transcrever fala para texto utilizando **Whisper**  
- 🤖 Processar respostas com **ChatGPT (OpenAI)**  
- 🔊 Converter texto em áudio com **gTTS**  
- 🗣 Executar comandos de voz  
- 🧠 Utilizar personalidade configurável via prompt de sistema  

O projeto foi desenvolvido e executado no **Google Colab**.

---

## 🧠 Funcionalidades

- Gravação de áudio diretamente pelo navegador  
- Transcrição automática de voz para texto  
- Conversação em linguagem natural com IA  
- Resposta falada (Text-to-Speech)  
- Personalidade definida do assistente  
- Comandos de voz embutidos  

---

## 🗣 Comandos de Voz

O assistente reconhece comandos especiais falados pelo usuário:

- **`limpar conversa`**  
  Limpa todo o histórico da conversa

- **`encerrar assistente`**  
  Finaliza a execução do assistente

Os comandos são identificados antes da chamada ao modelo de IA.

---

## 🧰 Tecnologias Utilizadas

- **Python**  
- **Google Colab**  
- **OpenAI API (ChatGPT)**  
- **Whisper (Speech-to-Text)**  
- **gTTS (Text-to-Speech)**  
- **JavaScript (MediaRecorder API)**  

---

## 🏗 Estrutura do Projeto

```
voice_assistant_ia/
│
├── voice_assistant.ipynb
├── README.md
├── .gitignore

```

## 🔐 Segurança da API Key

A **API Key da OpenAI não é armazenada diretamente no código**.

Ela é solicitada em tempo de execução por meio de **variáveis de ambiente**, o que garante:

- A chave não fique exposta no repositório
- Segurança ao compartilhar o projeto no GitHub
- Conformidade com boas práticas de desenvolvimento

---

## ▶️ Como Executar o Projeto

1. Abra o arquivo `voice_assistant.ipynb` no **Google Colab**  
2. Execute as células do notebook na ordem apresentada  
3. Quando solicitado, insira sua **OpenAI API Key**  
4. Autorize o acesso ao microfone no navegador  
5. Aguarde a gravação do áudio  
6. Fale com o assistente utilizando sua voz 🎤  
7. Ouça a resposta gerada automaticamente pelo assistente 🔊  

