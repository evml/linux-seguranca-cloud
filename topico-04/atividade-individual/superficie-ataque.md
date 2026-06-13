# Superfície de ataque

## Serviço publicado

Nginx

## Serviços ativos identificados

* SSH
* Nginx

## Portas observadas

* 22/TCP - SSH
* 80/TCP - HTTP

## Portas necessárias

| Porta | Serviço | Justificação                     |
| ----- | ------- | -------------------------------- |
| 22    | SSH     | Administração remota do servidor |
| 80    | HTTP    | Publicação do serviço web        |

## Riscos iniciais identificados

1. Acesso SSH com palavras-passe fracas.
2. Exposição desnecessária de portas não utilizadas.
3. Falta de atualização dos pacotes do sistema.
4. Configuração incorreta de permissões em ficheiros.
5. Divulgação de informações do servidor web.



