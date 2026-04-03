# SistemaCobranca

## 1. Proposta do Projeto

Este projeto tem como objetivo melhorar o processo de cobrança da empresa, substituindo atividades manuais por um sistema automatizado.

Atualmente, o processo envolve envio de cartas, ligações telefônicas e cobrança externa, o que pode gerar atrasos, falhas e dificuldade de controle.

A proposta é desenvolver um sistema que organize todo o fluxo de cobrança, automatizando etapas como envio de notificações, registro de contatos e acompanhamento de negociações.

Com isso, espera-se aumentar a eficiência do processo, reduzir custos e melhorar a recuperação de valores.

---


---
## 2. Diagrama de Atividade

<img width="426" height="988" alt="image" src="https://github.com/user-attachments/assets/c688246b-4169-4f93-826e-849ed4f481a8" />

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

<img width="426" height="162" alt="image" src="https://github.com/user-attachments/assets/b2e45713-881c-4c2d-b92c-ccc59503e2d9" />

### Enviar Notificação
Envio automático de mensagens de cobrança.

<img width="426" height="208" alt="image" src="https://github.com/user-attachments/assets/144bc819-16e7-43f3-a039-b9793eee7f6b" />

### Realizar Contato Telefônico
Tentativa de contato com o cliente e registro do resultado.

<img width="426" height="226" alt="image" src="https://github.com/user-attachments/assets/d326983c-bacf-4248-8775-00ccc2e09d92" />

### Negociar Dívida
Criação de acordo de pagamento quando há interesse do cliente.

<img width="426" height="208" alt="image" src="https://github.com/user-attachments/assets/36c35c8f-d19d-4751-bd23-58f3dae8aa91" />

### Registrar Pagamento
Atualização do sistema após confirmação do pagamento.

<img width="426" height="161" alt="image" src="https://github.com/user-attachments/assets/b07b79e8-68ce-4ed2-b5be-f1d487e9e1ab" />

### Acionar Cobrador Externo
Encaminhamento do caso para cobrança externa.

<img width="426" height="142" alt="image" src="https://github.com/user-attachments/assets/fb88407b-9be9-44c9-af7e-c286a8852d5b" />

### Protestar Título
Envio do título para protesto em caso de não pagamento.

<img width="426" height="149" alt="image" src="https://github.com/user-attachments/assets/ca0505c6-73cb-414b-ac08-242987e4c711" />

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
