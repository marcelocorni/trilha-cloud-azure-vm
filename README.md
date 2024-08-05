# Guia para Criar Máquinas Virtuais no Microsoft Azure

Este guia fornece um passo a passo básico para criar máquinas virtuais (VMs) no portal do Microsoft Azure.

## Sumário

- [Pré-requisitos](#pré-requisitos)
- [Passo a Passo](#passo-a-passo)
  - [1. Acessar o Portal do Azure](#1-acessar-o-portal-do-azure)
  - [2. Navegar até 'Máquinas Virtuais'](#2-navegar-até-máquinas-virtuais)
  - [3. Criar uma Nova Máquina Virtual](#3-criar-uma-nova-máquina-virtual)
  - [4. Configurar a Máquina Virtual](#4-configurar-a-máquina-virtual)
  - [5. Revisar e Criar](#5-revisar-e-criar)
- [Dicas Adicionais](#dicas-adicionais)
- [Recursos Úteis](#recursos-úteis)

## Pré-requisitos

- Conta ativa no Microsoft Azure.
- Acesso ao portal do Azure ([portal.azure.com](https://portal.azure.com)).
- Permissões necessárias para criar recursos no Azure.

## Passo a Passo

### 1. Acessar o Portal do Azure

1. Abra seu navegador web e vá para [portal.azure.com](https://portal.azure.com).
2. Faça login com suas credenciais da conta Microsoft Azure.

### 2. Navegar até 'Máquinas Virtuais'

1. No painel esquerdo do portal do Azure, clique em **'Máquinas Virtuais'**.
2. Você será redirecionado para a página de gerenciamento de máquinas virtuais.

### 3. Criar uma Nova Máquina Virtual

1. Na página 'Máquinas Virtuais', clique no botão **'Adicionar'** ou **'Criar máquina virtual'**.
2. Você será direcionado para a página de configuração da nova VM.

### 4. Configurar a Máquina Virtual

1. **Informações Básicas**:
   - **Assinatura**: Selecione a assinatura do Azure que será utilizada.
   - **Grupo de Recursos**: Selecione um grupo de recursos existente ou crie um novo.
   - **Nome da VM**: Insira um nome para a máquina virtual.
   - **Região**: Escolha a região onde a VM será hospedada.
   - **Opções de Disponibilidade**: Configure conforme suas necessidades (ex: Conjunto de Disponibilidade ou Zona de Disponibilidade).

2. **Imagem e Tamanho**:
   - **Imagem**: Escolha o sistema operacional e a imagem da VM (ex: Windows Server, Ubuntu, etc.).
   - **Tamanho da VM**: Selecione o tamanho da VM de acordo com a necessidade de recursos (CPU, memória).

3. **Configurações de Administração**:
   - **Nome de Usuário**: Insira o nome de usuário do administrador.
   - **Autenticação**: Escolha entre senha ou chave pública SSH (recomendado para Linux).

4. **Discos**:
   - Configure o tipo e tamanho dos discos (disco do sistema operacional e discos de dados adicionais, se necessário).

5. **Rede**:
   - Configure a rede virtual, sub-rede e outras opções de rede, como IP público e grupos de segurança de rede (NSG).

6. **Gerenciamento, Monitoramento e Outras Configurações**:
   - Configure opções adicionais como diagnósticos de inicialização, monitoramento, identidade gerenciada, etc.

### 5. Revisar e Criar

1. Após configurar todas as opções, clique em **'Revisar e criar'**.
2. Revise todas as configurações na tela de revisão.
3. Se todas as configurações estiverem corretas, clique em **'Criar'**.
4. Aguarde enquanto a VM é provisionada e implantada. Isso pode levar alguns minutos.

## Dicas Adicionais

- Utilize a funcionalidade de modelos do Azure para reutilizar configurações de VMs em novas implantações.
- Verifique a compatibilidade de software e os requisitos de rede antes de escolher uma imagem de VM.
- Utilize tags para organizar e gerenciar melhor os recursos no Azure.

## Recursos Úteis

- [Documentação de Máquinas Virtuais do Azure](https://docs.microsoft.com/pt-br/azure/virtual-machines/)
- [Tutoriais do Azure](https://docs.microsoft.com/pt-br/learn/azure/)
- [Suporte do Azure](https://azure.microsoft.com/pt-br/support/)

