# Modelo de Previsão de Inadimplência

Este repositório contém um estudo de base de dados e a aplicação de modelos preditivos para identificar potenciais riscos de inadimplência em empréstimos bancários. A base de dados em estudo está disponível em https://www.kaggle.com/datasets/yasserh/loan-default-dataset

## Descrição

A inadimplência em empréstimos representa um desafio significativo para instituições financeiras. Antecipar quais clientes possuem maior probabilidade de não cumprir suas obrigações financeiras permite que os bancos tomem medidas preventivas, minimizando perdas. Este projeto busca analisar dados históricos de clientes e aplicar modelos estatísticos e de machine learning para prever a probabilidade de inadimplência.

## Funcionalidades

- Análise exploratória dos dados para identificar padrões e variáveis relevantes.
- Pré-processamento dos dados, incluindo tratamento de valores ausentes e codificação de variáveis categóricas.
- Implementação de diversos modelos preditivos, como regressão logística, árvores de decisão e random forest.
- Avaliação e comparação do desempenho dos modelos utilizando métricas apropriadas.

## Tecnologias Utilizadas

- **Linguagem de Programação:** Python
- **Bibliotecas:**
  - Pandas
  - NumPy
  - Scikit-learn
  - Matplotlib
  - Seaborn
- **Ambiente de Desenvolvimento:** Jupyter Notebook

## Como Executar o Projeto

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/pavaladao/modelo-previsao-inadimplencia.git
   ```

2. **Navegue até o diretório do projeto:**

   ```bash
   cd modelo-previsao-inadimplencia
   ```

3. **Instale as dependências necessárias:**

   Certifique-se de que você tem o Python instalado. Recomenda-se o uso de um ambiente virtual.

   ```bash
   pip install -r requirements.txt
   ```

4. **Inicie o Jupyter Notebook:**

   ```bash
   jupyter notebook
   ```

5. **Abra e execute o notebook:**

   No navegador, abra o arquivo `Estudo-risco-inadimplencia.ipynb` e execute as células sequencialmente.

## Estrutura de Arquivos

```plaintext
modelo-previsao-inadimplencia/
├── Estudo-risco-inadimplencia.ipynb  # Notebook principal com a análise e modelagem
```

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.

---

*Observação:* Certifique-se de que os dados utilizados estão disponíveis no diretório `data/` e que você possui as permissões necessárias para utilizá-los. 
