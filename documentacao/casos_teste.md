# Cenários de Teste

## C001 - Login com sucesso

Dado que o usuário possui cadastro válido
Quando informar email e senha corretos
Então deverá acessar a área autenticada

---

## C002 - Login com falha

Dado que o usuário possui cadastro válido
Quando informar senha incorreta
Então deverá visualizar mensagem de erro
