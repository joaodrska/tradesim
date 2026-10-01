# 📈 TradeSim

**Plataforma web educacional de simulação de investimentos para escolas e universidades.**

O TradeSim permite que estudantes aprendam a investir na prática, comprando e vendendo ativos com dinheiro fictício, usando dados reais do mercado brasileiro. Tudo isso sem correr nenhum risco.

> 🚧 Projeto em desenvolvimento ativo. O código-fonte é privado, mas posso apresentar o projeto e o código em uma entrevista.

---

## 🎯 O problema

Muitos jovens terminam a escola e a faculdade sem nunca ter tido contato com investimentos. As plataformas das corretoras são feitas para quem já sabe investir: são confusas e não ensinam o básico.

O TradeSim resolve isso com um ambiente seguro, didático e com elementos de jogo, pensado para ser usado em sala de aula.

## ✨ Funcionalidades

- **Carteira de investimentos:** acompanha o preço médio de compra e o lucro ou prejuízo de cada ativo
- **Compra e venda simuladas** com dados reais do mercado brasileiro
- **Notícias geradas por IA**, que influenciam o mercado simulado
- **Motor de preços próprio**, que simula a variação dos ativos
- **Níveis de dificuldade:** Novato, Amador e Experiente
- **Login de usuários** e dados salvos na nuvem

## 🖼️ Telas

**tela inicial**
<img width="1345" height="558" alt="primeira tela" src="https://github.com/user-attachments/assets/8d95f743-cbae-4bd1-bae1-7d90fcbad157" />
**dashboard**
<img width="1348" height="595" alt="dashboard" src="https://github.com/user-attachments/assets/a9719cb1-a1f6-43aa-887e-122ed635f749" />
**tela de mercado**
<img width="1348" height="588" alt="mercado" src="https://github.com/user-attachments/assets/b547c53b-d1e6-423a-a78f-d7e4ab7cd94b" />


## 🛠️ Tecnologias

| Parte | Tecnologia |
|---|---|
| Backend (servidor) | Python + FastAPI |
| Banco de dados e login | Firebase (Firestore e Firebase Auth) |
| Inteligência artificial | Google Gemini |
| Dados de mercado | Brapi e AwesomeAPI |

## 🏗️ Como funciona

```mermaid
flowchart LR
    A[Site do aluno] --> B[API em FastAPI]
    B --> C[(Firebase)]
    B --> D[Gemini - notícias com IA]
    B --> E[Brapi / AwesomeAPI - dados do mercado]
```

## 👤 Autor

**João**, estudante universitário interessado em mercado financeiro, produto e empreendedorismo em tecnologia.

- LinkedIn: _(seu link aqui)_
- E-mail: _(seu e-mail aqui)_
