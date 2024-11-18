# Pratica-I

Contextualização
Uma empresa do setor de tecnologia está enfrentando dificuldades para gerenciar os atendimentos realizados por sua equipe de suporte técnico. O processo atual utiliza planilhas manuais, o que dificulta a organização, priorização e acompanhamento das demandas. Para melhorar a eficiência, a empresa decidiu implementar um sistema digital de gerenciamento de chamados.

Os chamados são classificados de acordo com a criticidade (baixa, média ou alta) e o status (aberto, em andamento, resolvido). Cada chamado deve estar associado a um cliente e a um colaborador responsável. A empresa deseja que o sistema permita gerenciar os chamados de maneira eficiente e organizada, oferecendo maior visibilidade sobre o fluxo de atendimento.

Desafio
Com base nesse cenário, desenvolva uma aplicação para gerenciar os chamados de suporte. A aplicação deve atender aos seguintes requisitos:

Cadastro de Clientes: Deve armazenar os dados do cliente: ID, nome, e-mail e telefone.
Cadastro de Chamados: Deve permitir o registro dos seguintes dados para cada chamado:

ID do chamado.
ID do cliente.
Descrição do problema.
Criticidade (baixa, média, alta).
Status (aberto, em andamento, resolvido) com valor padrão "aberto".
Data de abertura.
ID do colaborador responsável (opcional no cadastro inicial).

Gerenciamento de Chamados: Permitir a atualização do status e a designação ou troca do colaborador responsável por um chamado.
Visualização: Mostrar os chamados em uma interface com filtros por status, criticidade e colaborador responsável.

Entregas

Entregar em um repositório no Github.

Diagrama Entidade-Relacionamento (DER):
Um DER contendo as tabelas de clientes, colaboradores e chamados, incluindo os relacionamentos e as chaves necessárias.
Criação do Banco de Dados:
Desenvolver
a estrutura do banco de dados com tabelas, relacionamentos e consultas
necessárias. A estrutura deve ser exportada em formato SQL.
Diagrama de Caso de Uso:
Criar
um caso de uso que ilustre os atores (cliente, colaborador), os objetos
e as ações relacionadas ao fluxo de gerenciamento de chamados.
Tela de Cadastro de Clientes:
Interface para cadastrar clientes com validação de campos obrigatórios e e-mail válido.
Mensagem de sucesso após o cadastro.
Garantir a inserção dos dados no banco de dados.
Tela de Gerenciamento de Chamados:
Interface para listar os chamados organizados por status e criticidade.
Opção para editar o status e o colaborador responsável.
Filtros para facilitar a visualização.
