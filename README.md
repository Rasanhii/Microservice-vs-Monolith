# Microservice-vs-Monolith

Vamos imaginar um sistema simples de gerenciamento de estoque. Em um modelo monolítico, todas as funcionalidades estariam em um único programa.
Instruções do Programa:
- Adicionar um novo produto ao estoque (nome, quantidade, preço).
- Listar todos os produtos em estoque.
- Buscar um produto pelo nome.
- Atualizar a quantidade de um produto em estoque.
- Remover um produto do estoque.


Divida as funcionalidades em microsserviços separados. Cada um terá sua própria responsabilidade.
Instrução:
- Crie microsserviços para:
- Gerenciar produtos (adicionar, listar, buscar).
- Gerenciar estoque (atualizar quantidade, remover).

Desafio: 
Utilize uma biblioteca como Flask ou FastAPI ou Django ou outra que preferir para criar as APIs de cada microsserviço.
Pense em como os microsserviços se comunicariam (por exemplo, através de chamadas HTTP).
