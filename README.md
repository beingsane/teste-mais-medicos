# Programa Mais Médicos

Criar um sistema onde o usuário possa cadastar, listar e excluir médicos de uma base de dados. Seria interessante, porém não obrigatório, ter uma pesquisa de médico por CRM e Nome.

Desejável:
 * Aplicar orientação a objetos de forma adequada onde for possível
 * A classe de conexão com o banco de dados deve seguir o design pattern singleton

Por ora:
 * Não será necessário efetuar autenticação do usuário.
 * O layout não será levado em consideração, apenas as funcionalidades.
 * Não é necessário checar a consistência dos dados informados pelo usuário.

## Atributos da classe médico de médico

 * Nome completo
 * CRM
 * Número telefone de contato

## Dados técnicos

Abaixo temos as informações técnicas dos serviços.

### Servidor Web

O servidor web está disponível:

 * PHP: 5.6
 * Extensões: pgsql, pdo_pgsql, gd, iconv, mcrypt
 * Apache: 2.2
 * Host: localhost
 * Porta HTTP: 8080
 * Diretório raiz: ./www
 * Endereço Index: http://localhost:8080

### Acesso ao PostreSQL à partir do PHP

O schema utilizado deverá ser criado com seu nome, ex: erichnascimento, alisonalonso.

 * Host: utilizar  a variável de ambiente POSTGRES_PORT_5432_TCP_ADDR ($_ENV['POSTGRES_PORT_5432_TCP_ADDR'])
 * Porta: utilizar a váriável de ambiente POSTGRES_PORT_5432_TCP_PORT ($_ENV['POSTGRES_PORT_5432_TCP_PORT'])
 * Usuário: postgres
 * Senha: (deixar em branco)

### PgAdmin

Para manuntenção do banco, poderá ser utilizado o PG Admin
 * Host: localhost
 * Porta: 5432
 * Usuário: postgres
 * Senha: (deixar em branco)


