# Dados Falsos Gerados Automaticamente
>Este repositório contém um script Python que gera dados falsos de pessoas utilizando a biblioteca faker e os salva em um arquivo Excel. É útil para testes, simulações e outros cenários onde dados fictícios são necessários.

## Requisitos
Python 3.x
Bibliotecas Python: faker, pandas

## Execute
git clone https://github.com/gregorygustavo80/fake_data.git
#### pip install faker pandas

## Como usar
Clone este repositório ou baixe o script fake_data.py.
Certifique-se de ter os requisitos instalados.
Execute o script Python fake_data.py.
Um arquivo Excel chamado dados_fake.xlsx será gerado no mesmo diretório do script, contendo os dados falsos.

## Personalização
### Edite aqui a quantidade de dados gerados

### faker import Faker
import pandas as pd

fake = Faker('pt_BR')
num_registros = 100  

dados_fake = []

Você pode personalizar os tipos de dados e a quantidade de registros modificando o script fake_data.py. Consulte a documentação da biblioteca Faker para mais opções de geração de dados.

## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests para melhorar este script.

