### Título
Como cliente da loja virtual, eu quero poder fazer login com meu e-mail e senha, para que eu possa acessar meu histórico de pedidos e minhas informações de perfil.

### Cenário 1: Login com sucesso
**Dado** que eu sou um cliente cadastrado e estou na página de login
    E eu preenchi o campo "e-mail" com "cliente@exemplo.com"
    E eu preenchi o campo "senha" com "senha123"
**Quando** eu clico no botão "Entrar"
**Então** eu devo ser redirecionado para a minha página de perfil
    E eu devo ver uma mensagem de boas-vindas com meu nome.

### Cenário 2: Senha incorreta
**Dado** que eu sou um cliente cadastrado e estou na página de login
    E eu preenchi o campo "e-mail" com "cliente@exemplo.com"
    E eu preenchi o campo "senha" com "senha-errada"
**Quando** eu clico no botão "Entrar"
**Então** eu devo continuar na página de login
    E eu devo ver uma mensagem de erro "E-mail ou senha inválidos."

### Notas
- O sistema de autenticação será o serviço X.
- Não haverá opção "Lembrar de mim" nesta primeira versão.
- Dúvida: qual o comportamento esperado após 5 tentativas de login sem sucesso? (Bloquear a conta? Captcha?) - Discutir com o PO.
