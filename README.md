# 🪑 SysCadeiras

**Sistema de Controle de Produção e Estoque para Fábricas de Cadeiras**

SysCadeiras é um aplicativo desktop desenvolvido com **Electron** e **SQLite**, criado sob medida para pequenas e médias fábricas de cadeiras. Ele permite gerenciar a produção diária dos funcionários, controlar o estoque de peças por modelo e cor, gerar relatórios completos e calcular a folha de pagamento com base na produção.

.

---

## ✨ Funcionalidades

- **Cadastro de Modelos (Peças)** – Nome e valor unitário.
- **Cadastro de Cores** – Nome da cor.
- **Cadastro de Funcionários** – Nome e cargo.
- **Registro de Produção Diária**  
  - Data, funcionário, modelo, cor, quantidade e indicador de hora extra (+50%).
  - Permite adicionar múltiplos itens por produção.
- **Controle de Estoque Automático**  
  - Entradas via produção.
  - Saídas (vendas/consumo) com observação.
  - Saldo atualizado em tempo real por modelo e cor.
- **Pesquisa Avançada no Estoque** – Filtros por período, peça, cor e texto livre.
- **Relatórios**  
  - **Geral de Produção** (com filtros por data, funcionário, modelo, cor).
  - **Por Modelo/Cor** (agrupado).
  - **Movimentações de Estoque**.
  - **Folha de Pagamento** mensal por funcionário, com exportação CSV detalhada.
- **Dashboard Estatístico** – Gráficos de entradas/saídas, movimentações por dia, top itens e produção por funcionário.
- **Backup e Restauração**  
  - Cópia do banco de dados SQLite (.db) com otimização VACUUM.
  - Exportação/importação de dados em JSON.
- **Instalador Profissional para Windows** – Gera um executável que não requer Node.js ou dependências no computador do cliente.

---

## 🛠️ Tecnologias Utilizadas

- [Electron](https://www.electronjs.org/) – v28.0.0
- [SQLite3](https://www.npmjs.com/package/sqlite3) – Banco de dados local
- [Chart.js](https://www.chartjs.org/) – Visualização de dados no dashboard
- [electron-builder](https://www.electron.build/) – Empacotamento e criação de instalador
- HTML5, CSS3, JavaScript (ES6)

---

## 📸 Capturas de Tela

| Produção | Estoque | Relatórios |
|----------|---------|------------|
| ![Produção](screenshots/producao.png) | ![Estoque](screenshots/estoque.png) | ![Relatórios](screenshots/relatorios.png) |

> **Nota:** Coloque suas imagens na pasta `screenshots/` e ajuste os nomes dos arquivos conforme necessário.
