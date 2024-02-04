
Desafio de Ciência de Dados - Precificação de Aluguéis Temporários
Este repositório contém a solução para o desafio de Ciência de Dados proposto, envolvendo a precificação de aluguéis temporários em Nova York. A solução inclui uma análise exploratória dos dados, a construção de um modelo de previsão de preços e a avaliação desse modelo.


Estrutura do Repositório
/data: Pasta contendo o arquivo CSV com os dados de treinamento.
/notebooks: Notebooks Jupyter contendo a análise exploratória e a construção do modelo.
/models: Pasta para armazenar o modelo treinado no formato .pkl.
/reports: Relatórios em PDF das análises exploratórias.

Pré-requisitos
Python 3.x
Pacotes listados no arquivo requirements.txt. Você pode instalá-los usando o comando pip install -r requirements.txt.

Como Executar
Clone o repositório: git clone https://github.com/RaquelFonsec/Desafio-Data-Science.git
Navegue até o diretório: cd Desafio-Data-Science
Instale as dependências: pip install -r requirements.txt
Execute os notebooks no diretório /notebooks na ordem desejada.


Resultados da Análise Exploratória
Durante a análise exploratória dos dados, foram observados alguns padrões e tendências importantes. Abaixo estão alguns dos principais resultados:

Distribuição de Preços
A distribuição de preços revelou uma concentração em faixas específicas, indicando possíveis padrões de precificação. Além disso, identificamos a presença de alguns outliers que podem influenciar as análises.

Relação entre Disponibilidade e Preço
Durante a análise da relação entre a disponibilidade ao longo do ano e os preços, foram identificadas correlações distintas em diferentes bairros. A observação dessas variações sazonais nos preços com base na disponibilidade sugere um impacto significativo na precificação.

Insights:

Variações Sazonais: Foi notada uma clara variação nos preços em relação à disponibilidade ao longo do ano. Picos de preços podem estar associados a períodos de alta demanda, como temporadas turísticas ou eventos especiais.

Diferenças entre Bairros: A análise revelou que a relação entre disponibilidade e preço pode variar consideravelmente entre os bairros. Alguns bairros podem mostrar uma correlação mais forte, enquanto outros podem apresentar uma influência menos pronunciada.


Potencial Impacto na Estratégia de Precificação: A compreensão dessas correlações pode ser crucial para desenvolver estratégias de precificação mais eficientes. A adaptação da estratégia com base na relação específica de cada bairro permite uma abordagem mais precisa na definição de preços.


Word Cloud dos Nomes dos Locais
A nuvem de palavras gerada a partir dos nomes dos locais proporcionou insights interessantes, revelando palavras frequentes como Manhatan, Brooklyn etc. Essas associações podem indicar padrões criativos que influenciam a percepção do valor do local.

Localização para Investir: O gráfico de barras "Preço Médio por Bairro" sugere onde seria mais indicado investir com base nos preços médios, destacando os bairros com preços mais altos e mais baixos.

Impacto de Noites Mínimas e Disponibilidade: O mapa de calor mostra a correlação entre noites mínimas, disponibilidade e preço. Correlações mais fortes indicam um impacto mais significativo no preço.

Padrão no Texto do Nome do Local: A nuvem de palavras ajuda a identificar palavras comuns em locais de maior valor, proporcionando insights sobre possíveis padrões de nomenclatura.

Sugestão de Preço para o Apartamento Fornecido
Com base nas características fornecidas para um apartamento específico, a sugestão de preço calculada usando o modelo treinado foi de 190.30. Essa estimativa leva em consideração o bairro, número mínimo de noites e disponibilidade ao longo do ano.
z
