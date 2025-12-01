# 🎓 Plano de Estudos FATEC

Um gerenciador de estudos interativo e visual para candidatos do Vestibular da FATEC (Faculdade de Tecnologia de São Paulo).

🔗 **[Acesse o projeto online aqui](https://fatec-projeto.netlify.app/)**

## 📋 Sobre o Projeto

Desenvolvi esta aplicação para ajudar estudantes a organizarem o vasto conteúdo do edital da FATEC. O objetivo é gamificar o estudo, permitindo visualizar o progresso em tempo real através de gráficos e checklists.

Diferente de aplicações React tradicionais, este projeto foi construído para ser **leve e sem dependências de build** (como Webpack ou Vite), rodando diretamente no navegador.

## ✨ Funcionalidades

* **Checklist de Matérias:** Conteúdo completo do edital dividido por áreas (Português, Matemática, Ciências e Humanas).
* **Progresso Visual:** Gráfico de anel e barras de progresso que atualizam automaticamente conforme você marca os tópicos.
* **Persistência de Dados:** O progresso é salvo automaticamente no `LocalStorage` do navegador. Você pode fechar a aba e voltar depois que seus dados estarão lá.
* **Guia de Redação:** Dicas rápidas sobre critérios de avaliação e o que zera a nota.
* **Interface Responsiva:** Funciona bem no computador e no celular.

## 🛠️ Tecnologias Utilizadas

* **React (via CDN):** Para gerenciamento de estado (`useState`, `useEffect`) e componentes.
* **Tailwind CSS (via CDN):** Para estilização rápida e responsiva.
* **Babel (via CDN):** Para transpilar o JSX diretamente no browser.
* **HTML5 & JavaScript (ES6+):** Estrutura base.

## 🚀 Como rodar localmente

Como o projeto não utiliza Node.js ou bundlers, é extremamente simples de rodar:

1. Clone este repositório:
   ```bash
   git clone [https://github.com/SEU_USUARIO/plano-estudos-fatec.git](https://github.com/SEU_USUARIO/plano-estudos-fatec.git)
