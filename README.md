# azure_vm_whith_remote_state

Este projeto é um exemplo de como criar uma máquina virtual Linux no Azure utilizando o Terraform com armazenamento de estado remoto. A estrutura do projeto inclui:

- Resource group: grupo de recursos do Azure onde a VM será criada.
- Public IP: endereço IP público para acesso à VM.
- Network Interface: interface de rede da VM.
- Network Interface security Group Association: regras de segurança para a interface de rede.
- Linux Virtual machine: a própria máquina virtual Linux.

## Configuração de estado remoto

Este projeto utiliza armazenamento de estado remoto para gerenciar o estado do Terraform. Para configurar o armazenamento de estado remoto, siga as instruções aqui.

## Aviso

Este projeto cria recursos no Azure que podem incorrer em custos. Certifique-se de excluir os recursos criados quando não precisar mais deles.
