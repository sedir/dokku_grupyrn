# Deploy de aplicações Python para web com Dokku

Apresentação sobre o Dokku para o meetup do GruPy-RN, realizado na UFRN, no dia 02/06/2018.

## Tópicos
 - O que é Dokku
 - Recursos
 - Workflow
 - Demonstração prática com aplicação Python/Flask

## Execução

Toda a apresentação foi criada no Jupyter Notebook com o plugin RISE. Instale as dependências no `Pipfile` ou `requirements.txt` e execute para habilitar o módulo de slides:

```bash
jupyter-nbextension install rise --py --sys-prefix
```

Finalmente, exiba a apresentação com:

```bash
jupyter nbconvert --to slides apresentacao_dokku_grupy.ipynb --post serve
```
