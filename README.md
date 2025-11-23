# proj-azurechallengeKM

# Meu Primeiro Projeto – Chatbot de Suporte Clube de Vantagens

## Contexto
Meu primeiro Projeto criado através do Challenge do Azure Frontier Girls, programa desenvolvido pela Microsoft juntamente com a Womakers Code.

## Descrição
Este projeto consiste em um chatbot de suporte voltado para varejistas que acessam o site do Clube de Vantagens.  
O objetivo do agente é orientar de forma simples e objetiva sobre erros comuns de acesso, seguindo fluxos fixos e encaminhando o usuário para os canais corretos de atendimento quando necessário.  
O chatbot sempre apresenta o mesmo menu de opções e conduz o usuário passo a passo, sem antecipar etapas.  

**Observação:** Existe uma regra para usuários da plataforma do clube de vantagens: quem não acessa há mais de 3 meses terá o cadastro inativado até que seja feito o contato para realização de ativação.

## Objetivo do Agente
- Auxiliar usuários com problemas de acesso ao site.  
- Seguir fluxos pré-definidos de atendimento.  
- Encaminhar para os e-mails corretos em caso de erro ou necessidade de suporte humano.  
- Garantir uma experiência clara e cordial, sempre perguntando se o usuário deseja tirar outra dúvida ao final de cada fluxo.  

## Fluxo do Projeto

### Boas-vindas
Cumprimenta o usuário e explica que ajuda em problemas de acesso ao site.

### Menu de Opções
O chatbot apresenta sempre as mesmas opções numeradas:

1. Fazer login  
2. Recuperar senha  
3. Verificação em duas etapas (2FA)  
4. Outro problema de acesso  

### Respostas Fixas

#### Opção 1 – Fazer login
- Primeiro acesso → verificar e-mail de ativação (spam/lixo eletrônico).  
- Se ativado e não consegue acessar → suporte@clubeficticio.com.br  
- Não é primeiro acesso → verificar se há erro.  
  - Se sim → suporte@clubeficticio.com.br  
  - Se não → verificar se está há mais de 3 meses sem acessar.  
    - Se sim → cadastro@clubeficticio.com.br  
    - Se não → suporte@clubeficticio.com.br  

#### Opção 2 – Recuperar senha
- Orientar a clicar em "Esqueci minha senha".  
- Se não funcionar → verificar spam.  
- Se ainda não resolver → perguntar se está há mais de 3 meses sem acesso.  
  - Se sim → cadastro@clubeficticio.com.br  
  - Se não → suporte@clubeficticio.com.br  

#### Opção 3 – Verificação em duas etapas (2FA)
- Perguntar se recebeu o código enviado por e-mail.  
- Perguntar se está há mais de 3 meses sem acesso.  
  - Se sim → cadastro@clubeficticio.com.br  
- Perguntar se há erro.  
  - Se sim → suporte@clubeficticio.com.br  

#### Opção 4 – Outro problema de acesso
- Perguntar se já é cadastrado.  
  - Se sim → sac@clubeficticio.com.br  
  - Se não → www.clubeficticio.com  

### Encerramento
Após qualquer fluxo, o chatbot pergunta:  
- Deseja tirar outra dúvida? (Sim/Não)

Se a resposta for **Sim**:  
- Reapresenta o menu.  

Se a resposta for **Não**:  
- Responde: Obrigado pelo contato. Estamos à disposição sempre que precisar.  
- Encerra o chat.  

## Execução Registrada
- Simulação em vídeo 1: https://youtu.be/eo6MQvwEUYY  
- Simulação em vídeo 2: https://youtu.be/H9SzUW2W0PU  

Fluxo de execução com prints:  
https://1drv.ms/b/c/4b8d44d2b58721ac/IQBxY8WLEohEQI4yj2HjuOOdAbpvxnczi0vH9qM5l-id-Mw  

## Referências
- Microsoft Foundry

