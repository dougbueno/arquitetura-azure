# 🌐 Construindo Arquiteturas no Azure

Projeto realizado durante o **Bootcamp Bradesco Java Cloud Native** promovido pela **Digital Innovation One (DIO)**.  
Este guia apresenta os passos para criação de um projeto de arquitetura utilizando **grupos de recursos no Azure**, além de explicar os benefícios dessa abordagem.

---

## 🧭 Etapas para Criar um Projeto de Arquitetura no Azure

### 🔐 1. Acessar o Portal do Azure
- Acesse: [https://portal.azure.com](https://portal.azure.com)
- Faça login com sua conta Microsoft.

### 🗂 2. Acessar a Seção de Grupos de Recursos
- No menu à esquerda, clique em **"Grupos de recursos"**.
- Ou use a barra de busca para localizar.

### ➕ 3. Criar um Novo Grupo de Recursos
- Clique em **"Criar"** para iniciar o processo.

### ✏️ 4. Preencher os Detalhes
- **Assinatura**: Escolha a assinatura ativa.
- **Nome**: Defina um nome único para o grupo.
- **Região**: Escolha onde o grupo será localizado.
- Clique em **"Revisar + criar"**.

### ✅ 5. Validar e Criar
- Após a validação, clique em **"Criar"** para finalizar.

### 📂 6. Verificar a Criação
- Uma notificação aparecerá confirmando a criação.
- Clique em **"Ir para o grupo de recursos"**.

### 🛠 7. Gerenciar Recursos
- Adicione serviços como:
  - Máquinas Virtuais
  - Banco de Dados
  - Contas de Armazenamento
- Monitore e gerencie tudo de forma centralizada.

---

## ❓ Por que Criar um Grupo de Recursos?

### 🎯 Principais Benefícios

1. **Organização Lógica**
   - Agrupe recursos de uma mesma aplicação.
   - Facilite a localização e o gerenciamento.

2. **Gerenciamento do Ciclo de Vida**
   - Faça deploy, atualização e exclusão em massa.
   - Ao excluir um grupo, todos os recursos dentro dele são apagados.

3. **Controle de Acesso (IAM)**
   - Atribua permissões (RBAC) no grupo.
   - Controle quem pode acessar ou editar.

4. **Monitoramento e Custos**
   - Visualize e analise gastos centralizados.
   - Ajuda no controle e otimização de custos.

5. **Isolamento e Segurança**
   - Separe ambientes de desenvolvimento, teste e produção.
   - Aplique políticas de segurança com Azure Policy.

6. **Facilidade na Implantação**
   - Use ARM Templates para criar toda a estrutura automaticamente.

7. **Escopo para Operações**
   - Configure backups, monitoramento e auditorias em nível de grupo.

---

## 🧾 Resumo

> Criar um grupo de recursos no Azure é essencial para **organizar, gerenciar e proteger** os recursos de um projeto.  
Permite controle centralizado de acesso, políticas, custos e operações — sendo uma prática recomendada para **boas arquiteturas em nuvem**.

---

🔗 **Tecnologia utilizada:**  
- Plataforma: [Microsoft Azure](https://azure.microsoft.com/)

🎓 **Bootcamp:**  
[Bradesco - Java Cloud Native | DIO](https://www.dio.me)

