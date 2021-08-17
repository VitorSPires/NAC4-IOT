# NAC4-IOT
**Alunos:**
- Vitor Santana Pires
- Pedro Avelino
- Leonardo Dias
- Matheus Gregorio Simoni

**Turma:** 2TDSJ

**Ano**: 2021

## Objetivo / descrição do projeto
Projeto de cidade inteligente. Consiste em posicionar sensores em locais estratégicos para coletar informações de: _luminosidade_, _temperatura_ e _velocidade do vento_. Os dados são enviados a um controlador (_Arduino UNO_) que faz a comunicação via serial com o _Node-RED_, que por sua vez envia as informações para um banco de dados e, caso o ventos ultrapassem os _80 Km/h_, envia alertas pelo _Twitter_ de forma automática.

## Diagrama da solução
![Diagrama-NAC4](https://user-images.githubusercontent.com/61232337/129722493-5d4e375e-4cdf-421c-862e-13e5314e01a5.jpg)
