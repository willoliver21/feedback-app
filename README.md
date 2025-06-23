# 📝 Feedback App - Aplicativo de Coleta de Feedbacks

Este é um projeto simples e funcional desenvolvido para coletar **feedbacks de clientes** sobre um aplicativo de serviços. Ele integra tecnologias modernas para criar um ecossistema completo de coleta, visualização e análise de dados.

---

## ⚙️ Tecnologias Utilizadas

- **💾 Supabase** – Banco de dados PostgreSQL com API REST integrada
- **📊 Power BI** – Painéis dinâmicos para análise e visualização dos dados
- **🌐 HTML + JS** – Front-end simples para envio de feedbacks
- **🧠 ChatGPT + CursorAI** – Assistência na construção do código e automações
- **🐙 Git + GitHub** – Versionamento de código
- **▲ Vercel** – Hospedagem do front-end com deploy automático

---

## 📌 Funcionalidades

- Envio de feedbacks por usuários via formulário web
- Coleta dos dados direto no banco Supabase
- Visualização dos dados em tempo real no Power BI
- Gráfico com média de notas e total de feedbacks enviados
- Deploy automático com Vercel
- Código versionado com Git e hospedado no GitHub

---

## 🧪 Como testar

1. **Enviar Feedback**
   - Acesse: [https://feedback-app-willoliver21.vercel.app/](https://feedback-app-willoliver21.vercel.app/](https://feedback-app-azure-delta.vercel.app/)
   - Preencha:  
     - Nota do atendimento (1 a 5)  
     - Nota do valor cobrado (1 a 5)  
     - Comentário opcional  
   - Clique em **"Enviar Feedback"**

2. **Ver dados no Power BI**
   - Conectado via ODBC com Supabase
   - Dashboard com:
     - Média das notas
     - Quantidade de feedbacks
     - Tabela detalhada dos registros

---

## 🛠️ Instalação e Configuração Local (dev)

```bash
git clone https://github.com/willoliver21/feedback-app.git
cd feedback-app
code .
```

Você pode abrir o `index.html` direto no navegador para testar.

---

## 🌐 Deploy

- Vercel detecta alterações no GitHub e faz deploy automático.
- URL do projeto: `https://feedback-app-willoliver21.vercel.app/`

---

## 🔒 Segurança

- Dados enviados via HTTPS
- Conexão com Supabase protegida por chave pública restrita
- Possibilidade futura de adicionar autenticação de usuários

---

## 📈 Possíveis melhorias futuras

- Autenticação via Supabase
- Filtros por data e tipo de serviço
- Exportar feedbacks (PDF/Excel)
- Painel administrativo completo
- Mobile First / Responsividade

---

## 👤 Autor

**Wilson Oliver**  
📧 will.oliver.ti@outlook.com  
🔗 [github.com/willoliver21](https://github.com/willoliver21)
