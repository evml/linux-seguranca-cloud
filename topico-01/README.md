# Tópico 1 - Preparação do ambiente Linux

## Ambiente utilizado

VM local Ubuntu 26.04 executada através do Virt-Manager sobre WSL2 no Windows 11.

## Objetivo desta atividade

Preparar o ambiente Linux e organizar a primeira evidência técnica para os trabalhos do módulo.

## Estrutura criada

Foi criada a seguinte estrutura:

linux-seguranca-cloud/

├── topico-01/

│ ├── evidencias/

│ ├── comandos-topico-01.txt

│ └── README.md

└── produto-final/

## Comandos executados

* hostname – identificar o nome da máquina.
* whoami – identificar o utilizador autenticado.
* pwd – mostrar o diretório atual.
* uname -a – obter informações do sistema.
* hostname -I – consultar o endereço IP.
* df -h – verificar utilização do disco.
* free -h – verificar utilização da memória.
* tree – visualizar a estrutura de diretórios.

## Diferença entre VM, VPS e infraestrutura em nuvem

VM (Virtual Machine): máquina virtual criada localmente no computador.

VPS (Virtual Private Server): servidor virtual hospedado num fornecedor externo.

Infraestrutura em nuvem: conjunto de recursos computacionais disponibilizados através da Internet com elevada escalabilidade.

## Dificuldades encontradas

Inicialmente houve dificuldades na comunicação entre Windows, WSL2 e a máquina virtual Ubuntu através de SSH. O problema foi resolvido após a configuração e validação da rede virtual.

## Próximos passos

Preparar o ambiente para configuração de utilizadores, permissões, serviços web e medidas de segurança nos próximos tópicos.
