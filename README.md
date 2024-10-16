# RELATÓRIO DE ACIDENTES NO TRÂNSITO 2024
***
*Qual a porcentagem de vítimas de acidentes de trânsito por idade?*

`=SOMASE(acidentes2024_todas_causas_tipo!$AA:$AA;">40";acidentes2024_todas_causas_tipo!$AF:$AF)`

![image](https://github.com/user-attachments/assets/af53a725-7c24-4beb-abe4-eedd7b4aba57)

*Qual o número de mortos, feridos graves, feridos leves e os que sairam ilesos dos acidentes de trânsito?*

`=SOMASE(acidentes2024_todas_causas_tipo!$F:$F;'Vitimas Acidentes'!$A2;acidentes2024_todas_causas_tipo!AF:AF)`

![image](https://github.com/user-attachments/assets/3de158b5-02fa-4f5c-b121-9b8e5bfc8834)

*Quais as principais causas de acidentes de trãnsito no Brasil?*

`=CONT.SE(acidentes2024_todas_causas_tipo!K:K;A2)`

![image](https://github.com/user-attachments/assets/36be5a1f-3b25-4e6a-93a7-28e53c6256bd)

*Qual a porcentagem do sexo das pessoas envolvidas em acidentes de trânsito?*

`=CONT.SE(acidentes2024_todas_causas_tipo!AB:AB;A2)`
# PowerBi
***
