# Empréstimo de Equipamentos (Empresta Fácil)
Sistema para gerenciamento de empréstimos de equipamentos

1.	### DESCRIÇÃO DO SISTEMA DE EMPRÉSTIMO

O Sistema de Empréstimo tem como objetivo criar um gerenciador de empréstimos para equipamentos, exemplo: notebook, Datashow, caixa de som. A princípio será utilizado somente em ambiente empresarial público ou privado.

Imagine o cenário em que uma empresa dispões de uma certa quantidade de equipamentos para uso por qualquer colaborador. O gerenciador de empréstimo deve ser capaz de informar quais os equipamentos disponíveis para empréstimos e quais datas estão sem agendamentos. Não permitir problemas como um único equipamento ser agendado para mesma data e hora para colaboradores diferentes.
 
O notebook deve ter as informações de suas características cadastradas no sistema como marca, modelo, processador, memória RAM, disco rígido, placa vídeo, tamanho da tela, mouse com fio ou sem fio.

A caixa de som deve ter características como marca, modelo, potência, Bluetooth, USB, voltagem, entrada P10, entrada P2.

O Datashow deve ter as seguintes características cadastradas no sistema: marca, modelo, entrada VGA, entrada HDMI, voltagem e resolução.

Para todos os equipamentos deve haver o status de disponível ou não para agendamento.

O sistema deve conter dois tipos de usuário: Administrador e Comum. O usuário Administrador deve ter todos os privilégios do sistema. O usuário comum poderá apenas registrar seus empréstimos, consultas e gerir seu perfil. Os dados para cadastrar um usuário devem ser nome completo, CPF, matrícula interna, e-mail, telefone celular, senha.

É necessário que o sistema disponibilize comprovante virtual de empréstimo (agendamento, retirada e devolução) e com possibilidade de impressão. 
O agendamento deve seguir as seguintes condições: solicitar com no mínimo 1h de antecedência, informar a finalidade, quais e a quantidade de equipamentos, data de retirada e devolução e status (aguardando retirada, cancelado, em andamento, vistoria de devolução ou encerrado).

Para a retirada será necessária a confirmação do administrador do sistema e do solicitante através de login e senha. A carência para retirada será de 30min, após esse prazo os equipamentos voltarão a estar disponíveis para agendamento.

A devolução deve ocorrer a mesma confirmação através de login e senha pelo administrador do sistema e do usuário solicitante. Porém haverá conferência dos equipamentos e se houver ocorrência ela será registrada no processo de empréstimo e repassada para o solicitante as medidas que devem ser tomadas.

2.	### FUNCIOALIDADES BÁSICAS
    1.	;
    2.	;
    3.	;

3.	### FUNCIOALIDADES FUTURAS
    1.	Ter a possibilidade de registrar ocorrências com os equipamentos emprestados durante o empréstimo pelo usuário responsável;
    2.	Notificação para lembretes de retirada, devoluções;
    3.	Emitir relatórios de todas as movimentações ocorridas no sistema;


4.	REQUISITOS FUNCIONAIS (RF) E NÃO FUNCIONAIS (RNF)

#### REQUISITOS FUNCIONAIS (RF)

RF | DESCRIÇÃO
---|--- 
RF 01 |	Usuário com perfil administrador deve realizar CRUD equipamento.
RF 02 |	Usuário com perfil administrador deve realizar CRUD usuário comum.
RF 03 |	Usuário com perfil administrador deve realizar CRUD agendamento.
RF 04 |	Usuário com perfil comum deve apenas gerir seu perfil.
RF 05 |	Usuário com perfil comum deve cadastrar agendar equipamentos.
RF 04 |	Usuário com perfil comum deve cancelar agendamento.
RF 05 |	O sistema deve permitir fazer login com CPF.

#### REQUISITOS NÃO FUNCIONAIS (RNF) 

RNF | DESCRIÇÃO
---|---
RNF 01 | O sistema deve ser mobile e web
RNF 02 | O sistema deve ter o banco em nuvem
RNF 03 | Será utilizado criptografia para autenticação JWT
 
 

