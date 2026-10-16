
# Hora 4 - Métodos GET e POST

## Ex 1 - Formulário Base

Foram criados dois formulários HTML com os campos nome e idade e um botão de submissão.

Ficheiros:
- get.html
- post.html
- resultado.html

## Ex 2 - Método GET

O método GET envia os dados através da URL.

Exemplo:
resultado.html?nome=Ana&idade=20

Os dados aparecem na query string e podem ser vistos no separador Network das DevTools.

## Ex 3 - Método POST

O método POST envia os dados no corpo do pedido HTTP.

Os dados não aparecem na URL, mas podem ser consultados no separador Network, em Payload.

Para processar um pedido POST é necessário um servidor que aceite este método.

## Ex 4 - Comparação GET e POST

| Característica | GET | POST |
|---|---|---|
| Localização dos dados | URL | Corpo do pedido |
| Dados visíveis na URL | Sim | Não |
| Network | Query String Parameters | Form Data / Payload |
| Operação CRUD | Read | Create |
| Utilização | Pesquisar alunos | Criar alunos |
| Segurança | Não usar para dados sensíveis | Usar HTTPS para dados sensíveis |

### Qual o método adequado para consultar um registo?

O método GET, porque permite consultar informação sem alterar os dados.

### Qual o método adequado para criar um registo?

O método POST, porque permite enviar dados ao servidor para criar um novo registo.

### Segurança

O GET apresenta os parâmetros na URL, podendo ficar no histórico do navegador.

O POST envia os dados no corpo do pedido, mas é necessário utilizar HTTPS para proteger a comunicação.
