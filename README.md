 ## *CLASSIFICAÇÃO DE USO E OCUPAÇÃO DA TERRA NA BACIA HIDROGRÁFICA DO RIO DE ONDAS-BA ATRAVÉS DE ALGORÍTMO DE APRENDIZADO DE MÁQUINA*
 
 <p align="justify">
Esse projeto se trata de um estudo na região da bacia do Rio de Ondas - BA, sobre uso e cobertura  da terra,  através da plataforma do Google Earth Engine (GEE), com processamento de imagens dos landsat 5 TM e landsat8 OLI, implementando algoritmo de aprendizagem de maquina Random Forest. Abaixo segue o produtos gerados nesse projeto:
</p>

<div align="center">
 
### Figura 1 – Mapa de localização da bacia hidrográfica do Rio de Ondas- BA. 
<img width="1123" height="794" alt="localização_Mapa-test4" src="https://github.com/user-attachments/assets/655e0ac0-8526-43bd-98bc-e82fbf0ea142" />

*Fonte: autor.*

</div>

<div align="center">

### Figura 2 – Mosaico dos mapas classificados.
<img width="1123" height="794" alt="Mosaico_Mapas3" src="https://github.com/user-attachments/assets/7b36d693-9720-490f-9e06-46b0ab74056b" /> 

*Fonte: autor.*
</div>

<div align="center">

### Tabela 1: Evolução das Áreas (ha) por Classe de uso e cobertura da terra

| Classes / Anos | 1985 | 1990 | 2000 | 2010 | 2020 |
| :---: | :---: | :---: | :---: | :---: | :---: |
| Água | 16.839 | 18.909 | 13.641 | 10.213 | 10.968 |
| Vegetação | 138.066 | 122.453 | 147.562 | 171.040 | 203.898 |
| Agricultura | 110.602 | 149.779 | 100.740 | 100.643 | 93.870 |
| Solo Exposto | 235.859 | 218.718 | 211.218 | 223.637 | 229.671 |
| Área Urbana | 61.509 | 53.015 | 89.714 | 57.343 | 24.468 |
| **Total (ha)** | **562.875** | **562.874** | **562.875** | **562.876** | **562.875** |

*O ano de 1985 foi adotado como marco representativo para a década de 1980.*

*Fonte: autor.*

</div>


<div align="center">

### Tabela 2: Comparativo de Índices Kappa (Real vs. Automático)

| Anos | Kappa GEE<br>(Automático) | Kappa ArcGIS<br>(Manual) | Diferença<br>(viciamento) |
| :---: | :---: | :---: | :---: |
| 1985 | 1.0 (100%) | 0.28 (28%) | 72 % |
| 1990 | 0.99 (99%) | 0.18 (18%) | 81% |
| 2000 | 1.0 (100%) | 0.30 (30%) | 70% |
| 2010 | 0.99 (99%) | 0.35 (35%) | 64% |
| 2020 | 0.99 (99%) | 0.56 (56%) | 43% |

*Fonte: autor.*
</div>


