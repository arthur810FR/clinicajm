# Clínica MCL

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
│   │       │   ├── img/
│   │       │   └── js/
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
## 🛠️ Como Rodar o Projeto

### Pré-requisitos
- **Java** (JDK 11 ou superior)
- **Maven** (para gerenciamento de dependências)
- **PostgreSQL** (configurado e rodando)

### Instalação e Execução
1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seuusuario/clinicajm.git
   ```
2. **Navegue até o diretório do projeto:**
   ```bash
   cd clinicajm
   ```
3. **Compile e rode o projeto**
4. **Acesse o sistema no seu navegador:**
   ```bash
   Abra seu navegador e digite: http://localhost:8080
   ```
## 💻 Tecnologias Utilizadas
- **Java 11+** - Linguagem de programação
- **Spring Boot** - Framework para criação da aplicação
- **Thymeleaf** - Motor de templates para renderização de páginas HTML
- **PostgreSQL** - Banco de dados relacional
- **Maven** - Gerenciamento de dependências
- **HTML5 & CSS3** - Estrutura e estilização das páginas
- **JavaScript** - Scripts para interações dinâmicas no front-end

## 📚 Exemplos de Uso
1. **Cadastro de um novo paciente:**
   - Acesse a página de cadastro e preencha os dados do paciente.
   - Clique em "Salvar" para registrar o paciente no sistema.
2. **Agendamento de uma consulta:**
   - Selecione um paciente e um médico, escolha a data e hora, e clique em "Agendar Consulta".
3. **Realização de um atendimento:**
   - Acesse a consulta agendada e preencha os detalhes do atendimento, como sintomas e receita médica.

## 📞 Contato
**Arthur Francisco Guedes Azevedo**

- [LinkedIn](https://www.linkedin.com/in/arthur-azevedo-desenvolvedor/)
- [Email](mailto:arthurfranciscoazevedo@gmail.com)
