# Api REST e RESTFul

As APIs REST (Interface de Programação de Aplicações baseada em Transferência de Estado Representacional) e suas implementações práticas, conhecidas como RESTful, desempenham um papel fundamental na arquitetura de sistemas distribuídos e na comunicação entre diferentes componentes de software na era da web. A abordagem REST oferece um conjunto de princípios simples, mas poderosos, que permitem a criação de serviços web flexíveis, escaláveis e interoperáveis. Nesta introdução, exploraremos os fundamentos por trás da API REST, destacando suas características distintivas, e examinaremos como a implementação prática através de serviços RESTful proporciona uma estrutura robusta para o desenvolvimento de aplicações web modernas.

## Diferenças entre REST e RESTFul

REST representa um conjunto de princípios arquiteturais para serviços web baseados em HTTP. Por sua vez, RESTful é a implementação prática desses princípios, seguindo diretrizes específicas para garantir conformidade com os ideais do REST.

Enquanto REST fornece princípios gerais sem impor regras estritas, permitindo flexibilidade na implementação, RESTful é mais orientado a diretrizes específicas. Isso significa que RESTful segue padrões mais rigorosos, promovendo consistência e padronização nas implementações. Em termos de URI design, REST não impõe regras rígidas, permitindo interpretações variadas, enquanto RESTful encoraja uma abordagem estruturada e significativa para o design de URIs, facilitando a compreensão e a navegação.

Em resumo, REST estabelece os princípios fundamentais, enquanto RESTful se concentra na aplicação prática desses princípios, fornecendo diretrizes mais específicas para uma implementação consistente e padronizada.

## HTTP verbs

Os métodos HTTP, também conhecidos como HTTP verbs, desempenham um papel crucial na comunicação entre clientes e servidores em arquiteturas REST. Cada um destes métodos representa uma ação específica a ser executada em um recurso. Vamos dar uma breve olhada nos principais métodos HTTP:

1. **GET:**
   - **Propósito:** Solicita a obtenção de informações ou de um recurso específico.
   - **Exemplo:** Recuperar os detalhes de um usuário através da sua URI.
2. **POST:**
   - **Propósito:** Envia dados para o servidor a fim de criar um novo recurso.
   - **Exemplo:** Submeter um formulário com informações para criar um novo usuário.
3. **PUT:**
   - **Propósito:** Atualiza um recurso existente ou cria um novo se não existir.
   - **Exemplo:** Modificar os detalhes de um usuário com base na sua URI.
4. **DELETE:**
   - **Propósito:** Remove um recurso específico no servidor.
   - **Exemplo:** Excluir um usuário com base na sua URI.
5. **PATCH:**
   - **Propósito:** Aplica modificações parciais a um recurso.
   - **Exemplo:** Atualizar apenas alguns campos de um recurso, em vez de substituir o recurso inteiro.
6. **OPTIONS:**
   - **Propósito:** Retorna as opções de comunicação disponíveis para o recurso alvo.
   - **Exemplo:** Descobrir quais métodos ou cabeçalhos são suportados para uma determinada URI.
7. **HEAD:**
   - **Propósito:** Solicita apenas os cabeçalhos de resposta, sem o corpo da mensagem.
   - **Exemplo:** Verificar a última modificação de um recurso sem baixar o conteúdo completo.

Esses métodos estabelecem uma forma padronizada e consistente de interação entre clientes e servidores na web, permitindo uma variedade de operações em recursos por meio de ações bem definidas.

## HTTP Status Code

Os códigos de status HTTP são respostas numéricas fornecidas pelo servidor para indicar o resultado de uma solicitação do cliente. Alguns códigos comuns incluem:

- **2xx (Sucesso):** Indica que a solicitação foi bem-sucedida.
- **3xx (Redirecionamento):** Informa sobre redirecionamentos.
- **4xx (Erro do Cliente):** Indica erros do lado do cliente, como solicitação inválida ou recurso não encontrado.
- **5xx (Erro do Servidor):** Indica erros do lado do servidor, como falhas internas.

Esses códigos são essenciais para compreender e diagnosticar interações entre clientes e servidores na web.

---

Autor do resumo: Caio Guedes - 01558106
