### Título
Autenticação de Usuário na Plataforma

### Descrição
Como um usuário registrado, eu quero poder me autenticar usando meu e-mail e senha, para que eu possa acessar as funcionalidades exclusivas da minha conta.

### Critérios de Aceitação
- [ ] Dado que o usuário está na página de login, ele deve visualizar os campos "e-mail", "senha" e um botão "Entrar".
- [ ] Quando o usuário preenche credenciais válidas e clica em "Entrar", ele deve ser autenticado e redirecionado para o dashboard.
- [ ] Quando o usuário preenche credenciais inválidas (e-mail ou senha incorretos) e clica em "Entrar", o sistema deve exibir a mensagem de erro "Credenciais inválidas." e permanecer na página de login.
- [ ] O campo de senha deve mascarar os caracteres digitados.

### Notas
- Dependências: Nenhuma.
- Restrições: O sistema não deve diferenciar entre "usuário não existe" e "senha incorreta" na mensagem de erro por razões de segurança.
- Links: [Link para o protótipo no Figma](http://figma.com/link-para-o-prototipo)
