# Clínica MCL

[Link da Hospedagem](#)

## 📝 Descrição
A **Clínica MCL** é um sistema de gestão para clínicas médicas desenvolvido em **Spring Boot**, com interface utilizando **Thymeleaf** e estilização personalizada. O sistema visa facilitar o gerenciamento de pacientes, médicos e consultas, proporcionando um ambiente intuitivo para o atendimento médico.

## 🚀 Funcionalidades
- **Cadastro de Usuários:** Permite o registro de novos usuários com dados como nome, e-mail e senha.
- **Autenticação e Login:** Sistema de login seguro para acesso às funcionalidades do sistema.
- **Cadastro de Pacientes e Médicos:** Registra pacientes e médicos, incluindo especialidades médicas.
- **Listagem de Pacientes e Médicos:** Visualiza e gerencia as listas de pacientes e médicos.
- **Agendamento de Consultas:** Agende consultas médicas, associando pacientes e médicos a uma data e hora.
- **Registro de Atendimentos:** Registre detalhes dos atendimentos, como sintomas e receitas.
- **Visualização de Consultas:** Acompanhe e gerencie consultas agendadas, com edição e exclusão.

## 📂 Estrutura do Projeto
```bash
clinicajm/
├── .idea/
├── src/
│   ├── main/
│   │   ├── java/br/com/javamagazine/clinicajm/
│   │   │   ├── config/
│   │   │   │   └── converters/
│   │   │   │       └── ConfiguracaoSpringMvc.java
│   │   │   ├── controller/
│   │   │   ├── dao/
│   │   │   ├── domain/
│   │   │   ├── security/
│   │   │   ├── service/
│   │   │   └── ClinicajmApplication.java
│   │   └── resources/
│   │       ├── static/
│   │       │   ├── css/
│   │       │   │   ├── reset.css
│   │       │   │   ├── styles.css
│   │       │   │   ├── styles_forms.css
│   │       │   │   ├── styles_home.css
│   │       │   │   ├── styles_login.css
│   │       │   │   └── styles_user.css
│   │       │   ├── img/
│   │       │   └── js/
│   │       │       ├── progressbar.min.js
│   │       │       ├── scripts.js
│   │       │       └── scripts_user.js
│   │       ├── templates/
│   │       │   ├── consulta/
│   │       │   │   ├── add_consulta.html
│   │       │   │   ├── atendimento_consulta.html
│   │       │   │   └── list_consulta.html
│   │       │   ├── medico/
│   │       │   ├── paciente/
│   │       │   ├── home.html
│   │       │   ├── index.html
│   │       │   ├── login.html
│   │       │   └── user_cadastro.html
│   │       ├── application.properties
│   │       └── application.yml
│   └── test/
│       ├── java/br/com/javamagazine/clinicajm/
│       │   ├── testeBancoDeDados/
│       │   │   └── ConsultaRepositoryTest.java
│       │   ├── TesteDeIntegracao/
│       │   │   └── ConsultaControllerTest.java
│       │   ├── testeDesempenho/
│       │   │   └── ConsultaPerformanceTest.java
│       │   ├── TesteDeSistemas/
│       │   │   └── ConsultaServiceTest.java
│       │   ├── TesteDeUnidade/
│       │   │   └── ConsultaControllerTest.java
│       │   └── ClinicajmApplicationTests.java
├── target/
```
