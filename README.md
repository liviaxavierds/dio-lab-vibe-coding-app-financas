# App de Organização de Finanças Pessoais com Vibe Coding

O aplicativo é uma solução de organização de finanças pessoais via conversa natural, pensado para iniciantes e pessoas que buscam praticidade.
Principais diferenciais:

- Registro de gastos por chat em linguagem natural (Português e Inglês).
- Classificação automática de transações.
- Metas financeiras para economia/planejamento e limites por categoria.
- Alertas e relatórios simples e acessíveis.
- Agente Financeiro que sugere dicas personalizadas.
- Controle de compras parceladas.
- Página de Lançamentos para edição e exclusão de gastos.
- Interface acessível, com modos claro e escuro e design universal.
- Suporte a três moedas, permitindo maior flexibilidade para diferentes contextos financeiros.
- Tela inicial com visão clara e simplificada dos gastos diários e mensais, sem se tornar confusa ou sobrecarregada.

<img width="1917" height="866" alt="image" src="https://github.com/user-attachments/assets/d8dd33d2-f8a8-4b62-8824-3b2049733b74" />

<img width="1917" height="866" alt="image" src="https://github.com/user-attachments/assets/b7304065-4c12-4630-92ae-83eb1dac0146" />

Acesse a prévia da aplicação pelo link - https://lovable.dev/preview/CzjQgi3Q9AtHfLvwbEAy2KqkmpRw7Y9X

# Prompt Final (PRD)
Este foi o prompt final usado com a IA (Copilot + Lovable) para guiar o desenvolvimento da aplicação:

```txt
Create a Personal Finance Organization app based on natural conversations, following these guidelines:

1. App Structure:
- Main screens: Chat (expense registration and interaction with Financial Agent), Goals (definition and tracking of objectives), Reports (simple charts and insights), Installments (tracking of installment purchases), Launches (daily expenses with edit/delete options), and Settings (language, light/dark mode, accessibility).
- Implement simple and intuitive navigation between screens, following Universal Design principles and a clean visual style.

2. Expense Registration via Chat:
- Implement a chat screen where users can register expenses in Portuguese and English.
- Automatically interpret: transaction amount, category (food, transport, leisure, etc.), and date.
- Allow manual correction by the user if classification is incorrect.

3. Financial Goals and Alerts:
- Users can define financial goals for **savings/planning** (e.g., save $500/month).
- Users can also define **spending limits by category** (e.g., no more than $200/month on restaurants).
- The system must track progress in real time.
- Send notifications when expenses exceed limits or goals are not achieved.
- Display weekly and monthly reports with simple and accessible insights.

4. Financial Agent and Tips:
- Create a virtual Financial Agent that interacts with the user via chat.
- Provide personalized savings tips based on registered expenses.
- Use simple and educational language.
- Example: “You spent more on restaurants this month. How about cooking at home twice a week?”

5. UI and User Experience:
- Interface must follow Universal Design, accessible for different needs and compatible with screen readers.
- Clean and pleasant visual style, focused on simplicity.
- Light and dark modes, manual or automatic switching according to system preferences.
- Minimalist charts and reports, easy to interpret.
- Home screen must show a clear overview of total monthly spending and daily expenses, while keeping the layout simple and understandable.

Technical Requirements:
- NLP engine for natural language interpretation.
- Database for transaction and goal records.
- Push notification system.
- Reporting and simplified chart engine.
- Responsive UI with Universal Design.
- Support for Portuguese and English languages.
- Support for three currencies.

Initial Validation:
- Tests with a pilot group of beginner users.
- Evaluate clarity of conversation and accuracy of automatic classification.
- Measure engagement: frequency of use and expense registration.
- Collect feedback on accessibility and usability.

```

# Interações com o Copilot & Lovable

Durante o processo, foram realizadas diversas interações para ajustes e implementações. Estes incluem:
- Correção de erros identificados (botões, sincronização de parcelas, relatórios).
- Implementação da página “Launches” (Lançamentos) para edição e exclusão de gastos.
- Ajustes de identidade visual com paleta de cores personalizada (#fffcf2, #283618, #252422, #606c38, #f0ebe3, #fffdfa).
- Refinamento da experiência de chat e do Agente Financeiro.
- Implementação de suporte bilíngue (Português e Inglês) e compatibilidade com três moedas diferentes.
- Inclusão de uma visualização simples e clara dos gastos na tela inicial, sem poluição visual, mantendo o equilíbrio entre simplicidade e poder.
- Metas financeiras que contemplam tanto economia/planejamento quanto limites por categoria, oferecendo flexibilidade ao usuário.

<img width="1917" height="866" alt="image" src="https://github.com/user-attachments/assets/9716dac2-40b3-4dca-b281-e097a11b44ed" />

<img width="1917" height="868" alt="image" src="https://github.com/user-attachments/assets/ec36205a-63c1-4558-99f2-f011247c94b2" />

# Reflexão - O que eu aprendi
Durante o desenvolvimento deste projeto no Bootcamp da DIO, aprendi:

- A importância de detalhar ao máximo o PRD para reduzir ambiguidades no desenvolvimento.
- Como estruturar prompts claros e objetivos para guiar a IA (Lovable) sem margem de erro.
- A relevância de pensar na experiência do usuário desde o início, incluindo acessibilidade, simplicidade e visual clean.
- O valor de iterar constantemente: identificar erros, ajustar e validar cada funcionalidade.
- Que a colaboração com IA pode acelerar o processo criativo e técnico, mas exige precisão na comunicação.
- A importância de pensar em internacionalização (idiomas e moedas) para tornar o app mais inclusivo e útil em diferentes contextos.
- Que simplicidade não significa falta de poder: o app deve ser simples, mas poderoso, oferecendo clareza sem se tornar um emaranhado de informações.
- Que metas financeiras podem ser usadas tanto para planejamento de economia quanto para controle de gastos por categoria, ampliando o valor da aplicação.
