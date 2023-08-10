# RPA Challenge
### Robô feito para o desafio proposto no site RPA Challenge (https://rpachallenge.com)

Técnologias e Linguagens:
- UiPath Studio
- UiPath Orchestrator
- UiPath Assistant
- VBA
- Excel

<br>

### Desafio proposto:

- O objetivo deste desafio é criar um fluxo de trabalho que irá inserir dados de uma planilha nos campos do formulário na tela.

- Atenção! Os campos mudarão de posição na tela após cada envio ao longo de 10 rodadas, portanto, o fluxo de trabalho deve identificar corretamente onde cada registro da planilha deve ser digitado a cada vez.

- A contagem regressiva real do desafio começará assim que você clicar no botão Iniciar, até lá, você pode enviar o formulário quantas vezes desejar sem receber penalidades.

<br>

## Processo
#### 1- O robô primeiramente examina a planilha e coloca todas suas informações em uma tabela de dados
![image](https://github.com/Luis-Barros1/RPA_Challenge/assets/66507497/9590ef50-ba0b-4f31-9610-1b04a5ba1a42)

<br>

#### 2- Em sequência ele irá carregas essa informações para uma fila pré-inserida no orchestrador
![image](https://github.com/Luis-Barros1/RPA_Challenge/assets/66507497/b5364353-f7af-44b0-9bd0-b896c6200d9a)

<br>

#### 3- Para cada item da fila o robô irá buscar os campos na tela com base em suas âncoras e iserir os dados correspondentes e clicar em "Submit"
![image](https://github.com/Luis-Barros1/RPA_Challenge/assets/66507497/16ab63d6-f89f-4845-934d-831454f657c8)

<br>

#### 4- Por fim o robô finaliza o teste com 100% de acerto quanto a informação e campos onde ela foi inserida e finaliza o processo em uma média de 26 segundos
![image](https://github.com/Luis-Barros1/RPA_Challenge/assets/66507497/a467202a-aa9d-4794-b100-0214572f8007)






