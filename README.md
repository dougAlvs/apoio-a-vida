# Apoio-vida

## Descrição 

Apoio à vida é um projeto que envolve o uso de machine learning para prever a predisposição de uma pessoa estar vulnerável ao suícidio, podendo assim criar medidas preventivas de apoio à vida.

## Como Rodar

Com o Python 3 instalado, basta seguir o passo a passo inicial abaixo para criar um ambiente virtual e instalar as dependências do projeto:

1º - Crie uma venv chamada 'apoio-venv' com o comando 

```
python3 -m venv apoio-venv
```

2º - Ative a venv com o comando:

```
source apoio-venv/bin/activate
```

3º - Com a venv ativada, instale as dependências listadas no requirements.txt do repositório:

```
pip install -r requirements.txt
```

4º - Para rodar os notebooks, adicione o venv ao Jupyter com o seguinte comando:

```
python3 -m ipykernel install --user --name=apoio-venv
```

5º - Para puxar os dados da nuvem basta executar o comando na raiz do repositório e depois se autenticar no Google Drive:

```
dvc pull
```

6º - A visualização dos dados brutos iniciais pode ser realizada executando o notebook visualize_data.ipynb na pasta notebooks.

## Equipe

<table>
  <tr>
    <td align="center"><a href="https://github.com/arthurmlv"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/109696650?v=4" width="100px;" alt=""/><br /><sub><b>Arthur de Melo</b></sub></a><br />
    <td align="center"><a href="https://github.com/dougAlvs"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/98109429?v=4" width="100px;" alt=""/><br /><sub><b>Douglas Alves</b></sub></a><br /><a href="Link git" title="Rocketseat"></a></td>
    <td align="center"><a href="https://github.com/g16c"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/90865675?v=4" width="100px;" alt=""/><br /><sub><b>Gabriel Campello</b></sub></a><br /><a href="Link git" title="Rocketseat"></a></td>
        <td align="center"><a href="https://github.com/manuziny"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/88348637?v=4" width="100px;" alt=""/><br /><sub><b>Geovanna Maciel</b></sub></a><br />
        <td align="center"><a href="https://github.com/bottinolucas"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/101297130?v=4" width="100px;" alt=""/><br /><sub><b>Lucas Bottino</b></sub></a><br />
    <td align="center"><a href="https://github.com/joseluis-rt"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/78660807?v=4" width="100px;" alt=""/><br /><sub><b>José Luís</b></sub></a><br />
  </tr>
</table>
