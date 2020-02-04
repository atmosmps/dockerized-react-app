This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

*Este repositório foi criado, como teste para o artigo: [Dockerizando uma aplicação React JS](https://medium.com/@atmosmps/dockerizando-uma-aplica%C3%A7%C3%A3o-react-js-f6a22e93bc5d)*. Veja o artigo para mais informações.


Este repositório contém um script que foi criado para facilitar a conteinerização e deploy de uma aplicação frontend com React usando o Docker. O script está no arquivo: `run-app-deploy.sh`. Você pode copiar este arquivo e modifica-lo de acordo com sua necessidade.

Para levantar containers preparados para desenvolvimento utilize:

```./run-app-deploy.sh --dev```

Para levantar containers preparados para produção utilize:

```./run-app-deploy.sh --prod```

p.s: se você tiver problemas para executar o arquivo ```run-app-deploy.sh``` execute o seguinte comando:

```chmod +x run-app-deploy.sh```

Sugestões são bem vindas :)
