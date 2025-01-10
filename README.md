# CapitalControl1

Passo 1: Planejamento do Projeto

Requisitos:
  1 - Quais dados você precisa armazenar? 
  
  -> ações, fiis, moedas, bdr, crypto
  
  2 - Quais funcionalidades principais o sistema terá?
  
  -> CRUD de ativos
  -> Gráfico de rentabilidade
  -> Integração com API de cotações
  
  3 - Que informações você quer exibir para o usuário?
  
  -> todas as informações dos investimentos dele

Escolha da stack:
  Backend: Node.js
  Frontend: React.js
  DB: PostgreSQL
  API de Cotações: INDEFINIDA (grátis e rápida)

Modelagem do Bando de Dados: 
  Criar um diagrama para visualizar tabelas e suas relações

  Exemplo:
    Tabela ativos: id, nome, categoria, ticker, quantidade, valor_compra, data_compra, etc.
    Tabela categorias: id, nome (ações, FIIs, etc.).
    Tabela transações: para registrar entradas/saídas.
    Tabela usuários: (se houver autenticação)
