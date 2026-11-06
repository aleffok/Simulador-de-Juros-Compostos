# 📊 Simulador Dinâmico de Independência Financeira & Juros Compostos

Um simulador financeiro interativo desenvolvido em **Microsoft Excel**, projetado para planejar investimentos de longo prazo, calcular o acúmulo de patrimônio e estimar a geração de renda passiva por dividendos[cite: 10]. 

Este projeto foi construído com foco em **experiência do usuário (UX)**, automação lógica e visual limpo (estilo *dashboard* executivo).

---

## 🚀 Funcionalidades e Destaques

* **Painel de KPIs no Topo:** Indicadores consolidados em tempo real que mostram o prazo total em meses, o capital total investido do próprio bolso, o patrimônio acumulado final e a projeção de dividendos mensais[cite: 10].
* **Tabela Dinâmica Inteligente:** Utiliza fórmulas lógicas condicionais (`SE`) para expandir ou contrair o horizonte de simulação automaticamente com base no prazo estipulado pelo usuário.
* **Formatação Condicional Automatizada:** As linhas da tabela se pintam ou ocultam de forma responsiva, eliminando "linhas fantasmas" ou rastros visuais ao alterar prazos curtos ou longos.
* **Gráfico de Evolução Integrado:** Gráfico de desempenho dinâmico que ilustra a curva de crescimento do patrimônio em contraste com o capital investido ao longo do tempo.

---

## 🛠️ Tecnologias e Conceitos Aplicados

* **Funções Financeiras do Excel:** Uso de `VF` (Valor Futuro / *Future Value*) para o cálculo preciso de juros compostos com aportes periódicos.
* **Funções Lógicas:** Estruturas aninhadas de `SE` (`IF`) para controle dinâmico de exibição de linhas e validação de prazos.
* **Design de Interfaces (Spreadsheet UX):** Ocultação de linhas de grade na área de controle, hierarquia visual clara, alinhamento de dados e cards de destaque inspirados em aplicações financeiras modernas.

---

## ⚙️ Como Utilizar

1. Faça o download do arquivo `Simulador_Financeiro.xlsx` deste repositório.
2. Abra o arquivo no Microsoft Excel (ou em softwares compatíveis como o Google Planilhas).
3. Na seção de parâmetros, insira os valores desejados:
   * **Aporte Mensal** (R$)
   * **Prazo** (em anos)
   * **Taxa de Rendimento Mensal** (%)
   * **Dividend Yield Mensal** (%)
4. Acompanhe a atualização automática dos cards de resumo, da tabela temporal mês a mês e do gráfico de evolução!

---

## 📸 Pré-visualização do Projeto

*(Insira aqui um print de tela ou o arquivo de imagem do seu painel final preenchido para ilustrar o repositório)*

---

## 💡 Sobre o Projeto
Projeto desenvolvido como parte do aprendizado prático em modelagem financeira e automação de planilhas, unindo lógica de programação e estruturação de dados corporativos.
