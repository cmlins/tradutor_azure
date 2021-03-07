Para executar esse projeto é necessário:

1) Ativar o ambiente virtual
``.\Scripts\activate``

2) Instalar as bibliotecas necessárias e dependências
``pip install -r requirements.txt``

3) Seguir as orientações a seguir para obter os dados e preencher o arquivo '.env'
https://docs.microsoft.com/pt-br/learn/modules/python-flask-build-ai-web-app/5-exercise-create-translator-service

4) Arquivo .env:
``KEY=your_key
ENDPOINT=your_endpoint
LOCATION=your_location``

5) Em app.py adicionar o import ``request``
``from flask import Flask, render_template, request``

6) Para executar, use o comando:
``flask run``

