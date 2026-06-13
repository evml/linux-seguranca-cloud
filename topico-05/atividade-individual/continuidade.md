# Continuidade operacional

## Serviço crítico

Nginx

## Ficheiros críticos

- /var/www/html/topico-03
- Configurações do Nginx
- Conteúdo HTML publicado

## Logs importantes

- journalctl
- Logs do Nginx
- Logs do SSH

## Periodicidade de backup

Semanal

## Procedimento de recuperação

1. Restaurar backup.
2. Validar integridade dos ficheiros.
3. Iniciar ou reiniciar o Nginx.
4. Testar acesso ao serviço.

## Critérios de validação

- Serviço responde em HTTP.
- Conteúdo publicado encontra-se disponível.
- Nginx sem erros.
