# Alura-Store
Alura Store - Análise de Vendas
Bem-vindo ao Alura Store - Análise de Vendas, um projeto de ciência de dados desenvolvido como parte do Challenge Data Science da Alura. Este projeto analisa dados de vendas de quatro lojas virtuais, calculando o faturamento total e o ticket médio por loja, com visualização em gráficos.

# 📖 Sobre o Projeto
O projeto utiliza dados de vendas das lojas do sr. João, contendo informações como produto, preço, frete, data da compra, vendedor, localização e avaliações. O objetivo é realizar uma análise exploratória para calcular o faturamento total de cada loja e o ticket médio, além de gerar visualizações para insights sobre o desempenho das vendas.

# 🚀 Funcionalidades
Importação de Dados: Carrega dados de vendas de quatro lojas a partir de arquivos CSV hospedados no GitHub.
Cálculo de Faturamento: Calcula o faturamento total (preço + frete) de cada loja e exibe uma tabela com valores absolutos, percentuais e acumulados.
Ticket Médio: Calcula o ticket médio por loja e gera um gráfico de barras para visualização.
Tratamento de Erros: Funções com tratamento de exceções para garantir robustez na análise.
Valores Monetários: Exibe valores em reais (R$) sem problemas de formatação no Google Colab.

# 🛠️ Tecnologias Utilizadas
Python 3: Linguagem principal para análise de dados.
Pandas: Manipulação e análise de dados em DataFrames.
Matplotlib: Geração de gráficos para visualização do ticket médio.
Google Colab: Ambiente de execução do notebook.

# 📋 Pré-requisitos
Para executar o projeto localmente, você precisará de:

Python 3.8 ou superior.
Bibliotecas Python:
```bash
pip install pandas matplotlib
```
Opcional: Google Colab para executar o notebook diretamente no navegador.
Acesso à internet para carregar os dados dos arquivos CSV hospedados no GitHub.
⚙️ Instalação
Clone o repositório:
```bash
git clone https://github.com/rafaelherbster/Alura-Store.git
```

# 📊 Dados
Os dados são provenientes de quatro arquivos CSV (loja_1.csv, loja_2.csv, loja_3.csv, loja_4.csv) hospedados no repositório da Alura. Cada arquivo contém as seguintes colunas:

Produto: Nome do produto vendido.

Categoria do Produto: Categoria (ex.: eletrônicos, móveis).

Preço: Valor do produto em reais (R$).

Frete: Custo do frete em reais (R$).

Data da Compra: Data da transação.

Vendedor: Nome do vendedor.

Local da compra: Estado (ex.: SP, RJ).

Avaliação da compra: Nota de 1 a 5.

Tipo de pagamento: Método de pagamento (ex.: cartão de crédito, boleto).

Quantidade de parcelas: Número de parcelas.

lat e lon: Coordenadas geográficas do local da compra.

# 📈 Resultados
Faturamento: A função faturar() calcula o faturamento total por loja e exibe uma tabela com:
Faturamento em reais (R$).
Percentual do faturamento total.
Faturamento acumulado e percentual acumulado.
Ticket Médio: A função grafico_ticketMedio() gera um gráfico de barras mostrando o ticket médio por loja.
Exemplo de Saída

| Loja   | Faturamento (R$) | %     | Acumulado (R$) | %Acumulado |
|--------|------------------|-------|----------------|------------|
| Loja 1 | 1,616,346.99     | 26.14 | 1,616,346.99   | 26.14      |
| Loja 2 | 1,567,773.29     | 25.35 | 3,184,120.28   | 51.49      |
| Loja 3 | 1,542,047.52     | 24.93 | 4,726,167.80   | 76.42      |
| Loja 4 | 1,458,253.56     | 23.58 | 6,184,421.36   | 100.00     |

(Valores formatados com R\$ no README para evitar problemas de renderização no Colab.)

# 📷 Demonstração
O gráfico de ticket médio é gerado usando Matplotlib e exibido no notebook. Para visualizar, execute a função grafico_ticketMedio() no ambiente do Colab ou Jupyter.

(Adicione capturas de tela do gráfico ou da tabela ao repositório, se desejar.)

# 🤝 Como Contribuir
Faça um fork do repositório.
Crie uma branch para sua feature ou correção:
```bash
git checkout -b minha-nova-feature
```
Faça suas alterações e commit:
```bash
git commit -m "Adiciona minha nova feature"
```
Envie para o repositório remoto:
```bash
git push origin minha-nova-feature
```
Abra um Pull Request no GitHub.
Por favor, siga as diretrizes de contribuição e mantenha a formatação do código consistente.

# 📜 Licença
Este projeto está licenciado sob a MIT License.

# 🙌 Agradecimentos
À Alura pelo Challenge Data Science e pelos dados fornecidos.
À comunidade Python pelas bibliotecas Pandas e Matplotlib.

# 💡 Nota sobre Formatação de Valores Monetários no Google Colab
Para evitar que o caractere $ seja interpretado como LaTeX no Google Colab, use a barra invertida (\) antes do símbolo, como R\$. Exemplo em uma célula de texto:

```markdown
O faturamento é R\$1,616,346.99.
```
Alternativamente, envolva o texto em crases (`) para exibir como código:

```markdown
`R$1,616,346.99`
```
⭐ Se achou este projeto útil, deixe uma estrela no repositório!
Todos os direitos reservados. Rafael Herbster de Sena Maciel. 2025.

Email: rafaelherbster8@gmail.com 

Linkedin: www.linkedin.com/in/rafael-herbster
