#Indústria de Tempero Regina Ltda
##_Implantação de três máquinas virtuais

###A seguir será demonstrada a sequência de passos para a implantação de 3 máquinas virtuais

###Habilitar hyper-V no Windows Server 2008
Server Manager
Clicar em Start
Administrative Toolss
Clicar em Server Manager
Add Roles
selecionar a opção Hyper-V em Roles
selecionar uma placa de rede para a rede virtual
reiniciar o servidor 
Criar as máquinas virtuais
Acessar Server Manager
Roles
Hyper-V
Hyper-V Manager
Acessar o menu Action - New - Virtual Machine - Wizard
Especificar o nome da VM
Atribuir a quantidade  de memória RAM
selecionar o adaptador de rede virtual
conectar um disco
escolher criar um disco virtual
escolher usar um disco existente
realizar a configuração do sistema operacional
clicar com botão direito na Vm
clicar em Settings
IDE Controller 1, selecione a imagem do Sistema Operacional
Clicar em conectar a VM
Ligar a VM
instalar o sistema operacional

##Hypervisor do tipo 2
Essa prática é considerada um hipervisor do Tipo 2, pois este tipo de arquitetura necessita do sistema operacional para que sejam executadas as máquinas virtuais.Sistema operacional é o host.
