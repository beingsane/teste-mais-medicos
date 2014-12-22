Programa Mais Médicos
=====================

Criar um sistema onde o usuário possa cadastar, listar e excluir médicos de uma base de dados. Seria interessante, porém não obrigatório, ter uma pesquisa de médico por CRM e Nome.

Desejável:
 * Aplicar orientação a objetos de forma adequada onde for possível
 * A classe de conexão com o banco de dados deve seguir o design pattern singleton

Por ora:
 * Não será necessário efetuar autenticação do usuário.
 * O layout não será levado em consideração, apenas as funcionalidades.
 * Não é necessário checar a consistência dos dados informados pelo usuário.

### Atributos da classe médico de médico ###

 * Nome completo
 * CRM
 * Número telefone de contato

Servidor Web
------------
O servidor web já está rodando é sua máquina:
 * PHP: 5.6
 * Apache: 2.2
 * Porta HTTP: 80
 * Diretório raiz: /home/vagrant/www


Base de dados
-------------
O schema utilizado deverá ser criado com seu nome, ex: erichnascimento, alisonalonso.
Host: localhost
Porta: 6543 (atenção pois não é na porta default)
Usuário: postgres
Senha: (deixar em branco)



