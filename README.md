# Teste Prático para QA Pleno

## Objetivo
Avaliar a capacidade do candidato de:
1. Elaborar planos e roteiros de teste para uma aplicação web.
2. Criar relatórios de bugs detalhados para suporte ágil ao time de desenvolvimento.
3. Demonstrar habilidade prática no uso de Cypress para automação de testes funcionais.
4. Realizar testes em uma API REST, incluindo validação de respostas, erros e fluxos principais.

---

## Parte 1: Testes na aplicação OpenCart Demo
### Aplicação a ser testada
**URL**: [OpenCart Demo](https://www.opencart.com/index.php?route=cms/demo)

### Instruções
1. Acesse a aplicação e explore as funcionalidades disponíveis.
2. Concentre-se nos seguintes fluxos principais:
   - **Usuário**:
     - Login/logout com credenciais válidas e inválidas.
     - Alteração de informações do perfil.
   - **Catálogo de Produtos**:
     - Navegação e busca de produtos.
     - Adicionar/remover produtos ao carrinho.
     - Finalização de compra (simulação).
   - **Administração**:
     - Gerenciamento de produtos (adicionar, editar, excluir).
     - Visualização de pedidos.

3. **Artefatos a serem entregues**:
   - **Plano de Testes**:
     - Objetivo e escopo.
     - Roteiro de testes com cenários detalhados, incluindo:
       - Pré-condições.
       - Passos a serem seguidos.
       - Resultados esperados.
   - **Relatório de Bugs** (mínimo de 3 bugs fictícios):
     - Inclua título, descrição, impacto, passos para reprodução, resultado esperado/atual e evidências (capturas de tela ou vídeos).

4. **Automação com Cypress**:
   - Implemente os seguintes casos de teste:
     1. Verificar se é possível adicionar um produto ao carrinho e visualizar os detalhes no carrinho.
     2. Validar que um usuário não autenticado não consegue acessar áreas restritas.
     3. Testar o fluxo de login/logout com credenciais válidas.

---

## Parte 2: Testes de API
### API a ser testada
**API**: [JSONPlaceholder API](https://jsonplaceholder.typicode.com)

### Instruções
1. Acesse a documentação e explore os endpoints disponíveis.
2. Concentre-se nos seguintes fluxos principais:
   - **GET /posts**: Listar todos os posts.
   - **POST /posts**: Criar um novo post.
   - **PUT /posts/:id**: Atualizar informações de um post existente.
   - **DELETE /posts/:id**: Remover um post.
   - **GET /comments?postId=:id**: Filtrar comentários de um post específico.

3. **Artefatos a serem entregues**:
   - **Plano de Testes para API**:
     - Inclua cenários como:
       - Validação de status HTTP (`200`, `201`, `404`, etc.).
       - Testes de edge cases (ex.: tentar criar um post com dados incompletos).
     - Estruture cada cenário com pré-condições, passos, e resultados esperados.
   - **Relatório de Bugs** (mínimo de 2 bugs fictícios):
     - Use endpoints reais para simular erros ou inconsistências.
     - Inclua evidências (print de requisições/respostas usando Postman, Curl ou outra ferramenta).

4. **Automação de Testes de API**:
   - Use Cypress ou outra ferramenta (ex.: Postman + Newman) para:
     1. Criar um post e validar que ele aparece na listagem.
     2. Atualizar um post e verificar que as mudanças foram aplicadas.
     3. Excluir um post e garantir que ele não existe mais.

---

## Critérios de Avaliação
1. **Planos e Roteiros de Teste**:
   - Clareza e alinhamento com o cenário proposto.
   - Cobertura adequada de cenários.
2. **Relatórios de Bugs**:
   - Detalhamento e utilidade para o time de desenvolvimento.
   - Estruturação e clareza.
3. **Automação (Cypress e API)**:
   - Qualidade do código (limpeza, boas práticas, reutilização).
   - Cobertura dos cenários e funcionamento correto.
4. **Organização e Apresentação**:
   - Estrutura dos artefatos entregues e facilidade de entendimento.

---

## Instruções Finais
1. Envie os resultados organizados, incluindo:
   - Documentos de planejamento e relatórios.
   - Código de automação (incluindo setup e instruções para execução).

Boa sorte!
