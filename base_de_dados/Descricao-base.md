### Conjunto de Dados sobre Doenças Cardíacas

#### Descrição das Variáveis

- **idade** - idade da pessoa (em anos)
- **sexo** - gênero da pessoa (1 = masculino; 0 = feminino)
- **tipo_dor_torácica** - tipo de dor torácica
  - Valor 0: angina típica
  - Valor 1: angina atípica
  - Valor 2: dor não anginosa
  - Valor 3: assintomático
- **pressão_arterial_repouso** - pressão arterial em repouso (em mm Hg na admissão ao hospital)
- **colesterol** - nível de colesterol sérico da pessoa em mg/dl
- **glicose_jejum** - glicose no sangue em jejum [> 120 mg/dl] (1 = verdadeiro; 0 = falso)
- **ecg_repouso** - ECG (eletrocardiograma) em repouso
  - Valor 0: normal
  - Valor 1: anomalia da onda ST-T (inversões da onda T e/ou elevação ou depressão do ST de > 0,05 mV)
  - Valor 2: mostrando hipertrofia ventricular esquerda provável ou definitiva pelos critérios de Estes
- **frequência_cardíaca_máxima** - frequência cardíaca máxima atingida
- **angina_exercício** - angina induzida pelo exercício (1 = sim; 0 = não)
  - A angina induzida pelo exercício é uma queixa comum de pacientes cardíacos, especialmente ao se exercitarem no frio. Geralmente ocorre durante a atividade (esforço) e desaparece com repouso ou medicação para angina. Por exemplo, dor ao caminhar morro acima ou em tempo frio pode ser angina. A dor da angina estável é previsível e geralmente semelhante a episódios anteriores de dor torácica.
- **depressão_ST** - depressão do segmento ST induzida pelo exercício em relação ao repouso
  - A depressão do segmento ST induzida pelo exercício é considerada um achado confiável de ECG para o diagnóstico de aterosclerose coronariana obstrutiva. A depressão do segmento ST é considerada um sinal eletrocardiográfico comum de isquemia miocárdica durante o teste de exercício. A isquemia é geralmente definida como privação de oxigênio devido à perfusão reduzida. A depressão do segmento ST inferior a 0,5 mm é aceita em todas as derivações. A depressão do segmento ST de 0,5 mm ou mais é considerada patológica.
- **inclinação** - inclinação do segmento ST no pico do exercício
  - Valor 0: inclinação ascendente
  - Valor 1: plana
  - Valor 2: inclinação descendente
- **num_veias_principais** - número de vasos principais (0-3) coloridos por fluoroscopia
- **talassemia** - talassemia
  - Valor 0: normal
  - Valor 1: defeito fixo
  - Valor 2: defeito reversível
  - Pessoas com talassemia podem acumular muito ferro em seus corpos, seja pela doença ou por transfusões de sangue frequentes. Muito ferro pode resultar em danos ao coração, fígado e sistema endócrino, que inclui glândulas produtoras de hormônios que regulam processos em todo o corpo.
- **alvo**
  - 0 = sem doença
  - 1 = com doença