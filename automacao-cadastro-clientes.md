Atue como um especialista em N8N.

Crie uma automação para cadastrar automaticamente novos clientes.

Público:
Equipe de atendimento ou responsável pelo cadastro de clientes.

Ferramentas envolvidas:
N8N, formulário Webhook e PostgreSQL.

Fluxo:

1. Receber os dados do novo cliente através de um formulário.
2. Validar nome, e-mail e telefone.
3. Verificar se o e-mail já está cadastrado no banco de dados.
4. Caso o e-mail não exista, cadastrar o cliente no PostgreSQL.
5. Retornar uma confirmação informando que o cadastro foi realizado.

Regras:
Não cadastrar clientes sem nome ou e-mail válido.
Não permitir cadastros duplicados utilizando o mesmo e-mail.
Caso o e-mail já esteja cadastrado, informar que o cliente já existe e não realizar um novo cadastro.

Explique quais nós do N8N devem ser utilizados e a lógica de funcionamento do workflow.

