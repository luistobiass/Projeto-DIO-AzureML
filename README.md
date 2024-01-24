# Projeto-DIO-AzureML
Repositório dedicado à entrega do projeto de Machine Learning na plataforma DIO

Este projeto representa a implementação de um modelo encarregado de realizar a previsão dos aluguéis de bicicletas utilizando a amplamente reconhecida base de dados daily-bike-share.csv.

!["dio_logo"](https://www.ifsc.edu.br/documents/1035121/2170426/dio.png/ab47310a-b7a6-49d2-b3c1-72e88a7c99ed?t=1625144670996)

## Passo a passo do projeto

### Dentro da ferramenta ML automatizado
- Definido nome do trabalho, experimento e descrição.
- Selecionado o tipo de tarefa à ser realizado (Regressão).
- Criado uma nova base de dados tabular do arquivo [daily-bike-share.csv](https://raw.githubusercontent.com/MicrosoftDocs/mslearn-aml-labs/master/data/daily-bike-share.csv)
- Definido a coluna de destino (Rentals).
- Definido o tipo de validação (Divisão de validação de treinamento 10%).
- Definido também os dados de teste (Divisão de teste de treinamento 10%).
- Selecionado os modelos RandomForest e LightGBM
- Máximo de avaliações, avaliações simultâneas e nós definidos (3)
- Limite da pontuação da métrica definido (0.085)
- Tempo limite do experimento e iteração definido (15)
- Encerramento antecipado habilitado
- O tamanho da maquina virtual foi definido como **Standard_D3_v2 (4 núcleo(s), 14GB de RAM, 200 GB de armazenamento)** com somente uma instância.
