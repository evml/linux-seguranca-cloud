# Permissões aplicadas

## Ambiente utilizado

VM local Ubuntu 26.04 executada através do Virt-Manager sobre WSL2.

## Utilizador e grupos

Os comandos whoami, id e groups foram utilizados para identificar o utilizador autenticado e os grupos aos quais pertence.

## Ficheiros criados

* publico.txt
* restrito.txt
* script.sh

## Permissões aplicadas

| Ficheiro     | Permissão | Justificação                                                 |
| ------------ | --------- | ------------------------------------------------------------ |
| publico.txt  | 644       | Permite leitura para todos e escrita apenas ao proprietário. |
| restrito.txt | 640       | Permite leitura apenas ao proprietário e grupo.              |
| script.sh    | u+x       | Permite execução apenas ao proprietário.                     |

## Relação com o princípio do menor privilégio

As permissões foram atribuídas apenas aos utilizadores que necessitam de acesso aos ficheiros. Desta forma reduz-se o risco de alterações não autorizadas e aumenta-se a segurança do sistema. A utilização de permissões específicas é mais adequada do que conceder acesso total a todos os utilizadores.
