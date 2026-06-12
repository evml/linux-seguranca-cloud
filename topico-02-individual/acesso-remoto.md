# Acesso remoto e chaves SSH

## Diferença entre autenticação por palavra-passe e autenticação por chave

A autenticação por palavra-passe exige que o utilizador introduza uma palavra-passe para aceder ao servidor.

A autenticação por chave SSH utiliza um par de chaves criptográficas (pública e privada), sendo mais segura e resistente a ataques de força bruta.

## Chave pública

A chave pública foi gerada através do comando ssh-keygen.

Ficheiro:

~/.ssh/id_ed25519.pub

## Chave privada

A chave privada foi gerada através do comando ssh-keygen.

Ficheiro:

~/.ssh/id_ed25519

## Cuidados de segurança

* Nunca divulgar a chave privada.
* Utilizar frases-passe fortes.
* Manter permissões adequadas na pasta .ssh.
* Efetuar cópias de segurança seguras das chaves.

## Evidência segura

Foi gerado um par de chaves SSH através do comando ssh-keygen.

Por razões de segurança, o conteúdo da chave privada não foi incluído nesta documentação.


## Evidência da geração de chaves

Foi executado o comando:

ssh-keygen

Verificação realizada através de:

ls -l ~/.ssh

Ficheiros identificados:

- id_ed25519
- id_ed25519.pub
