API REST de agendamento de horários desenvolvida com Spring Boot.

🚀 Funcionalidades

- Cadastrar agendamentos
- Buscar agendamentos por data
- Alterar agendamentos
- Deletar agendamentos
- Validar horários já preenchidos

🧪 Endpoints

POST /agendamentos

GET /agendamentos?data=2026-02-03

PUT /agendamentos

DELETE /agendamentos

📦 Exemplo de requisição

{
"servico": "Corte",
"profissional": "João",
"dataHoraAgendamento": "2026-02-03T13:00:00",
"cliente": "Loyane",
"telefoneCliente": "13999999999"
}

📚 Tecnologias

- Java
- Spring Boot
- Spring Data JPA
- H2 Database
- Lombok