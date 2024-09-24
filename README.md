# MVP-Ciencia-de-Dados
Este trabalho é para conclusão do curso de Pós Graduação em Ciências de Dados e Analytics Puc Rio de Janeiro 

Conhecendo os datasets

Colunas presentes em todos os dataframes:

* FID:  Chave primária de cada dataset;
* Geocodigo: código do município;
* Nome: nome do município;
* MoradDPPOTot ou MoradDPPOTotTot: Total de pessoas em **domicílios particulares permanente ocupados (DPPO)**.

Cabe ressaltar que cada campo (coluna) tem a sua correspondente em percentagem que é calculada em relação ao total de moradores em domicílios (DPPO). Estas se iniciam com "Perc" e segue com denominação da coluna com valores absolutos. Exemplo: MoradDPPOTotVala tem como correspondente em termos percentuais a PercMoradDPPOTotVala.
---
Dicionário das colunas densDemog:

* AreaUnidTerrit: Área em km² do município;
* DensDemog: Densidade Demográfica do município p/km²;
* PopResid: População residente do município.
---
Dicionário das colunas coletaLixoMun:

* MoradDPPOColetDomicServLimpTot: Pessoas em domicílios (DPPO) que tem o lixo coletado no domicílio por serviço de limpeza;
* MoradDPPOColetTot: Pessoas em domicílios (DPPO) que possui coleta de lixo direta ou indireta (em domícilio ou através do deposito em caçambas). Os valores refletem a soma da coluna MoradDPPOColetDomicServLimpTot com a MoradDPPODepCacambServLimpTot;
* MoradDPPODepCacambServLimpTot: Pessoas em domicílios (DPPO) que depositam o lixo em caçambas de serviço de limpeza.
---
Dicionário colunas do Dataframe esgotamentoSanitario:

* MoradDPPOTotFossaRudimBur: Pessoas em domicílios (DPPO) com esgotamento sanitário em fossa rundimentar ou buraco;
* MoradDPPOTotFossaSeptOuFiltroNaoRede: Pessoas em domicílios (DPPO) com esgotamento sanitário em fossa séptica ou filtro não ligado à rede;
* MoradDPPOTotFossaSeptOuFiltroRede: Pessoas em domicílios (DPPO) com esgotamento sanitário em fossa séptica ou fossa filtro ligado à rede;
* MoradDPPOTotOutraForma: Pessoas em domicílios (DPPO) com esgotamento sanitário de outra forma;
* MoradDPPOTotRedeGeralPluv: Pessoas em domicílios (DPPO) com esgotamento sanitário ligado a rede geral ou rede pluvial;
* MoradDPPOTotRedeGeralPluvFossaRede: Pessoas em domicílios (DPPO) com esgotamento sanitário ligado a rede geral ou pluvial ou fossa septica ligada à rede. Os valores apresentados representados nesta coluna representa a soma da MoradDPPOTotFossaSeptOuFiltroRede com a MoradDPPOTotRedeGeralPluv;
* MoradDPPOTotRioLagoCorregMar: Pessoas em domicílios (DPPO) com esgotamento sanitário despejado em rio, lago, corrego e mar;
* MoradDPPOTotSemBanhOuSanit: Pessoas em domicílios (DPPO) sem banheiro ou sanitário;
* MoradDPPOTotVala: Pessoas em domicílios (DPPO) com esgotamento sanitário por valas.
---
Dicionário colunas do Dataframe aguaCanalizada:

* MoradDPPOCanalizCasaTot: Pessoas em domicílios (DPPO) com água canalizada até interior da casa;
* MoradDPPOCanalizTerrTot: Pessoas em domicílios (DPPO) com água canalizada até o terreno;
* MoradDPPOSemCanalizTot: Pessoas em domicílios (DPPO) sem água canalizada.
---
Dicionário colunas do Dataframe aguaRedeDistr:

* MoradDPPOTotChuva: Pessoas em domicílios (DPPO) abastecidos principalmente com água armazenda de chuvas;
* MoradDPPOTotFonte: Pessoas em domicílios (DPPO) abastecidos principalmente com água de fonte, nascente ou mina;
* MoradDPPOTotOutra: Pessoas em domicílios (DPPO) abastecidos principalmente com água de outra forma;
* MoradDPPOTotPipa: Pessoas em domicílios (DPPO) abastecidos principalmente com água de carro-pipa;
* MoradDPPOTotPocoProfund: Pessoas em domicílios (DPPO) abastecidos principalmente com água de poço profundo ou artesiano;
* MoradDPPOTotPocoRaso: Pessoas em domicílios (DPPO) abastecidos principalmente com água de poço raso, freático ou cacimba;
* MoradDPPOTotRedeGeral: Pessoas em domicílios (DPPO) abastecidos principalmente com água da rede geral de distribuição;
* MoradDPPOTotRios: Pessoas em domicílios (DPPO) abastecidos principalmente com água de rios.

