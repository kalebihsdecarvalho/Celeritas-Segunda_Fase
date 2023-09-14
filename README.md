# Celeritas-Segunda_Fase
O projeto consiste em construir um modelo de classificação que seja capaz de prever se uma região é perigosa ou não para turistas. Os dados que serão utilizados para treinar o modelo são dados de crimes contra o patrimônio, coletados diariamente durante os últimos 12 meses em uma cidade turística do Brasil.

A planilha de treinamento fornecida tem 8000 instâncias, cada uma representando uma região. Cada instância possui 20 características, que são fatores que podem contribuir para a periculosidade de uma região, como por exemplo, o número de habitantes, o número de roubos e furtos, a renda média dos habitantes, etc. A coluna "target" indica se a região é perigosa (valor 1) ou não perigosa (valor 0).

Após treinar o modelo, ele será usado para prever a periculosidade de regiões que não estão na planilha de treinamento. A planilha de teste fornecida tem 2400 instâncias, que são semelhantes às instâncias da planilha de treinamento, mas não possuem os rótulos de periculosidade.

O objetivo do projeto é desenvolver um modelo capaz de prever a periculosidade de regiões com alta precisão. Um modelo preciso pode ajudar a proteger turistas e moradores de regiões perigosas.

Aqui estão algumas etapas específicas do projeto:

    Preparação dos dados: os dados precisam ser preparados para o treinamento do modelo. Isso inclui a limpeza dos dados, a remoção de valores ausentes e a transformação das variáveis para que elas sejam compatíveis com o modelo escolhido.
    Seleção do modelo: existem vários modelos de classificação que podem ser usados para esse projeto. O modelo ideal será aquele que apresentar a melhor precisão no conjunto de treinamento.
    Treinamento do modelo: o modelo será treinado usando os dados de treinamento. O processo de treinamento envolve a otimização dos parâmetros do modelo para que ele possa prever a periculosidade das regiões com a maior precisão possível.
    Validação do modelo: o modelo será validado usando os dados de teste. A validação é importante para avaliar a generalização do modelo, ou seja, para verificar se ele é capaz de prever a periculosidade de regiões novas, que não foram usadas para o treinamento.
    Predição de novas instâncias: o modelo será usado para prever a periculosidade das regiões da planilha de teste.

O projeto será avaliado com base na precisão do modelo na previsão da periculosidade das regiões da planilha de teste.
