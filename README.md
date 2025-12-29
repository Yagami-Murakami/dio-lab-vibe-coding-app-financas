# 🟣 CyberFlow AI - O Futuro das Finanças Pessoais

![Cover Project](https://img.shields.io/badge/Status-Concluído-success)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![AI Powered](https://img.shields.io/badge/AI-Powered-purple?style=for-the-badge)

> Uma experiência financeira gamificada e inteligente, construída com React, Tailwind e "Vibe Coding".

---

## 📺 Demonstração em Ação

Veja o **CyberFlow AI** transformando frases naturais em controle financeiro, com animações fluidas e uma interface Cyberpunk imersiva:

![GIF de Demonstração do CyberFlow](https://github.com/user-attachments/assets/da0ab47d-3354-41ac-ae7b-1f5bc11cdc3e)
*(O sistema reconhecendo valores, categorizando transações e a navegação entre metas e carteira)*

---

## 🚀 Sobre o Projeto

O **CyberFlow AI** não é apenas mais uma planilha de gastos. É um assistente financeiro pessoal que utiliza lógica de interpretação de texto (NLP simulado via Regex avançado) para transformar frases do dia a dia em transações financeiras estruturadas.

Desenvolvido durante o **Desafio Vibe Coding da DIO**, o projeto foca em uma UX futurista (Cyberpunk/Neon) e numa experiência "mobile-first" fluida, provando como a IA pode acelerar o desenvolvimento de interfaces complexas e regras de negócio robustas.

## ✨ Principais Funcionalidades

* **🤖 AI Parser V3.0:** Digite *"Comprei um Nintendo 2 por 18000"* e o sistema entende que o valor é **R$ 18.000,00** (ignorando números que fazem parte do nome do produto).
* **🧠 Categorização Inteligente:** Reconhece automaticamente se a transação é uma **Entrada** (ex: "Recebi", "Lucro", "Caiu") ou **Saída** (ex: "Gastei", "Ifood", "Uber").
* **🎯 Metas Gamificadas:** Crie objetivos financeiros com ícones/emojis personalizados e acompanhe barras de progresso visuais dinâmicas.
* **💼 Carteira Editável:** Ajuste manualmente o saldo de seus bancos virtuais e investimentos para refletir sua realidade financeira.
* **💾 Persistência Local:** Todos os dados ficam salvos no seu navegador (LocalStorage), garantindo privacidade e acesso rápido.
* **🧘 Vibe Score:** Um indicador de saúde financeira que muda de cor conforme seus hábitos de consumo recentes.

---

## 🛠️ Tecnologias Utilizadas

* **React.js** (Hooks, Context API/State Management)
* **TailwindCSS** (Estilização Neon, Glassmorphism e Responsividade)
* **Framer Motion** (Animações de entrada e transições fluidas)
* **Lucide React** (Ícones modernos)
* **Regex Avançado & Lógica Heurística** (O "cérebro" do parser de linguagem natural)

---

## 💡 O Processo de Criação (Vibe Coding & Prompt Engineering)

Este projeto foi evoluído através de rápidas iterações utilizando IA Generativa como "copiloto". O foco foi utilizar *Prompt Engineering* preciso para gerar componentes visuais prontos e lógicas complexas de JavaScript.

### 📝 O Prompt Final (PRD)

Abaixo, o prompt consolidado (Product Requirements Document) que guiou a IA na estruturação final do projeto:

```text
Atue como um Engenheiro de Software Sênior especialista em React e UX.
Crie um aplicativo de Finanças Pessoais "CyberFlow" com as seguintes regras:

1. ESTÉTICA: Tema Dark Cyberpunk (Zinco, Roxo Neon #a855f7, Verde Matrix). Fonte Orbitron para títulos.
2. INTEGRAÇÃO DE IA: Crie uma função 'aiParser' robusta que:
   - Identifique valores monetários em frases complexas (ex: "Nintendo 2 por 18000" -> Valor: 18000).
   - Use heurística para diferenciar Receitas de Despesas baseada em palavras-chave (ex: "Lucro", "Recebi" = Income).
3. FUNCIONALIDADES:
   - Dashboard com Saldo, Gráficos e "Vibe Score".
   - Aba de Metas: Modal para adicionar metas com escolha de Emojis e barra de progresso.
   - Aba Carteira: Cartão de crédito virtual e campos editáveis para saldo bancário e investimentos.
4. TÉCNICA:
   - Use Framer Motion para animações de entrada.
   - Persistência automática em LocalStorage.
   - Layout responsivo com navegação mobile na parte inferior.


## 📚 Reflexão e Aprendizados

Participar deste desafio no Lab da DIO solidificou o conceito de "Vibe Coding":

- **Comunicação Assertiva com IA:** Aprendi que definir a "vibe" estética (cores, fontes, estilo) no início do prompt economiza horas de CSS manual.
- **Lógica Complexa via Prompt:** Desenvolver o parser de texto exigiu iterar sobre casos de erro (ex: números no nome do produto confundindo o valor), o que aprimorou minha capacidade de descrever regras de negócio para a IA.
- **Integração de Bibliotecas:** A IA foi excelente em unir o React com Tailwind e Framer Motion, criando uma base de código limpa que eu pude refinar.

---

### 🔗 Links Úteis

- [🤖 Conversa Original com a IA (Gemini)](https://gemini.google.com/share/42bcf6a380ba)
- [💻 Código Fonte no GitHub](LINK_DO_SEU_REPOSITORIO_AQUI)

---

<p align="center">
  Feito com 💜 e muita Vibe Cyberpunk por <strong>Antonio Jonas (Tuninho)</strong> no Lab da DIO.
</p>
