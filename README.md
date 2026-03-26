# RESET-DE-SENHA-DO-USU-RIO-NO-ACTIVE-DIRECTORY
RESET DE SENHA DO USUÁRIO NO ACTIVE DIRECTORY
Este Processo permite que você crie um fluxo para o reset de senha dos usuários da rede.

Sobre este fluxo de automação:
Em média reset de senha representa entre 15% a 30% do volume de chamados que um service desk tem que resolver mensalmente.

Este Workflow permite a criação de um serviço para o Reset de Senhas dos usuários pelo Active Directory.
Nessa etapa validamos se o usuário existe, caso ele existe coletamos alguns dados do AD como:
– UPN, PO, St, Mail, Manager Mail

Depois validamos se o CPF / RG informado como entrada no processo  e igual ao CPF e RG que estão registrados no AD.
Nesse robô usamos os parametros do AD como Street, PO Box, mas caso na sua rede sejam outros parâmetros, você pode modificar o fluxo para atender sua necessidade.<img width="275" height="215" alt="image" src="https://github.com/user-attachments/assets/2ec5fbf4-ca52-4e29-83f7-d046b46cc992" />
