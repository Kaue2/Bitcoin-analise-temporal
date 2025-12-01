## 📊 Descrição do Dataset

- **Origem:** Yahoo Finance (BTC-USD)
- **Credibilidade:** Fonte reconhecida globalmente para dados financeiros, amplamente utilizada em pesquisas acadêmicas e aplicações práticas.
- **Coleta:** Dados obtidos via API pública do Yahoo Finance utilizando a biblioteca `yfinance` em Python.
- **Tipo de dados:** Série temporal financeira (preço diário do Bitcoin).
- **Variáveis:**
  - Date → Data da observação
  - Open → Preço de abertura
  - High → Preço máximo
  - Low → Preço mínimo
  - Close → Preço de fechamento
  - Adj Close → Preço ajustado
  - Volume → Volume negociado
  - 
---

# 🚀 Como rodar o projeto com Jupyter Lab

Este projeto utiliza **Jupyter Lab** para análise de séries temporais com modelos e insights usando redis. Abaixo estão os passos necessários para configurar e executar o ambiente corretamente.

## 🧰 Pré-requisitos

- [Docker Desktop](https://www.docker.com/products/docker-desktop/) instalado e em execução
- Python 3.10+ instalado
- Git instalado (para clonar o repositório)

## 📥 Clonando o projeto

Para começar, clone este repositório em sua máquina local usando o comando abaixo:

```bash
  git clone https://github.com/Kaue2/Bitcoin-analise-temporal.git
  
  cd Bitcoin-analise-temporal
```

## 📦 Instalação dos pacotes

Antes de rodar o projeto, instale os pacotes necessários com base no arquivo `requirements.txt`:

```bash
  pip install -r requirements.txt 
``` 

E abra os notebooks com:
```bash
  jupyter lab 
```
