# Robô (aranha) Quotes
Projeto criado para o curso de Recuperação de Informação na Web e em Redes Sociais do Mackenzie. Para todar esse código é preciso ter o scrapy instalado na sua maquina. 

## Para instalar o scrapy:

Execute a instalação diretamente pelo PIP pelo comando abaixo

```
pip install scrapy
```

## Executando a aranha

Uma vez instalada, acenda ao diretório robo_aj e execute o comando:

``` 
scrapy crawl quotes_spider 
``` 

O scrapy permite que você salve o resultado em outros formados, diretamente no comando de linha. para isso, basta incluir ```-O``` seguido do nome do arquivo e extensão. São aceitos ```.csv```, ```.json``` e ```.jl``` (JSONLine). Exemplo:

``` 
scrapy crawl quotes_spider -O quotes.jl 
``` 

Consulte a documentação do scrapy para outros comandos.

## Alteração do código

Para alterar a aranha, vocÊ deve mexer no arquivo [quotes_spider.py](quotes/spiders/quotes_spider.py). Não é necessário mexer nos demais arquivos. Os links com os textos do Arnaldo Jabor no jornal o tempo estão ja pre carregados [neste html](arnaldo_jabor.html)
