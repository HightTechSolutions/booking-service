# Regras de Negócio — Sistema de Agendamento de Aulas de Pilates

1. Somente funcionários cadastrados podem acessar o sistema.
2. Funcionários podem cadastrar, editar ou remover professores e definir seus horários disponíveis.
3. Funcionários podem cadastrar, editar ou remover alunos, incluindo o plano contratado (básico, médio, premium).
4. Funcionários podem configurar os dias e horários de funcionamento da clínica.
5. O sistema oferece três planos:
   - **Plano Básico:** até 1 aula por semana.
   - **Plano Médio:** até 2 aulas por semana.
   - **Plano Premium:** até 3 aulas por semana.
6. O sistema não permite agendar mais aulas do que o limite semanal do plano do aluno.
7. Para cada aula criada, o funcionário deve definir o professor, o horário e o limite máximo de alunos.
8. Não é permitido ultrapassar o limite de alunos definido para cada aula.
9. Caso uma aula esteja lotada, ao tentar agendar um aluno, ele será automaticamente inserido em uma fila de espera.
10. Quando uma vaga for liberada, o primeiro aluno da fila será notificado e alocado automaticamente na aula.
11. Não é permitido agendar dois compromissos para o mesmo professor no mesmo horário.
12. Um aluno não pode ser agendado em duas aulas no mesmo horário.
13. Ao final de cada aula, o professor informa ao funcionário a lista de presença dos alunos.
14. O funcionário registra a presença ou falta de cada aluno no sistema.
15. A ausência (falta) registrada implica na perda automática do direito àquela aula na semana, descontando uma aula do saldo semanal do plano do aluno.
16. Não há possibilidade de reposição ou remarcação da aula perdida por falta.
17. O sistema mantém um histórico de presenças e faltas de cada aluno.
18. Atrasos não são considerados; apenas presença ou falta são registrados.
19. Alunos com excesso de faltas podem ser restringidos de novas marcações, conforme política definida pela clínica.
20. O aluno pode remarcar ou cancelar uma aula até um limite de antecedência definido pela clínica.
21. Cancelamentos dentro do prazo liberam a vaga para o próximo da fila.
22. Cancelamentos fora do prazo podem consumir a aula do saldo do aluno.
23. O sistema registra a situação do pagamento do aluno (em dia, vencido, etc).
24. Alunos inadimplentes não podem agendar novas aulas.
25. Funcionários podem emitir comprovantes de pagamento.
26. Alunos e professores recebem notificações de confirmação, alteração, cancelamento ou liberação de vagas.
27. O sistema envia lembretes de aulas agendadas para alunos e professores.
28. Alunos na fila de espera recebem aviso quando uma vaga é liberada.
29. O sistema gera relatórios de agendamentos, presenças, faltas e ocupação das turmas.
30. Todas as ações dos funcionários são registradas no sistema para auditoria.

---
