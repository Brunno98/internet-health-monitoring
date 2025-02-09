## Como rodar o projeto?

Basta executar o comando `docker compose up -d` e depois acessar o grafana em `localhost:3000`.

Ao logar pela primeira vez, entre com as credencias usernam: admin e password: admin.

Será solicitado para criar uma nova senha, depois disso você terá acesso ao grafana.

## Grafana

As configurações do datasource do prometheus e o dashboard do blackbox exporter estão armazendas na pasta [grafana/](grafana/)

Quando o docker-compose subir o conteiner do grafana, esses arquivos de configuração irão para a pasta `/etc/grafana/provisioning` do container e o grafana irá carregar o datasource do prometheus e dashboard do blackbox automaticamente.