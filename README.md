**Projeto MM - Moeda Mestre | Backend**

O projeto será desenvolvido utilizando Node.js, com um foco especial em seguir boas práticas e princípios RESTful.

**Perguntas Iniciais:**
- Quais endpoints devem ser implementados?
- Quais dados precisam ser armazenados no banco de dados?
- Que informações serão enviadas para a API?
- Que informações precisamos retornar?

*Essas questões serão devidamente abordadas e respondidas ao final deste documento.*

---

**Etapas do Projeto:**

**Problema:**
Desenvolver uma solução completa e organizada para gestão financeira pessoal.

**Solução:**
Criar uma versão simplificada do aplicativo "Minhas Finanças".

**Layouts:**
[Fotos do Aplicativo]

**Escopo:**
*O que será feito?*

1. **Controle de Usuários:**
   - Criar, editar, excluir e recuperar contas de usuários no MM.

2. **Carteiras:**
   - Possibilitar a criação de carteiras de diversos tipos, como carteira, conta corrente, poupança.
   - Permitir que o cliente crie, edite e exclua tipos de carteiras.

3. **Contas Financeiras:**
   - **Contas a Receber:**
      - Informar se é recorrente e a categoria da conta (ex: benefícios, comissão, fixa, pagamentos, serviços, vendas).
      - Cliente pode criar, editar e apagar categorias.
      - Adicionar a carteira de entrada do valor, enviar imagem do comprovante financeiro e confirmar a efetivação.

   - **Contas a Pagar:**
      - Informar se é recorrente e a categoria da conta (ex: alimentação, carro, educação, encargos, lazer, moradia, pagamentos, saúde, serviços, transporte, vestuário).
      - Cliente pode criar, editar e apagar categorias.
      - Adicionar a carteira de saída do valor, enviar imagem do comprovante financeiro e confirmar a efetivação.

   - **Transferências Monetárias:**
      - Informar se é recorrente e confirmar a efetivação da transferência entre carteiras.
      - Adicionar a carteira de saída e entrada do valor, enviar imagem do comprovante financeiro.

   - **Dados para Relatórios:**
      - Resumo por período e carteira, mostrando saldo total de abertura, despesas, transferências crédito/débito, receitas e saldo atual e previsto.
      - Resumo de despesas por período, agrupado por categoria.
      - Resumo de receitas por período, agrupado por categoria.
      - Resumo de transferências por período.
      - Resumo atual por carteiras.

   - **Orçamentos:**
      - Criar, editar e apagar orçamentos, vinculando categorias de saídas e valor previsto.

*O que não será feito?*
- [Detalhar aqui o que não será incluído no projeto.]

**Desenvolvimento:**
[Detalhar aqui as etapas específicas do desenvolvimento.]

**Testes:**
[Detalhar aqui o plano de testes para o projeto.]
