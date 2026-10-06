
# Projeto: MedAgenda 
            Aplicação para a gestão de consultas médicas num hospital/clínica. O objetivo principal é evitar sobreposições de horários e esquecimentos nas marcações, facilitando a gestão da agenda dos médicos.

## Funcionalidade: Marcar Consulta
            O Recepcionista seleciona o paciente e o médico e indica a data, a hora e a duração da consulta. O sistema só regista a consulta se esta for válida: 
                - a data/hora está dentro do horário de expediente do Médico;
                - o Médico não tem outra consulta no mesmo horário. 
            Se o agendamento não for válido, o sistema apresenta uma mensagem a explicar o motivo.

