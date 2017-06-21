README.
## <center> Reprodutibilidade em Pesquisa Computacional
### Projeto da Disciplina IA369Z_2017S1 -Faculdade de Engenharia Elétrica e de Computação Unicamp </center>

Este README é composto de:
- Instruções de Instalação;
- Instruções de Configuração;
- Informações sobre a versão de software;
- Licenças;
- Organização do GitHub.
- Instalação da Máquina Virtual

 ** -----------------------------

## 1. Instruções de Instalação:
 
 ### Instalação do Jupyter Notebook:

* NO MICROSOFT WINDOWS (Instalação em bare metal): Baixar do site do Jupyter em jupyter.org.
O pacote utilizado para o teste foi o Anaconda3-4.3.1-Windows-x86_64.exe. Faça a instalação padrão para qualquer Windows. Após a instalação será mostrada no menu iniciar um link para aplicativa chamado "Anaconda3 64bit", escolha a opção Jupyter Notebook. 
Ao clicar no ícone aparecerá a tela de execução e após automaticamente será aberto em navegador web padrão para a aplicação Notebook. 

* LINUX (Instalação em Máquina Virtual): Baixar do site do https://www.virtualbox.org e https://www.centos.org/download. 
Os pacotes utilizados para os testes foram VirtualBox-5.1.18-114002-Win.exe (máquina virtual) e CentOS-7-x86_64-DVD-1611.iso (Sistema Operacional Linux).
A instalação do hipervisor Virtualbox foi no Sistema Operacional Microsoft Windows 7 Professional com service pack 1.
Faça a instalação padrão para qualquer Windows. Após a instalação será mostrada no menu iniciar um link para aplicativa chamado "Oracle VM VirtualBox" escolha a opção Oracle VM Virtualbox.

 ## 2. Instruções de Configuração; 
 
Especificação da Máquina Virtual: 
  Nome: Centos, Versão: Red Hat (64-bit), Memória Base: 1024MB, 
  Processador: 4 vCPU (Intel I5-2400 3.4Ghz), Armazenamento (VMDK): 30,31GB em tamanho fixo,
  Virtualização de Hardware: VT-x, Ordem de boot: Disco Ótico, Disco Rígido e Rede,
  Local de Instalação: D:\VirtualMachines\           

 ### --- No Jupyter Notebook

O jupyter notebook foi testado em dois ambientes: Windows e Linux com as seguintes especificações:

- Microsoft Windows 7 Professional com service pack 1
  Instalação padrão do Windows, através de duplo clique no pacote executável. Permite a escolha o diretório de instalação.   

- Linux CentOS Linux release 7.3.1611 (Core)
   Fácil de instalar utilizando anaconda. Pode ser instalado também pelo gerenciador de instalação de pacotes yum: #> yum install anaconda.

## 3. Informações sobre a versão de software. 
  
- Anaconda3-4.3.1-Windows-x86_64.exe;
- VirtualBox-5.1.18-114002-Win.exe;
- CentOS-7-x86_64-DVD-1611.iso;
- Microsoft Windows 7 Professional em Português;
  
## 4. Licenças
  Leia em LICENSE.
 
## 5. Organização do GitHub.
 
 A estrutura de diretórios estão organizada da seguinte forma:

- /data --> dataset e informações necessárias para o funcionamento do projeto;
- /deliver --> diretório destinado para entrega dos notebooks;
- /dev --> diretório de desenvolvimento;
- /figures --> diretório de figuras e imagens do projeto.

## 6. Instalação da Máquina Virtual

Para este projeto foi criado uma máquina virtual com todos os softwares utilizado e seus notebooks. Veja em README-VM.md

## 7. Para realizar suas reprodutividade
Os parâmetros que podem ser alterados para os testes são as fontes de dados no diretório /data, notebooks: dc_hyperscale.csv
dc_ip_traffic.csv

## 8. Entrega dos notebooks
Os notebooks destinados para a entrega da disciplina estão localizados no diretório /deliver
