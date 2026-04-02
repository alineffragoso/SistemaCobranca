# SistemaCobranca

## 1. Proposta do Projeto

Este projeto tem como objetivo melhorar o processo de cobrança da empresa, substituindo atividades manuais por um sistema automatizado.

Atualmente, o processo envolve envio de cartas, ligações telefônicas e cobrança externa, o que pode gerar atrasos, falhas e dificuldade de controle.

A proposta é desenvolver um sistema que organize todo o fluxo de cobrança, automatizando etapas como envio de notificações, registro de contatos e acompanhamento de negociações.

Com isso, espera-se aumentar a eficiência do processo, reduzir custos e melhorar a recuperação de valores.

---


---
## 2. Diagrama de Atividade

Início
↓
Receber título para cobrança
↓
Registrar no sistema
↓
[PROCESSOS PARALELOS]
→ Enviar 1ª notificação (email/SMS)
→ Realizar contato telefônico
↓
Cliente respondeu?
→ Sim → Iniciar negociação
→ Não → Enviar 2ª notificação
↓
Contato telefônico realizado?
→ Sim → Iniciar negociação
→ Não → Aguardar retorno
↓
Sem resposta geral?
→ Sim → Acionar cobrador externo
↓
Cliente aceita negociar?
→ Sim → Registrar acordo
→ Não → Protestar título
↓
Pagamento realizado?
→ Sim → Transferir valores → Finalizar
→ Não → Protestar título
↓
Após protesto houve pagamento?
→ Sim → Transferir valores → Finalizar
→ Não → Devolver título → Finalizar
↓
Fim


---
## 3. Atores do Sistema

- Operador de cobrança  
- Sistema automatizado  
- Cobrador externo  
- Empresa contratante  
- Cliente (devedor)  

---

## 4. Casos de Uso

### Registrar Título
Cadastrar um novo título com dados do cliente, valor e vencimento.

### Enviar Notificação
Envio automático de mensagens de cobrança.

### Realizar Contato Telefônico
Tentativa de contato com o cliente e registro do resultado.

### Negociar Dívida
Criação de acordo de pagamento quando há interesse do cliente.

### Registrar Pagamento
Atualização do sistema após confirmação do pagamento.

### Acionar Cobrador Externo
Encaminhamento do caso para cobrança externa.

### Protestar Título
Envio do título para protesto em caso de não pagamento.

---

## 5. Requisitos Funcionais

- O sistema deve permitir cadastrar títulos de cobrança  
- O sistema deve enviar notificações automaticamente  
- O sistema deve registrar tentativas de contato  
- O sistema deve permitir negociação de dívidas  
- O sistema deve registrar pagamentos  
- O sistema deve acionar cobrador externo  
- O sistema deve realizar protesto de títulos  

---

## ⚙️ 6. Requisitos Não Funcionais

- O sistema deve ser acessado via web  
- Deve possuir bom desempenho  
- Deve garantir segurança dos dados  
- Deve ter interface simples e intuitiva  
- Deve ter alta disponibilidade  

---

## 7. Regras de Negócio

- A segunda cobrança só deve ser enviada se não houver resposta da primeira  
- A negociação só ocorre se houver contato com o cliente  
- O cobrador externo só é acionado após tentativas sem sucesso  
- O protesto ocorre quando não há acordo ou pagamento  
- O processo só é finalizado após pagamento ou devolução do título  

---

## 8. Melhorias Propostas

- Substituição de cartas físicas por email, SMS e WhatsApp  
- Automação do fluxo de cobrança  
- Registro automático de todas as interações  
- Acompanhamento em tempo real do processo  

---

## Conclusão

O sistema proposto melhora significativamente o processo de cobrança, tornando-o mais rápido, organizado e eficiente. Além disso, reduz falhas humanas e aumenta a taxa de recuperação de crédito.
