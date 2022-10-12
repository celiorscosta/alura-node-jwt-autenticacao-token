# Node.js e JWT: autenticação com tokens

| :placard: API em NodeJS |     |
| -------------  | --- |
| :sparkles: Nome        | **Node.js e JWT: autenticação com tokens**
| :label: Tecnologias | NodeJSr

Mais um estudo em node, agora mais voltado para as questões de segurança de aplicações.
> Blog do código, um blog simples em Node.js

## Tópicos abordados.

- Identifique e solucione problemas de segurança em sistemas de autenticação;
- Entenda o que são funções de hashing e como usá-las para guardar senhas de forma mais segura;
- Construa um sistema de autenticação usando tokens;
- Entenda o funcionamento do JSON Web Token e como usá-lo para autenticação;
- Utilize um banco de dados chave-valor em memória na sua aplicação.

## Project setup

Antes de rodar o sistema para testar, é necessario criar na raiz do projeto um arquivo chamado `.env`.
Dentro deste arquivo você devera adicionar a `CHAVE_JWT` conformer descrito abaixo:

```
CHAVE_JWT="coloque-sua-chave-secreta-aqui"
```

Para gerar a chave rode no seu terminal o comando:

```
node -e "console.log(require('crypto').randomBytes(256).toString('base64'))"
```

Copie a string gerada após a conclusão do comando e cole no lugar de "coloque-sua-chave-secreta-aqui".

Pronto!
