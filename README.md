📝 Feedback App - Aplicativo de Coleta de Feedbacks
Este é um projeto simples e funcional desenvolvido para coletar feedbacks de clientes sobre serviços prestados por profissionais. Ele integra tecnologias modernas para criar um ecossistema completo de coleta, visualização e análise de dados, servindo como uma ferramenta de avaliação de reputação.

⚙️ Tecnologias Utilizadas
💾 Supabase – Banco de dados PostgreSQL com API REST integrada
📊 Power BI – Painéis dinâmicos para análise e visualização dos dados
🌐 HTML + JS – Front-end simples para envio de feedbacks
🧠 ChatGPT + CursorAI – Assistência na construção do código e automações
🐙 Git + GitHub – Versionamento de código
▲ Vercel – Hospedagem do front-end com deploy automático
📌 Funcionalidades
Envio de feedbacks por usuários via formulário web.
Coleta do nome do profissional avaliado e notas específicas de qualidade e pontualidade.
Armazenamento dos dados direto no banco Supabase.
Visualização dos dados em tempo real no Power BI.
Gráfico com média de notas (qualidade, pontualidade) e total de feedbacks enviados.
Deploy automático com Vercel.
Código versionado com Git e hospedado no GitHub.
🧪 Como testar
Enviar Feedback

Acesse: https://feedback-app-willoliver21.vercel.app/
Preencha:
Nome do profissional avaliado
Nota da qualidade do serviço (1 a 5)
Nota da pontualidade (1 a 5)
Comentário opcional
Clique em "Enviar Feedback"
Ver dados no Power BI

Conectado via ODBC com Supabase.
Dashboard com:
Média das notas por critério (qualidade, pontualidade).
Quantidade de feedbacks.
Tabela detalhada dos registros, podendo ser filtrada por profissional.
🛠️ Instalação e Configuração Local (dev)
Bash

git clone https://github.com/willoliver21/feedback-app.git
cd feedback-app
code .
Você pode abrir o index.html direto no navegador para testar.

🌐 Deploy
A Vercel detecta alterações no branch main do GitHub e faz deploy automático.
URL do projeto: https://feedback-app-willoliver21.vercel.app/
🔒 Segurança
Dados enviados via HTTPS.
Conexão com Supabase protegida por chave pública restrita (anon key).
Validações no front-end e CHECK constraints no banco de dados para garantir a integridade dos dados.
📈 Possíveis melhorias futuras
Integração com Plataforma Externa (ex: Staircase):
Vincular feedbacks a perfis de profissionais e clientes via ID em vez de nome em texto.
Adicionar autenticação de usuários para garantir a veracidade das avaliações.
Exibir notas e comentários diretamente no perfil público do profissional.
Funcionalidades Avançadas no Painel:
Filtros por data, profissional e tipo de serviço.
Exportar relatórios de feedbacks (PDF/Excel).
Melhorias na Interface:
Design Mobile First e maior responsividade.
Permitir que profissionais respondam aos feedbacks recebidos.
👤 Autor
Wilson Oliver
📧 will.oliver.ti@outlook.com
🔗 github.com/willoliver21
