# RELATÓRIO DE ACIDENTES NO TRÂNSITO 2024
***
*Qual a porcentagem de vítimas de acidentes de trânsito por idade?*

`=SOMASE(acidentes2024_todas_causas_tipo!$AA:$AA;">40";acidentes2024_todas_causas_tipo!$AF:$AF)`

*Qual o número de mortos, feridos graves, feridos leves e os que sairam ilesos dos acidentes de trânsito?*

`=SOMASE(acidentes2024_todas_causas_tipo!$F:$F;'Vitimas Acidentes'!$A2;acidentes2024_todas_causas_tipo!AF:AF)`

*Quais as principais causs de acidentes de trãnsito no Brasil?*

`=CONT.SE(acidentes2024_todas_causas_tipo!K:K;A2)`

*Qual a porcentagem do sexo das pessoas envolvidas em acidentes de trânsito?*

`=CONT.SE(acidentes2024_todas_causas_tipo!AB:AB;A2)`
