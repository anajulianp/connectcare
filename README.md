# ConnectCare 🤝

Projeto acadêmico desenvolvido para a disciplina de Engenharia de Prompt e Aplicações em IA (Unicid).

🔗 **Acesse o projeto:** https://connectcaredonate.lovable.app/

📄 [Documentação completa](./documetacao.pdf)
📊 [Apresentação](./apresentacao.pdf)

### 📚 O que aprendi

- Como consumir e integrar APIs externas (BrasilAPI, Gmail)
- Como estruturar prompts para orientar o comportamento de uma IA (papel, regras, formato de saída)
- Como usar IA generativa (Gemini) dentro de um fluxo automatizado, incluindo lidar com limitações como alucinações
- Como conectar diferentes ferramentas (Lovable, Make, Google Sheets) para criar um sistema funcional de ponta a ponta

---

### 📌 Problema

Muitas pessoas desejam doar itens (roupas, alimentos, calçados), mas desistem por não saberem quais instituições próximas aceitam aquele material específico. A falta de informações centralizadas gera um distanciamento entre quem quer ajudar e quem precisa de suprimentos.

### 🎯 Objetivo

Conectar doadores e ONGs de forma simples e eficiente, permitindo localizar rapidamente pontos de coleta por meio de filtros de segmento e proximidade.

### 🛠️ Ferramentas utilizadas

![Lovable](https://img.shields.io/badge/-Lovable-FF5A00?style=flat-square)
![Make](https://img.shields.io/badge/-Make-6D00CC?style=flat-square)
![Gemini](https://img.shields.io/badge/-Gemini%20API-8E75B2?style=flat-square)
![Google Sheets](https://img.shields.io/badge/-Google%20Sheets-34A853?style=flat-square&logo=google-sheets&logoColor=white)
![Gmail API](https://img.shields.io/badge/-Gmail%20API-D14836?style=flat-square&logo=gmail&logoColor=white)

- **Lovable** — criação da interface (vibe coding assistido por IA)
- **Make** — automação e orquestração dos dados entre as ferramentas
- **Gemini API** — validação cadastral das ONGs e geração de respostas personalizadas
- **BrasilAPI** — consulta e validação de CNPJ
- **Google Sheets** — banco de dados do projeto
- **API do Gmail** — envio automático de e-mails de confirmação

### ⚙️ Como funciona

O ConnectCare integra front-end e back-end para interpretar a intenção do doador, processar os dados e recomendar ONGs próximas que aceitam o item desejado. As próprias ONGs também podem se cadastrar na plataforma através de um formulário, passando por uma validação automática via IA e consulta de CNPJ.

### 👥 Equipe

Projeto desenvolvido em grupo (Tokens):
Ana Júlia Nicolino Pignataro, Douglas dos Santos Zamboni, Gabriela Gonçalves de Melo, Gustavo Batista Silva do Canto, João Vitor Silva Alves Araújo, Julia Otsubo de Jesus, Lucas Fortes de Melo, Karine dos Santos Nogueira e Pedro H.S. Turubia.

### 🚀 Melhorias futuras

- Sistema de avaliação das ONGs pelos doadores
- Filtros de urgência para situações de crise
- Atualização de dados feita diretamente pelas próprias instituições
