# Virtualização com Ubuntu Server

Este repositório tem como objetivo fornecer um guia para criar uma máquina virtual Ubuntu utilizando o sistema operacional Windows e a ferramenta de virtualização Hyper-V.

## Conceitos Fundamentais

### Virtualização

A [virtualização](https://azure.microsoft.com/pt-br/resources/cloud-computing-dictionary/what-is-virtualization/#:~:text=A%20virtualiza%C3%A7%C3%A3o%20cria%20um%20ambiente%20de%20computa%C3%A7%C3%A3o%20simulado,computador%20f%C3%ADsico%20ou%20servidor%20em%20diversas%20m%C3%A1quinas%20virtuais.) cria um ambiente de computação simulado, permitindo que múltiplos sistemas operacionais funcionem em um único computador físico.

### Hyper-V

O [Hyper-V](https://learn.microsoft.com/pt-br/virtualization/hyper-v-on-windows/about/) é uma tecnologia de virtualização desenvolvida pela Microsoft que permite criar e gerenciar máquinas virtuais em sistemas Windows.

### Sistemas Operacionais

Um [sistema operacional](https://tecnoblog.net/responde/o-que-e-um-sistema-operacional/) é um conjunto de programas responsável por gerenciar os recursos do computador e fornecer uma interface entre o hardware e o usuário.

### Ubuntu Server

O [Ubuntu Server](https://tecnoguia.istocks.club/ubuntu-desktop-vs-ubuntu-server-qual-e-a-diferenca/2021-03-12/) é uma versão do sistema operacional Ubuntu otimizada para uso em servidores, oferecendo estabilidade e segurança.

## Instalação do Hyper-V

O Hyper-V é instalado a partir dos recursos do Windows. Siga estes passos:

1. Acesse o Painel de Controle.
2. Clique em "Programas".
3. Selecione "Ativar ou desativar recursos do Windows".
4. Marque as opções relacionadas ao Hyper-V.
5. Reinicie o Windows para concluir a instalação.

![Hyper-V Installation](https://github.com/CarlosJuncher03/Virtual_ubuntu/assets/145303814/f14d2df4-8269-4879-ace6-9380f2f4aee2)

## Download da ISO Ubuntu Server

1. Faça o download da ISO do [Ubuntu Server](https://releases.ubuntu.com/20.04/).

![Download Ubuntu Server ISO](https://github.com/CarlosJuncher03/Virtual_ubuntu/assets/145303814/a4882ae4-2389-4c4d-a977-b18a01ae12ae)

## Criando uma Nova Máquina Virtual

O processo para criar uma nova máquina virtual é simples:

1. Acesse o Hyper-V e clique em "Criar uma Máquina Virtual".

![Criar Máquina Virtual](https://github.com/CarlosJuncher03/Virtual_ubuntu/assets/145303814/7de90727-d78c-4a51-b125-35ceac933faf)

2. Siga as etapas fornecidas, como definir o nome da máquina, especificar a geração, definir o tamanho da memória, escolher o adaptador de rede e o tamanho do armazenamento.

![Configuração da Máquina Virtual](https://github.com/CarlosJuncher03/Virtual_ubuntu/assets/145303814/d207c5a1-718c-4bf6-80c0-449cbc3b67f8)

3. Selecione a ISO do Ubuntu Server baixada anteriormente.

![Selecionar ISO](https://github.com/CarlosJuncher03/Virtual_ubuntu/assets/145303814/63a98620-849e-42d6-b21b-2be3ad4ac69c)

4. Finalize e inicie a máquina virtual.

Após isso, você pode realizar as configurações adicionais conforme necessário.
