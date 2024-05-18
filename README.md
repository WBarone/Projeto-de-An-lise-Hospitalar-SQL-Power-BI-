# Projeto de Análise Hospitalar (SQL+Power-BI)

# Introdução

O objetivo deste projeto foi de adquirir experiência com Bancos de Dados, através da linguagem SQL, tendo como produto final um Dashboard criado no Power BI. Neste projeto, somos livres para escolher qual SGBD será utilizado para executar o problema. Neste caso, o escolhido foi o SQL Server.

# Contexto

O XHospital está precisando dos nossos serviços como Analistas de Dados. Toda operação hospitalar é feita através de um ERP que utiliza como base de dados um banco SQL.

Esse sistema contempla um módulo que gera relatórios, mas como de costume, são relatórios limitados e extrair real valor deles não é uma tarefa fácil.

Os diretores do XHospital precisam avaliar o setor de internação e, muito melhor do que páginas e páginas de relatórios, querem um Dashboard dinâmico para fazer essa análise.

O setor de TI te dará acesso à base de dados, mas tem um detalhe: esse setor está desfalcado. Parte da equipe está de férias e um colaborador não faz mais parte da equipe. Isso significa que o setor está bem sobrecarregado e nós, como bons Analistas de Dados, precisaremos desenvolver as queries SQL necessárias para fazer o projeto acontecer.

# Perguntas
Criaremos um dashboard que responda perguntas como:

- **Qual o número de Admissões? E a quantidade de altas?**
- **Qual a taxa de mortalidade?**
- **Qual é o TMP (Tempo Médio de Permanência) dos pacientes?**
- **Quais convênios nos geram maior faturamento?**
- **Quais as classes de procedimentos que mais realizamos na unidade?**

# Coleta e Tratamento dos Dados através do SQL

O dataset será formado por 6 tabelas, sendo elas:

_1. tab_classe_procedimento.csv_

_2. tab_convenio.csv_

_3. tab_internacoes.csv_

_4. tab_medicos.csv_

_5. tab_paciente.csv_

_6. tab_procedimento.csv_

Abaixo o detalhamento de cada uma das tabelas:
