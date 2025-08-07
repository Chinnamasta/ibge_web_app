# Web App Nomes BR 🇧🇷

Este projeto é um web app simples que consulta dados do IBGE (Instituto Brasileiro de Geografia e Estatística) sobre a frequência de nomes no Brasil ao longo das décadas. 🔎 Ele permite que o usuário digite um nome e visualize a sua popularidade em um gráfico de linha e em uma tabela. 📊

O web app foi desenvolvido em Python, utilizando as bibliotecas `streamlit` para a interface, `pandas` para manipulação de dados e `requests` para fazer a requisição à API do IBGE. 🐍

## Funcionalidades ✨

- **Consulta por Nome:** O usuário pode inserir um nome no campo de busca. ✍️
- **Dados do IBGE:** O app faz uma requisição à API de Nomes do IBGE para obter a frequência do nome por década. 📈
- **Tabela de Frequência:** Exibe uma tabela com a frequência do nome para cada década pesquisada. 📋
- **Gráfico de Evolução:** Apresenta um gráfico de linha que mostra a evolução da popularidade do nome ao longo do tempo. 📉
- **Tratamento de Erros:** Exibe uma mensagem de aviso caso não encontre dados para o nome pesquisado. ⚠️

## Tecnologias Utilizadas 🛠️

- **Python:** Linguagem de programação principal. 🐍
- **Streamlit:** Framework para criar e compartilhar web apps de machine learning e ciência de dados. 🎈
- **Pandas:** Biblioteca para manipulação e análise de dados. 🐼
- **Requests:** Biblioteca para fazer requisições HTTP. 🌐
- **API de Nomes do IBGE:** A fonte dos dados utilizados no projeto. 📚

## Como Executar o Projeto 🚀

Para rodar este projeto localmente, siga os passos abaixo:

### 1. Pré-requisitos ✅

Certifique-se de ter o Python instalado em sua máquina.

### 2. Clonar o Repositório 📂

```bash
pip install streamlit pandas requests
streamlit run app.py # ou o nome do seu arquivo principal

## Contribuição 🤝
Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request se encontrar um bug ou tiver uma sugestão de melhoria. 💡

## Licença 📜
Este projeto está licenciado sob a licença MIT.
git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)
cd seu-repositorio
