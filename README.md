## Instruções

O diretorio docker serve como volume para os arquivos de instalação do jenkins, para que em caso de "reinicio" da docker não se perca tudo e precise efetuar todos os downloads novamente

O diretorio scripts serve como volume para scripts que o jenkins precise executar


### Iniciando 

```bash
sudo docker-compose build
sudo docker-compose up -d
```

###  [Exemplo de uso do jenkis para execução de CRON](https://blog.migracloud.com/usando-o-jenkins-para-criar-agendamentos-cron/)

Parametros do CRON

0 (Minuto) | 23 (hora) | * (Todos os dias) | * (Todos os meses) | * (Todos os dias da semana)

