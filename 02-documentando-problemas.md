# Documentando Problemas de Forma Estruturada

Uma boa documentação de problemas é essencial para que equipes técnicas consigam entender, reproduzir e resolver situações relatadas por usuários.

Relatos vagos ou incompletos geram retrabalho, atrasam a análise técnica e dificultam a identificação da causa raiz.
Por isso, documentar problemas de forma estruturada é uma prática fundamental em equipes de suporte técnico.

---

## Por que a documentação é importante

Quando um problema é bem documentado, ele permite que diferentes pessoas entendam rapidamente o que está acontecendo.

Uma boa documentação ajuda a:

- reduzir retrabalho entre suporte e desenvolvimento
- facilitar a reprodução do problema
- identificar padrões entre diferentes ocorrências
- acelerar a análise técnica
- registrar conhecimento para consultas futuras

Sem uma documentação clara, problemas podem parecer aleatórios ou difíceis de investigar.

---

## Elementos essenciais de um bom registro de problema

### 1. Contexto

Descrever onde e em que situação o problema ocorre.

Exemplos de contexto:

- módulo ou área do sistema
- tipo de usuário que executou a ação
- fluxo que estava sendo realizado
- momento em que o problema apareceu

Quanto mais claro for o contexto, mais fácil será entender o cenário.

---

### 2. Passos para reproduzir

Descrever exatamente o caminho que leva ao problema.

Exemplo:

1. Acessar determinada página
2. Preencher um formulário
3. Confirmar a ação
4. Observar o comportamento do sistema

Passos claros permitem que outras pessoas reproduzam a situação com facilidade.

---

### 3. Comportamento esperado

Explicar o que deveria acontecer normalmente.

Exemplo:

> Após confirmar a ação, o sistema deveria salvar os dados e exibir uma mensagem de confirmação.

Isso ajuda a entender qual é o comportamento correto do sistema.

---

### 4. Comportamento observado

Descrever o que realmente acontece.

Exemplo:

> Após confirmar a ação, o sistema permanece na mesma tela sem exibir mensagem ou salvar os dados.

Esse contraste entre esperado e observado facilita a análise técnica.

---

### 5. Evidências adicionais

Sempre que possível, incluir informações que ajudem na investigação.

Exemplos:

- prints de tela
- mensagens de erro
- registros de log
- horário aproximado da ocorrência
- frequência do problema

Essas evidências ajudam a acelerar a análise.

---

## Exemplo de documentação estruturada

**Contexto**

Usuário tentando registrar um novo item em um formulário.

**Passos para reproduzir**

1. Acessar a página de cadastro
2. Preencher todos os campos obrigatórios
3. Clicar em "Salvar"

**Comportamento esperado**

O sistema deveria salvar o registro e exibir confirmação.

**Comportamento observado**

O botão é clicado, mas o sistema não salva os dados nem apresenta mensagem de erro.

---

## Benefícios dessa abordagem

Documentar problemas de forma estruturada ajuda a transformar relatos isolados em informações úteis para investigação técnica.

Com o tempo, esses registros também permitem identificar padrões e gerar insights para melhorias no produto.
