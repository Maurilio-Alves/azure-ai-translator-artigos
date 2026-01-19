# 🤖 Tradutor de Artigos Técnicos com Azure AI

Este projeto foi desenvolvido como parte de um desafio da **DIO (Digital Innovation One)**. O objetivo é criar uma ferramenta que utiliza o serviço de **Azure AI Translator** para traduzir artigos técnicos diretamente de páginas da web.

## 🛠️ Tecnologias Utilizadas

* **Python**: Linguagem base do projeto.
* **Azure AI Translator**: Serviço de tradução inteligente da Microsoft.
* **BeautifulSoup**: Para extração de conteúdo (Web Scraping) do site Dev.to.
* **Requests**: Para comunicação com a API do Azure.

## 🚀 Como funciona

1. O script `tradutor_web.py` acessa a URL de um artigo técnico (ex: Dev.to).
2. O conteúdo é extraído e limpo, focando apenas no texto principal.
3. O texto é enviado em blocos para o recurso de IA no Azure (`meu-tradutor-maurilio`).
4. A tradução é salva automaticamente em um arquivo na pasta `/outputs`.

## 📊 Resultados
O projeto demonstrou alta precisão na tradução de termos técnicos como "Framework", "Multi-currency" e "Machine Learning", mantendo o contexto original.

---
Desenvolvido por **Maurilio** como parte do portfólio de IA.