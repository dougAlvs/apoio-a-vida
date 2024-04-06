# Apoio-vida

## Descrição 

Apoio à vida é um projeto que envolve o uso de machine learning para prever a predisposição de uma pessoa estar vulnerável ao suícidio, podendo assim criar medidas preventivas de apoio à vida.

## Como Rodar

Com o Python 3 instalado, basta seguir o passo a passo inicial abaixo para criar um ambiente virtual e instalar as dependências do projeto:

1º - Crie uma venv chamada 'apoio-venv' com o comando 

```
python -m venv apoio-venv
```

2º - Ative a venv com o comando:

```
source apoio-venv/bin/activate
```

3º - Com a venv ativada, instale as dependências listadas no requirements.txt do repositório:

```
pip install -r requirements.txt
```

4º - Para puxar os dados da nuvem basta executar o comando na raiz do repositório:

```
dvc pull
```

5º - A visualização dos dados brutos iniciais pode ser realizada executando o notebook visualize_data.ipynb na pasta notebooks.