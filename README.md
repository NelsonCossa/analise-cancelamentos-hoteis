##Análise de Cancelamentos de Reservas Hoteleiras e Impacto na Geração de Receitas

## Contexto e Problema de Negócio
Nos últimos anos, o City Hotel e o Resort Hotel têm registado elevadas taxas de cancelamento de reservas, resultando na redução das receitas e numa utilização ineficiente dos quartos disponíveis. Reduzir estas taxas é crucial para aumentar a eficiência operacional e maximizar a geração de receitas.

## Objetivo do Projeto
### Objetivo Geral
Analisar os padrões de cancelamento de reservas hoteleiras e o seu impacto na geração de receitas no City Hotel e no Resort Hotel.

### Objetivos Específicos
- Identificar a taxa de cancelamento de reservas  
- Comparar reservas canceladas e não canceladas  
- Avaliar o impacto dos cancelamentos na tarifa média diária  
- Analisar a evolução temporal dos cancelamentos  
- Apoiar a formulação de recomendações empresariais  

## Estrutura do Projeto
analise-cancelamentos-hoteis/
│
├── data/ # Datasets utilizados (ex: hotel_booking.csv)
├── notebooks/ # Notebooks Jupyter com análise e visualizações
├── src/ # Scripts Python com funções reutilizáveis
├── requirements.txt # Dependências do projeto
├── README.md # Documentação do projeto
└── .gitignore # Arquivos ignorados pelo Git

## Tecnologias e Bibliotecas
- **Linguagem:** Python 3.x  
- **Análise de dados:** pandas, numpy  
- **Visualização:** matplotlib, seaborn  
- **Ambiente de execução:** Jupyter Notebook  

## Como Rodar o Projeto
1. **Clonar o repositório**
```bash
git clone https://github.com/SEU_USUARIO/analise-cancelamentos-hoteis.git
cd analise-cancelamentos-hoteis



## Instalar dependências

pip install -r requirements.txt

## Abrir o notebook
jupyter notebook notebooks/analise_cancelamentos.ipynb
