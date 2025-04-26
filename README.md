# Criação de Máquina Virtual no Microsoft Azure

Este repositório foi criado como parte do desafio da DIO para praticar a criação e configuração de uma máquina virtual no Microsoft Azure.

## 📌 Objetivo

- Praticar a criação de máquinas virtuais no Azure.
- Registrar os passos, dicas e boas práticas.
- Utilizar o GitHub para documentar e compartilhar o aprendizado.

## 🚀 Passos Realizados

1. Acesso ao portal [Microsoft Azure](https://portal.azure.com).
2. Criação de um novo recurso: **Máquina Virtual**.
3. Preenchimento dos dados principais:
   - **Nome da VM:** exemplo-vm
   - **Sistema Operacional:** Windows Server 2019 ou Ubuntu.
   - **Tamanho:** B1s (uso gratuito ou baixo custo).
   - **Usuário e Senha** para login.
4. Configuração da rede e abertura de portas (RDP para Windows, SSH para Linux).
5. Revisão de configurações e criação da VM.
6. Acesso à VM criada via RDP ou SSH.

## 💡 Dicas e Anotações

- **Grupo de Recursos:** Use sempre para organizar melhor seus serviços.
- **Regra de Firewall:** Libere apenas as portas necessárias (ex.: 3389 para RDP, 22 para SSH).
- **Cuidado com Custos:** Pare ou exclua a máquina virtual quando não estiver em uso.
- **Snapshots:** Faça snapshots antes de grandes alterações.

## 🖼️ Capturas de Tela

Exemplo da criação de uma máquina virtual no portal do Azure:

![Criação da Máquina Virtual no Azure](./images/Imagem%20github-azure.png)

## 📚 Referências

- [Documentação Oficial Azure - Criar VM Windows](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal)
- [GitHub Markdown Guide](https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github)
