# GestaoClinicaOdontologicaSQL


GRUPO 3: Claudiane Sutil, Giselle Pontes, José Arthur F, Lucas Perrin, Pedro Falco, Samuel Alves, Simone Gomes


Criação de um banco de dados para uma cínica odontológica fictícia para a disciplina de Banco de Dados da Residência TIC/Software do Serratec 2025.2.

REQUISITOS:

Projeto: Sistema de Gestão para Clínica Odontológica
Uma clínica odontológica deseja informatizar o seu atendimento e gestão de pacientes. O sistema a ser desenvolvido precisa permitir o agendamento de consultas, registro de atendimentos e controle de profissionais e pacientes. O sistema não incluirá funcionalidades para gestão financeira ou faturamento.
Requisitos Funcionais:
•
O sistema deve ser capaz de armazenar informações sobre os pacientes, incluindo: id, nome completo, CPF, data de nascimento, telefone, e-mail, endereço e histórico de consultas.
•
Os pacientes devem poder agendar consultas, escolhendo um dentista e um horário disponível.
•
As consultas devem ser registradas no sistema com as seguintes informações: id, paciente, dentista responsável, data e horário da consulta, descrição do atendimento e prescrição (caso aplicável).
•
O sistema deve permitir a atualização ou cancelamento de consultas, respeitando regras de prazo mínimo para alterações.
•
Sobre os dentistas, o sistema deve armazenar: id, nome completo, CPF, CRO (registro profissional), especialidade e horário de atendimento.
•
Cada dentista pode ter um ou mais horários de atendimento cadastrados no sistema, respeitando sua agenda.
•
O sistema deve armazenar os procedimentos odontológicos oferecidos pela clínica, com as seguintes informações: id, nome, descrição e duração média.
•
Cada consulta pode incluir um ou mais procedimentos odontológicos realizados.
•
O sistema deve permitir que os atendentes da clínica acessem e atualizem os dados dos pacientes, consultas e dentistas.
Requisitos Não Funcionais:
•
Deve ser criado um modelo conceitual, um lógico e um físico;
•
Deve ser inserido, um mínimo de, 10 registros em cada tabela (INSERT);
•
SQL de dois índices coerentes;
• SQL de 3 atualizações de registros com condições em alguma tabela.
• SQL de 3 exclusão de registros com condições em alguma tabela.
• Cinco consultas contextualizadas:
o 1ª - Quantidade de consultas por especialidade: selecione todas as especialidades
dos dentistas e faça um COUNT para contar o número total de consultas realizadas por
cada especialidade.
o 2ª - Quantidade de consultas realizadas por cada dentista: selecione o nome de todos
os dentistas e faça um COUNT para contar a quantidade de consultas realizadas por
cada um e exiba em ordem decrescente pela quantidade de consultas.
o 3ª - Pacientes com maior número de consultas: liste os pacientes e a quantidade de
consultas que cada um realizou, ordenando em ordem decrescente pelo número de
consultas.
o 4ª - View com lista de consultas ordenadas por data: crie uma VIEW que selecione os
seguintes campos: id_consulta, nome_paciente, nome_dentista, data_consulta,
procedimentos_realizados e ordene em ordem decrescente pela data da consulta.
o 5ª - Média de consultas por dentista: calcule a média de consultas realizadas por
dentista.
• Todos os comandos devem ser salvos em um único script com comentários de separação;
• Crie um repositório individual no GitHub e preencha o README com uma contextualização (um
parágrafo) do cenário onde se poderia aplicar essa modelagem (por exemplo, uma loja virtual
de vestuário que...), insira os prints dos modelos conceitual e lógico e o script completo com os
comandos SQL.
