# AgendaUni

O projeto AgendaUni é produto da disciplina de Análise,Projeto e Implementação de Sistemas do curso de Sistemas de Informação da Unichristus - Semestre 2017.2


## Informaçãoes Iniciais

Você pode encontrar a descrição do projeto em [DescriçÃo do projeto](https://github.com/alinembl/agendauni/blob/master/Projeto%20-%20AgendaUni.pdf)

### Artefatos

Constam no repositório:

* [Descrição dos Casos de Uso](https://github.com/alinembl/agendauni/tree/master/Casos%20de%20Uso)
* [Diagramas](https://github.com/alinembl/agendauni/tree/master/Diagramas) - Casos de uso,DSS e classes conceituais
* [Protótipo Funcional](https://github.com/alinembl/agendauni-django) - Protótipo funcional (em Django) do UC03

### Para funcionamento do protótipo

* download e descompactar o repositório
```
source myvenv/bin/activate
python manage.py runserver
```
* acesse 127.0.0.1:8000
* dados de Acesso

```
login: aline
senha: agendauni
ou
python manage.py createsuperuser no terminal para criar novo usuário
```
* acesso ao painel de admin em 127.0.0.1/admin
