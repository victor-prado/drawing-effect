# drawing-effect
Efeito de ilustração à lápis em imagens.


## Licença
### [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


## Requisitos

Instalação dos requisitos conforme o recomendado em https://jacobian.org/writing/python-environment-2018/

* [pyenv](https://github.com/pyenv/pyenv) ([Common build problems](https://github.com/pyenv/pyenv/wiki/Common-build-problems))
* [pipenv](https://docs.pipenv.org/)


## Instalação

Instale um ambiente isolado e os pacotes necessários através do comando

```sh
$ cd DIRETORIO_DO_PROJETO
$ pipenv install --skip-lock
```

Caso seja necessária a instalação de algum pacote adicional, instale-o através do comando

```sh
$ cd DIRETORIO_DO_PROJETO
$ pipenv install --skip-lock NOME_DO_PACOTE
```

onde `NOME_DO_PACOTE` é o pacote a ser instalado (exemplo: `numpy`)


## Execução

Executar o ambiente do projeto com o comando

```sh
$ cd DIRETORIO_DO_PROJETO
$ pipenv run jupyter notebook implementacao.ipynb
```


## Autores
 * [Cintia Tho](https://github.com/CintiaTho)
 * [Luiz Garcia](https://github.com/luizfmgarcia)
 * [Victor do Prado](https://github.com/victor-prado)
