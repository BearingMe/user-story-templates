### Título
Como cliente, eu quero fazer login para acessar minha conta.

### Detalhes
- A autenticação será feita via e-mail e senha.
- O usuário deve ser redirecionado para a página "Minha Conta" após o login.
- Em caso de falha, uma mensagem de erro genérica ("Usuário ou senha inválidos") deve ser exibida para evitar informar qual campo está incorreto.
- A discussão com o PO confirmou que não haverá bloqueio de conta por tentativas de erro por enquanto.

### Tarefas técnicas
- [ ] Criar a UI da página de login (campos de e-mail, senha e botão).
- [ ] Desenvolver a lógica de validação dos campos no front-end.
- [ ] Criar o endpoint na API para autenticar o usuário.
- [ ] Implementar a lógica de redirecionamento após login com sucesso.
- [ ] Implementar a exibição de mensagem de erro.

### Definição de Pronto (DoD)
- [x] Todas as tarefas técnicas concluídas.
- [x] A funcionalidade foi testada manualmente (login com sucesso, e-mail errado, senha errada).
- [x] O código foi revisado por pelo menos um colega de equipe.
- [ ] Novos componentes de UI foram adicionados ao Storybook.
- [ ] Testes de unidade cobrem o serviço de autenticação.
