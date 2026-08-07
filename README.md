#Atividade 1: Fundamentos do Teste de Software

## 🛠️ O que foi usado
* **Linguagem Python 3:** Para análise das regras de negócio do módulo de inscrição e checkout.
* **Ambiente de Desenvolvimento:** VS Code / PyCharm / IDLE para execução dos scripts e testes manuais.
* **Teste de Mesa (Execution/Dry Run):** Análise lógica linha a linha do código para rastreamento de falhas.
* **Markdown:** Para documentação técnica e estruturação do repositório no GitHub.

---

## 💡 O que foi aprendido

### 1. Tríade do QA (Erro vs. Defeito vs. Falha)
* **Erro (Humano):** Engano do desenvolvedor ao digitar `- 10` em vez de calcular a porcentagem de 10%.
* **Defeito / Bug (Código):** A instrução incorreta gravada no código-fonte.
* **Falha (Sistema):** A cobrança com valor errado exibida para o usuário final no checkout.

### 2. Tipos de Teste
* **Funcionais ("O QUE o app faz"):** Validação de regras de negócio (ex.: verificação do cupom `ALUNO10`, filtro de workshops e emissão de certificados).
* **Não Funcionais ("COMO o app faz"):** Desempenho, segurança e escalabilidade (ex.: tempo de resposta menor que 2s, suporte a 5.000 acessos simultâneos e criptografia de senhas).

### 3. Níveis da Pirâmide de Teste
* **Unitário:** Teste isolado de uma única função (ex.: validar isoladamente a função `validar_inscricao`).
* **Integração / Sistema / Aceitação (UAT):** A importância de testar desde a menor unidade de código até a validação final pelo cliente.

