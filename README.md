# InstallBaseDesktop - Ansible Linux deb

Automação da preparação de um ambiente desktop Linux utilizando **Ansible**.

Este projeto foi criado com objetivo de automatizar a configuração inicial de uma máquina, reduzindo o trabalho manual após uma instalação do sistema operacional.

A ideia é transformar uma instalação "limpa" em um ambiente pronto para uso pessoal e desenvolvimento, instalando ferramentas essenciais, aplicativos e componentes utilizados no meu dia a dia.

---

## Objetivo

Automatizar:

- Atualização do sistema
- Instalação de ferramentas básicas
- Instalação do Google Chrome
- Configuração do Docker
- Instalação do Kubernetes CLI (`kubectl`)
- Instalação do Kind (Kubernetes local)
- Instalação de aplicativos via Snap

---

# Tecnologias utilizadas

- Ansible
- Snap
- Linux Mint / Ubuntu

---

# Requisitos

Antes de executar, certifique-se que possui:

- Linux Mint ou distribuição baseada em Debian/Ubuntu
- Python instalado
- Ansible instalado
- Acesso root

Instalação do Ansible:

```yaml
sudo apt update

sudo apt install ansible -y
```

Execução do playbook:

```yaml
ansible-playbook  InstallBaseDesktop.yml
```
