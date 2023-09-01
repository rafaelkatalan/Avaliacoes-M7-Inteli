# Avaliacoes-M7-Inteli
Avaliações do Módulo 7

O dockerfile do backend foi criado de forma que ele usa como imagem base o python, copia os requirements e intala as bibliotecas necessarias citadas no requirements. Ele, então, copia todos os arquivos para dentro do diretorio na imagem e inicializa o app uvicorn.

O dockerfile do frontend foi criado de forma que ele usa como imagem base o node, copia o package.json e intala os requerimentos para executar o frontend. Então, ele copia todos os arquivos para dentro do diretorio na imagem e inicializa o app node.

O docker-compose cria uma imagem para o backend a partir do dockerfile do backend e uma imagem para o frontend a partir do dockerfile do frontend.

Para executar o app, basta rodar no terminal dentro do diretorio da aplicaçãp 'docker-compose up' e acessar o frontend no localhost:3000.

| ***IMPORTANTE:*** Utilizar dentro do contexto do container.