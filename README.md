📌 Projeto de Testes Manuais Funcionais no Mundo Ágil
📜 Descrição
Este projeto tem como objetivo revisar conceitos úteis para testes manuais no mundo ágil, bem como compreender e praticar atividades relativas ao dia a dia de um QA, com foco em testes manuais funcionais.
🚀 Entregáveis
• 	📑 Plano de fluxo de trabalho e ciclo de vida do bug
• 	📝 Documento com 2 User Stories
• 	🧩 Mind-map de pelo menos uma User Story
• 	🧪 2 Casos de teste utilizando técnica step-by-step
• 	🎭 2 Casos de teste utilizando BDD
🔄 Plano de Fluxo de Trabalho
1. 	🔍 Refinamento da User Story
2. 	📅 Planejamento dos testes
3. 	✍️ Criação dos casos de teste
4. 	🖥️ Execução dos testes manuais funcionais
5. 	🐞 Registro de defeitos (bugs)
6. 	🔁 Reteste após correção
7. 	✅ Encerramento do bug e entrega validada
🐞 Ciclo de Vida do Bug
Novo → Em Análise → Confirmado → Em Correção → Pronto para Reteste → Validado → Encerrado
🗒️ User Stories
User Story 1: Cadastro de Usuário
👤 Como um usuário visitante
Quero realizar meu cadastro na plataforma
Para acessar funcionalidades exclusivas
Critérios de Aceitação:
• 	✍️ Deve ser possível cadastrar nome, e-mail e senha
• 	📧 Deve validar e-mail obrigatório e formato válido
• 	🔒 Senha deve ter no mínimo 6 caracteres
User Story 2: Login de Usuário
👤 Como um usuário cadastrado
Quero fazer login na plataforma
Para acessar minha conta e utilizar os recursos
Critérios de Aceitação:
• 	📧 Campos obrigatórios: e-mail e senha
• 	⚠️ Mensagem de erro caso dados estejam incorretos
• 	🖥️ Redirecionamento para a dashboard após login bem-sucedido
✅ Casos de Teste Step-by-Step
Caso 1 — Cadastro com Dados Válidos
1. 	🌐 Acessar a página de cadastro
2. 	✍️ Preencher nome, e-mail válido e senha válida
3. 	🖱️ Clicar no botão "Cadastrar"
Resultado Esperado: ✅ Cadastro realizado com sucesso e redirecionamento para a dashboard
Caso 2 — Cadastro com E-mail Inválido
1. 	🌐 Acessar a página de cadastro
2. 	✍️ Preencher nome válido, e-mail inválido (ex.: sem "@") e senha válida
3. 	🖱️ Clicar no botão "Cadastrar"
Resultado Esperado: ⚠️ Exibir mensagem de erro: "E-mail inválido."
🎭 Casos de Teste BDD
Cenário 1 — Login Bem-Sucedido
• 	Dado que o usuário está na página de login
• 	Quando informa e-mail e senha válidos
• 	E clica no botão "Entrar"
• 	Então o sistema deve redirecionar para a dashboard
Cenário 2 — Login com Senha Incorreta
• 	Dado que o usuário está na página de login
• 	Quando informa e-mail válido e senha incorreta
• 	E clica no botão "Entrar"
• 	Então o sistema deve exibir a mensagem "Senha incorreta."
🧠 Mind Map
Cadastro de Usuário
• 	👤 Nome
• 	✅ Válido
• 	❌ Inválido (vazio)
• 	📧 E-mail
• 	✅ Válido
• 	❌ Inválido (sem @, vazio)
• 	🔒 Senha
• 	✅ Válida (mínimo 6 caracteres)
• 	❌ Inválida (vazia, menos de 6 caracteres)
