# 📘 Casos de Uso - Sistema de Chamados

Este documento descreve os casos de uso do sistema de chamados com base nos atores identificados no diagrama.

---

## Caso de Uso: Abrir Chamado
**Ator Principal:** Usuário  
**Resumo:** Permite ao usuário registrar um chamado de suporte relacionado a problemas com software, hardware ou acessos.  
**Pré-condições:** O usuário deve estar autenticado no sistema.  
**Pós-condições:** Um chamado é registrado com uma categoria e fica disponível para análise.  

### Fluxo Principal
1. O usuário acessa o sistema e realiza login.
2. Seleciona **"Abrir Chamado"**.
3. Escolhe a categoria do problema (Software, Hardware ou Acessos).
4. Preenche os campos obrigatórios (descrição, prioridade, anexos, etc).
5. Confirma a abertura do chamado.
6. O sistema registra o chamado e exibe o número do protocolo.

### Extensões
- **3a.** O usuário não seleciona nenhuma categoria → O sistema exibe uma mensagem de erro solicitando a seleção.
- **4a.** O formulário não é preenchido corretamente → O sistema destaca os campos obrigatórios que faltam.
- **5a.** O usuário cancela a operação → O sistema descarta os dados inseridos.

---
