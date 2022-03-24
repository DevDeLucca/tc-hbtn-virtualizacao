------------------------------------------------------------------------------------------------------
- Apresente uma solução de como deve ser a criação de uma máquina virtual no Hyper-V
------------------------------------------------------------------------------------------------------
- Habilitar o Hyper-V usando o PowerShell -

- Abra um console do PowerShell como Administrador.
- Considerado como boa pratica executar o comando Windows Update, para verificação se a maquina esta atualizada
- Execute o comando a seguir:
Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V -All


1 Abra a Criação Rápida do Hyper-V no menu iniciar

2 Escolha o sistema operacional de sua preferencia, ou escolha o seu proprio.
   A Caso Escolha sua propria origem de instalação selecione "Origem de instalaçao Local".
   B Selcionar "Alterar origem de instação".
   C Escolha o .ISO ou .VHDX que ira trasformar a nova maquina virtual.
   D Se a imagem foi Linux desmarque a opção inicialização segura.

3 Selecione "Criar maquina Virtual" 
-------------------------------------------------------------------------------------------------------
- Demosntração de o porque essa pratica e considerada um hipervisor do tipo 02
-------------------------------------------------------------------------------------------------------
O hipervisor tipo 2, tambem conhecido como hosted, e a execução de um sistema operãcional convencional
como as camadas de softwares e aplicação, contain Server Manager

- A VM roda sobre um Sistema operacional host, sendo assim pode se considerar um hypervisor tipo 2


-------------------------------------------------------------------------------------------------------
- Realize uma nova pesquisa para configuração do Servidor Físico, levando em consideração que o artigo 
é de 2011, qual a configuração ideal para um servidor suportar três máquinas virtuais dos mesmos 
tipos apresentados no artigo.
-------------------------------------------------------------------------------------------------------
Em geral um hardware ja considerado defazad pelo tempo,se faz necessario upgrade, para apresentação 
de melhor performance, em acordo com as necessidade de um novo servidor, sendo tabme necessario as 
adequações necessarias em relação a Disco rigido, memoria RAM do tamanho da memoria RAM 
e tambem do disco rigido

