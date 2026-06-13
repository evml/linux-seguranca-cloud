# Hardening inicial

## Serviço analisado

Nginx

## Riscos específicos

* Exposição de informações do servidor.
* Configurações incorretas de permissões.
* Serviços desnecessários ativos.
* Software desatualizado.

## Medidas aplicáveis imediatamente

* Atualizar pacotes do sistema.
* Utilizar firewall UFW.
* Manter apenas portas necessárias abertas.
* Rever permissões dos ficheiros publicados.
* Utilizar utilizadores sem privilégios administrativos para tarefas normais.

## Medidas para tópicos seguintes

* Configurar HTTPS.
* Ocultar versão do Nginx.
* Implementar monitorização.
* Implementar backups automáticos.
* Definir plano de continuidade operacional.
