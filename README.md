# ListaMercado

Projeto WEB para lista de compras em mercado

##Caso de uso 

### Caso de Uso: Sistema de Lista de Compras Online para Supermercado


#### Fluxo Principal

**1. Cadastro e Autenticação**
   - **Descrição:** O usuário se cadastra no sistema com nome, e-mail e senha. Em seguida, faz o login.
   - **Fluxo de Ações:**
     1. O usuário acessa a página de cadastro e preenche suas informações.
     2. Após o cadastro, o usuário recebe uma confirmação e faz login no sistema.

**2. Criação de Lista de Compras**
   - **Descrição:** O usuário cria uma nova lista de compras e adiciona itens conforme a necessidade.
   - **Fluxo de Ações:**
     1. O usuário escolhe a opção "Criar Nova Lista".
     2. O sistema apresenta um campo para adicionar itens (nome do item, quantidade e unidade de medida).
     3. O usuário insere os itens e salva a lista.

**3. Edição e Exclusão de Itens**
   - **Descrição:** O usuário pode atualizar ou remover itens em uma lista de compras já criada.
   - **Fluxo de Ações:**
     1. O usuário acessa uma lista existente.
     2. O sistema permite adicionar, remover ou editar a quantidade de itens na lista.
     3. O usuário salva as alterações.

**4. Sugestão de Produtos**
   - **Descrição:** O sistema sugere itens com base no histórico de compras e nas ofertas do supermercado.
   - **Fluxo de Ações:**
     1. Ao acessar uma lista, o sistema verifica o histórico do usuário e as ofertas.
     2. Sugere itens relevantes que o usuário pode adicionar à lista.

**5. Compartilhamento de Lista**
   - **Descrição:** O usuário pode compartilhar a lista com amigos ou familiares via link ou e-mail.
   - **Fluxo de Ações:**
     1. O usuário acessa a lista e seleciona "Compartilhar".
     2. O sistema gera um link único ou oferece envio via e-mail para compartilhar a lista.

**6. Finalização da Lista**
   - **Descrição:** Após finalizar as compras, o usuário marca a lista como concluída e pode arquivá-la para referência futura.
   - **Fluxo de Ações:**
     1. O usuário abre a lista e marca os itens comprados como "Concluídos".
     2. O sistema permite que o usuário salve a lista como histórico e, em seguida, arquive-a.

---

####  Requisitos Funcionais

1. **Cadastro e Login de Usuário:**  
   - Permitir que o usuário se cadastre com nome, e-mail e senha.
   - Sistema de login seguro com autenticação de dois fatores (opcional).

2. **CRUD de Listas e Itens:**  
   - Criar, atualizar, e deletar listas de compras.
   - Adicionar, editar e excluir itens de uma lista.

3. **Sugestão de Produtos:**  
   - Exibir sugestões baseadas em histórico e promoções.

4. **Compartilhamento de Lista:**  
   - Permitir ao usuário compartilhar a lista via link ou e-mail.

5. **Armazenamento de Histórico:**  
   - Guardar listas antigas para referência futura.

6. **Interatividade e Design Responsivo:**  
   - Design intuitivo e fácil de usar, adaptável para dispositivos móveis e desktops.

---

#### Requisitos Não Funcionais

1. **Usabilidade:**  
   - Interface amigável e de fácil navegação para diferentes perfis de usuários.

2. **Segurança:**  
   - Armazenamento seguro de dados dos usuários com criptografia.

3. **Escalabilidade:**  
   - Suporte a um grande número de usuários simultâneos.

4. **Desempenho:**  
   - Tempo de resposta rápido ao acessar, criar e editar listas.
