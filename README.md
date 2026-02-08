
# Projeto 02: Administração de Sistemas Abertos

## Equipe e Orientador

- **Equipe:** Bruno de Farias Andrade e Ícaro Machado da Silva
- **Orientador:** Leonidas Francisco de Lima Júnior

## Descrição

Projeto acadêmico desenvolvido para a disciplina Administração de Sistemas Abertos do curso de Redes de Computadores do IFPB. O objetivo é provisionar e configurar um ambiente de serviços usando Vagrant, Ansible e VirtualBox, demonstrando práticas de automação e administração de sistemas.

## Estrutura do projeto

Arquivos e recursos principais:

- `docker-compose.yml` - definição de serviços em contêiner
- `Dockerfile` - imagem Docker personalizada
- `nginx.conf` - configuração do servidor Nginx
- `playbook_ansible.yml` - playbook Ansible para provisionamento
- `requirements.txt` - dependências Python
- `Vagrantfile` - definição da máquina virtual usada no projeto

## Requisitos

Instale as seguintes ferramentas na máquina host antes de executar o projeto:

- VirtualBox
- Vagrant
- Ansible

## Como executar

1. Inicialize a VM com Vagrant:

```
vagrant up
```

2. Após o provisionamento, abra um navegador e acesse a aplicação em:

```
http://192.168.56.180:8080
```

Observação: a máquina Vagrant está configurada para usar o endereço IP `192.168.56.180` na porta `8080`. Caso modifique o `Vagrantfile` ou a rede, ajuste a URL conforme necessário.
