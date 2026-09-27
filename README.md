# 🎮 Xbox Game Pass Subscriptions Sales - Dashboard em Excel

Projeto desenvolvido como desafio prático para a **DIO (Digital Innovation One)**. A solução consiste num **Dashboard Executivo de Vendas** construído no Excel para analisar o desempenho comercial das assinaturas do **Xbox Game Pass**, integrando dados de planos, renovações automáticas e pacotes adicionais (*Season Passes*).

---

## 🎯 Objetivo do Projeto

Transformar dados brutos de subscritores numa ferramenta visual e estratégica para a tomada de decisões. O painel responde a perguntas de negócio essenciais relacionadas com faturamento total, retenção por renovação automática e adesão a complementos como *EA Play* e *Minecraft Season Pass*.

---

## 🖥️ Experiência Interativa do Dashboard

A aba principal (**Dashboard**) foi desenhada com foco na usabilidade executiva (*UI/UX*), simulando a interface do próprio ecossistema Xbox:

- **Menu Lateral Clicável:** A primeira coluna funciona como um menu de navegação interativo. Ao clicar nas opções do menu, o painel atualiza dinamicamente as métricas e os gráficos.
- **Big Numbers (KPIs):** Destaque para os indicadores-chave de desempenho em cartões visuais (*Big Numbers*), permitindo a leitura rápida dos totais de faturamento, volume de vendas e métricas principais sem a necessidade de ler tabelas complexas.
- **Gráficos Dinâmicos:** Os gráficos adaptam-se instantaneamente de acordo com a seleção feita no menu lateral, facilitando a análise de cenários e tendências.

---

## 📁 Estrutura e Organização do Ficheiro

Para garantir uma apresentação limpa e focada no utilizador final, o ficheiro foi estruturado em **4 abas**, onde as abas técnicas e de apoio foram **ocultadas**, mantendo apenas o Dashboard visível ao abrir o Excel:

- **🖥️ Dashboard (Visível):** O painel executivo principal (*Xbox Game Pass Subscriptions Sales*), onde se concentram os *Big Numbers*, os gráficos interativos e a navegação por menu.
- **🧮 Cálculos (Oculta):** Aba técnica de consolidação de dados onde são processadas as perguntas de negócio (faturamento de planos anuais, distribuição por auto-renovação, total acumulado de assinaturas EA Play e Minecraft).
- **📊 Bases (Oculta):** Base de dados relacional com os registos dos subscritores (Subscriber ID, Nome, Plano: *Ultimate/Standard/Core*, Tipo: *Monthly/Quarterly/Annual*, Renovação Automática, Preços e Cupons).
- **🎨 Assets (Oculta):** Guia de identidade visual do projeto, contendo a paleta de cores oficial da marca Xbox (ex: `#22C55E`, `#9BC848`), ícones e elementos visuais.

> **Nota:** As abas de apoio permanecem no ficheiro em segundo plano para garantir o correto funcionamento das fórmulas e tabelas dinâmicas, podendo ser reexibidas a qualquer momento caso seja necessário auditar a estrutura de dados.

---

## 🚀 Como Visualizar e Utilizar

1. Faça o download do ficheiro `Dashboard de Vendas do Xbox.xlsx` disponível neste repositório.
2. Abra o ficheiro no **Microsoft Excel** (versão desktop recomendada para pleno funcionamento das macros, segmentadores e elementos interativos).
3. Navegue utilizando a coluna de menu lateral para alternar as visões dos *Big Numbers* e gráficos em tempo real.

---

## 💡 Aprendizados e Competências

- Estruturação e tratamento de bases de dados de assinaturas/SaaS no Excel.
- Separação de camadas (Model/View) ocultando abas de apoio para entregar um produto final executivo.
- Criação de interfaces interativas (*Dashboard UI*) com menus clicáveis, *Big Numbers* e gráficos dinâmicos.
- Resolução de problemas de negócio com Tabelas e Fórmulas Dinâmicas.
- Documentação de portfólio técnico e controlo de versão com Git e GitHub.
