
# Hora 3 - Protocolo HTTP e Comunicação Web

## Ex 1 - Pedido Principal

Site escolhido: https://www.ipss.pt

Para analisar o pedido principal, abri o site no navegador e utilizei as ferramentas de desenvolvimento (F12), no separador Network.

O pedido principal é o pedido do tipo document, responsável por carregar a página HTML.

## Ex 2 - Registar Dados

| Informação | Resultado |
|---|---|
| Método HTTP | A preencher |
| URL do pedido | A preencher |
| Código de estado | A preencher |
| Content-Type | A preencher |

Os dados devem ser consultados no separador Headers do pedido principal.

## Ex 3 - Recursos Adicionais

| Recurso | Método HTTP | Código de Estado | Content-Type |
|---|---|---|---|
| Recurso 1 - A preencher | A preencher | A preencher | A preencher |
| Recurso 2 - A preencher | A preencher | A preencher | A preencher |
| Recurso 3 - A preencher | A preencher | A preencher | A preencher |

Os recursos adicionais podem incluir imagens, ficheiros CSS e JavaScript.

## Ex 4 - Tabela de Códigos HTTP

| Código | Nome | Significado |
|---|---|---|
| 200 | OK | O pedido foi realizado com sucesso. |
| 301 | Moved Permanently | O recurso foi movido permanentemente para outro URL. |
| 302 | Found | O recurso foi redirecionado temporariamente. |
| 400 | Bad Request | O pedido enviado está incorreto. |
| 403 | Forbidden | O servidor não permite o acesso ao recurso. |
| 404 | Not Found | O recurso pedido não foi encontrado. |
| 500 | Internal Server Error | Ocorreu um erro interno no servidor. |

## Ex 5 - Diferença entre 404 e 500

### Erro 404 - Not Found

O erro 404 acontece quando o recurso pedido não existe no endereço indicado.

Pode acontecer quando o utilizador escreve um URL incorreto ou quando uma página foi eliminada.

### Erro 500 - Internal Server Error

O erro 500 acontece quando existe um problema interno no servidor.

Pode ser causado por erros no código Java, problemas na base de dados ou configurações incorretas.

### Diferença

O erro 404 indica que o recurso não foi encontrado.

O erro 500 indica que o servidor teve um problema ao processar o pedido.
