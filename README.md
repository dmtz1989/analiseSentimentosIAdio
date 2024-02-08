# Desafio "Análise de Sentimentos com Language Studio no Azure AI"

##### Como parte da resolução do desafio proposto pela DIO, estou descrevendo as etapas de como realizei a criação dos pontos de extremidades que usei no laboratório de Machine Learning.

##### Os passos seguidos foram:

###### 1. Foi criada uma conta no Portal do Azure (https://portal.azure.com/).
###### 2. Após a conta criada, foi realizada a criação do Resource Group.
###### 3. Com o Resource Group criado, foi realizada a criação de um Azure AI Services, com as seguintes configurações:

    Subscription: Your Azure subscription.
    Resource group: LAB-AI-900-DIO
    Region: East US.
    Name: idiomaLanguageDIO.
    
###### 4. Após a criação do Azure Ai Service, acessei o Language Studio, através da URL "https://language.cognitive.azure.com/".
###### 5. Após o login no Language Studio, foi selecionada o Resource para poder iniciar a análise dos textos. Os inputs utilizados, como o output gerado, estão nas pastas "inputs" e "output", respectivamente.
###### 6. Foi realizada a análise do texto apresentado abaixo. O texto também se encontra na pasta "inputs", dentro do repositório:
![input](https://github.com/dmtz1989/analiseSentimentosIAdio/blob/main/Inputs/Input.png)

    Fui para Recife comprar remédios, mas eles estavam muito caros e próximos do vencimento.
    Estava em São Paulo a negócios e não consegui o que queria.
    O calor em Belo Horizonte estava agradável, assim como a comida servida no Mercado Central.
    Fui a praia com a namorada e mais uns amigos e estava insuportável de lotado.
    Ganhei um smartphone de aniversário, e o aparelho é perfeito.
    A pizza de queijo da Padaria Imperial é sensacional de boa.
    Recife Antigo é um dos melhores lugares para curtir o final de semana.
    A Igreja do Monte dos Guararapes é uma das mais antigas do Brasil.
    Festa Junina é melhor que Carnaval.
    Ouvir música em ótimos fones de ouvido é uma sensação bastante satisfatória.

###### 6.1. Segue abaixo os prints dos Outputs gerados:

![Output 1](https://github.com/dmtz1989/analiseSentimentosIAdio/blob/main/Output/Output%201.png)

![Output 2](https://github.com/dmtz1989/analiseSentimentosIAdio/blob/main/Output/Output%202.png)

![Output 3](https://github.com/dmtz1989/analiseSentimentosIAdio/blob/main/Output/Output%203.png)

![Output 4](https://github.com/dmtz1989/analiseSentimentosIAdio/blob/main/Output/Output%204.png)

![Output 5](https://github.com/dmtz1989/analiseSentimentosIAdio/blob/main/Output/Output%205.png)

![Output 6](https://github.com/dmtz1989/analiseSentimentosIAdio/blob/main/Output/Output%206.png)

![Output 7](https://github.com/dmtz1989/analiseSentimentosIAdio/blob/main/Output/Output%207.png)

###### 7. Análise de Sentimentos feita, percebo que dependendo da setença usada, a IA detecta que pode ser usada a mesma avaliação para alvos distintos. Também detectei que em algumas setenças, não houve marcações, porém a mesma detectou com exatidão que as mesmas se tratavam de setenças com sentimentos negativos.

###### 8. Após o término nas análises, foi realizada a remoção da Workspace e do Resource Group, para evitar gastos excedentes.
