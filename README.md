# NAC4-IOT
**Alunos:**
- Vitor Santana Pires
- Pedro Avelino
- Leonardo Dias
- Matheus Gregorio Simoni

**Turma:** 2TDSJ

**Ano**: 2021

## Objetivo / descrição do projeto
Projeto de cidade inteligente. Consiste em posicionar sensores em locais estratégicos para coletar informações de: luminosidade, temperatura e velocidade do vento. Os dados são enviados a um controlador (Arduino UNO) que faz a comunicação via serial com o Node-RED, que por sua vez armazena as informações para um banco de dados e, caso o ventos ultrapassem os 80 Km/h, envia alertas pelo Twitter de forma automática.

## Diagrama da solução
![Diagrama-NAC4](https://user-images.githubusercontent.com/61232337/129722493-5d4e375e-4cdf-421c-862e-13e5314e01a5.jpg)

## Como usar
1. **Cole esse código no CMD para clonar o peojeto na sua máquina local**
```
git clone https://github.com/VitorSPires/NAC4-IOT
```

2. **Softwares necessários**
    - <a href="https://www.simulide.com/p/home.html" target="_blank">SimulIDE</a>
    - <a href="https://www.arduino.cc" target="_blank">Arduino</a>
    - [com0com](https://github.com/VitorSPires/NAC4-IOT/files/7010892/com0com.zip)
    - <a href="https://nodered.org" target="_blank">Node-RED</a>

3. **Configurando o Com0com**
    - <a href="https://www.youtube.com/watch?v=I6YIPL_p-L0" target="_blank">Tutorial</a>

4. **Rodando o sistema**

      Após a instalação dos softwares necessários, abra o SimulIDE e importe os arquivos de extensão _.simu_ e _.ino_ para e depois importe o código para o controlador. Inicie a simulação e o sistema será ativado.
 
5. **Fazendo alterações**

    Para modificar o código do controlador, basta editar o arquivo _.ino_ e importá-lo novamente

    Para iniciar o servidor local Node-RED, abra o CMD e digite:
    ```
   node-red
    ```
    Abra as seguintes páginas no navegador: <br>
          - <a href="https://127.0.0.1:1880" target="_blank">Node-RED</a><br>
          - <a href="https://127.0.0.1:1880/ui/" target="_blank">Dashboard</a>

## Link de vídeo demonstração
<a href="https://www.youtube.com/watch?v=baFG36Lkv8Y" target="_blank">Demonstração NAC4</a>

## Referências
- <a href="https://github.com/VitorSPires/NAC4-IOT/files/7010818/s2-NAC4.pptx" target="_blank">Proposta-NAC4</a>
- <a href="https://www.youtube.com/watch?v=oPLCOFkpYmM" target="_blank">Como usar o frequencímetro</a>
- <a href="https://github.com/VitorSPires/NAC4-IOT/files/7010814/DisruptiveArchitecturesIOTeIA_Aula.02.pdf" target="_blank">Conectando o Node-RED com Twitter e banco de dados</a>
- <a href="https://www.youtube.com/watch?v=I6YIPL_p-L0" target="_blank">Comunicação serial emulada</a>
