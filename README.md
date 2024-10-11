Clínica MCL
Link da Hospedagem

📝 Descrição
A Clínica MCL é um sistema de gestão para clínicas médicas desenvolvido em Spring Boot, com interface utilizando Thymeleaf e estilização personalizada. O sistema visa facilitar o gerenciamento de pacientes, médicos e consultas, proporcionando um ambiente intuitivo para o atendimento médico.

🚀 Funcionalidades
Cadastro de Usuários: Permite o registro de novos usuários com dados como nome, e-mail e senha.
Autenticação e Login: Sistema de login seguro para acesso às funcionalidades do sistema.
Cadastro de Pacientes e Médicos: Registra pacientes e médicos, incluindo especialidades médicas.
Listagem de Pacientes e Médicos: Visualiza e gerencia as listas de pacientes e médicos.
Agendamento de Consultas: Agende consultas médicas, associando pacientes e médicos a uma data e hora.
Registro de Atendimentos: Registre detalhes dos atendimentos, como sintomas e receitas.
Visualização de Consultas: Acompanhe e gerencie consultas agendadas, com edição e exclusão.
📂 Estrutura do Projeto
bash
Copiar código
src
└── main
    ├── java/com/clinica/mcl/... (código Java)
    └── resources
        ├── static
        │   ├── css
        │   │   ├── reset.css
        │   │   ├── styles.css
        │   │   ├── styles_forms.css
        │   │   ├── styles_home.css
        │   │   ├── styles_login.css
        │   │   └── styles_user.css
        │   ├── img
        │   └── js
        │       ├── progressbar.min.js
        │       ├── scripts.js
        │       └── scripts_user.js
        ├── templates
        │   ├── consulta
        │   │   ├── add_consulta.html
        │   │   ├── atendimento_consulta.html
        │   │   └── list_consulta.html
        │   ├── medico
        │   ├── paciente
        │   ├── home.html
        │   ├── index.html
        │   ├── login.html
        │   └── user_cadastro.html
        ├── application.properties
        └── application.yml
🛠️ Como Rodar o Projeto
Pré-requisitos
Java (JDK 11 ou superior)
Maven (para gerenciamento de dependências)
PostgreSQL (configurado e rodando)
Instalação e Execução
Clone o repositório:
bash
Copiar código
git clone https://github.com/seuusuario/clinica-mcl.git
Navegue até o diretório do projeto:
bash
Copiar código
cd clinica-mcl
Configure o banco de dados: Edite o arquivo application.properties ou application.yml com as informações do seu banco de dados PostgreSQL.
properties
Copiar código
spring.datasource.url=jdbc:postgresql://localhost:5432/clinica_mcl
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha
Compile e execute a aplicação:
bash
Copiar código
mvn spring-boot:run
Acesse a aplicação: Abra o navegador e vá para http://localhost:8080.
💻 Tecnologias Utilizadas
Java 11 - Linguagem principal
Spring Boot - Framework para construção do backend
Thymeleaf - Motor de templates para renderizar HTML
PostgreSQL - Banco de dados relacional
HTML5, CSS3 - Interface do usuário
JavaScript - Funcionalidades dinâmicas na interface
📷 Capturas de Tela
Página de Cadastro

Página de Login

Listagem de Pacientes

Listagem de Médicos

Agendamento de Consultas

Registro de Atendimento

Nota: Substitua link-da-imagem pelos links das imagens hospedadas, caso queira incluir imagens no GitHub.

📚 Exemplos de Uso
Cadastro de um novo usuário: Acesse a página de cadastro e insira seu nome, e-mail e senha.
Agendamento de consulta: Selecione um paciente, um médico e uma data para agendar uma consulta.
Registro de atendimento: Insira informações de sintomas e receitas durante o atendimento ao paciente.
📞 Contato
Arthur Francisco Guedes Azevedo
