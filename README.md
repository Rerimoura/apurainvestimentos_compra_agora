# 📊 Apurador de Investimentos (Versão Excel)

Aplicação web para apuração de investimentos em promoções de produtos, construída com Streamlit.

## 🚀 Acesso

Acesse a aplicação diretamente pelo Streamlit Cloud:
👉 *(link será gerado após o deploy)*

## ✨ Funcionalidades

- Upload da **planilha Simulador** (Preço Final) com COD BARRAS e Valor Negociado
- Upload de um ou mais **arquivos Excel de Orçamento** (Compra Agora)
- Cruzamento automático de produtos por código
- Cálculo de **Investimento Total (Verba)** e **Valor Total de Pedido**
- Geração de **relatório Excel formatado** com:
  - Resumo geral (Verba Total, TT.Pedido, % Investimento)
  - Formatação de moeda (R$) e percentual
  - Cores personalizadas por tipo de coluna
- Download da planilha modelo Compra Agora

## 📋 Como Usar

1. **Planilha Simulador** — Faça upload do Excel com colunas `COD BARRAS` (ou `EAN`, `CÓDIGO BIZ`) e `Valor Negociado`
2. **Nome da Rede** — Informe o nome da rede para identificação no relatório
3. **Orçamentos Excel** — Faça upload dos arquivos Excel de orçamento (com colunas `EAN`, `QUANTIDADE`, `PREÇO`)
4. **Processar** — Clique em "Processar e Calcular Investimentos"
5. **Download** — Baixe o resultado em Excel formatado

## 🛠️ Tecnologias

- Python 3.9+
- [Streamlit](https://streamlit.io/)
- [Pandas](https://pandas.pydata.org/)
- [OpenPyXL](https://openpyxl.readthedocs.io/)

## 📦 Instalação Local

```bash
pip install -r requirements.txt
streamlit run app_apurador_excel.py
```

## 📄 Licença

Uso interno — Projeto Nivea
