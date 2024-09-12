# VM Setup Automação

## Sobre
Este projeto automatiza a configuração de uma máquina virtual (VM) com todas as ferramentas e softwares necessários para que um desenvolvedor inicie um novo projeto de maneira rápida e eficiente. A automação é realizada utilizando **Ansible** ou **Terraform**, garantindo que o ambiente seja configurado de forma consistente e com os padrões desejados.

## Features
- Instalação automática de pacotes essenciais (Git, Docker, etc.)
- Configuração de linguagens e frameworks de desenvolvimento (Python, Node.js, etc.)
- Configuração de ambientes de banco de dados
- Suporte para provisionamento em diferentes provedores de nuvem ou localmente
- Flexível para ajustes conforme as necessidades do projeto

## Ferramentas usadas
- **Ansible** ou **Terraform**: para provisionar e configurar a VM
- **Shell Scripts**: para customizações adicionais
- **Cloud Provider**: opcional, para rodar em AWS, Azure, etc.

## Setup

### Usando Ansible:
1. Clone este repositório:
   ```bash
   git clone https://github.com/seuusuario/vm-setup.git
   cd vm-setup
   ```

2. Execute o playbook do Ansible:
```bash
ansible-playbook setup.yml
```
3. Usando Terraform:
1. Clone este repositório:
```bash
git clone https://github.com/seuusuario/vm-setup.git
cd vm-setup
```
2. Inicie o Terraform:
```bash
terraform init
terraform apply
```

## Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.
