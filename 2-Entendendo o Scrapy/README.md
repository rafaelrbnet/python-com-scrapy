## Dicas de instalação do Scrapy no Windows
Fazer o download od arquivo Twisted-18.9.0-cp36-cp36m-win32.whl
pip install Twisted-18.9.0-cp36-cp36m-win32.whl
pip install pypiwin32
pip isntall scrapy

## Comandos Scrapy

Executa um arquivo scrapy
    scrapy runspider aula02.py

Criando o projeto
    scrapy startproject courses
    cria a estrutura básica do projeto

Criando uma spider dentro do projeto
    scrapy genspider coursera https://pt.coursera.org/

Executando a Spider
    scrapy crawl coursera