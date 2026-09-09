# 📊 Simulador de Investimentos em Fundos Imobiliários (FIIs)

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge)

## 📌 Sobre o Projeto

Este projeto foi desenvolvido como parte de um desafio prático da **DIO (Digital Innovation One)**, com o objetivo de aplicar conceitos fundamentais e avançados de **Microsoft Excel** no desenvolvimento de uma ferramenta interativa para simulação de investimentos em **Fundos Imobiliários (FIIs)**.

A ferramenta permite que o usuário projete o crescimento do seu patrimônio ao longo do tempo, calculando aportes, reinvestimento de dividendos e distribuição de carteira de acordo com o seu perfil de risco.

---

## 🎯 Objetivos de Aprendizagem

- [x] Criar uma ferramenta prática de simulação financeira no Excel;
- [x] Aplicar cálculos e fórmulas financeiras (juros compostos, acúmulo de patrimônio e proventos);
- [x] Construir cenários de investimento em diferentes prazos temporais;
- [x] Aplicar validação de dados e funções condicionais para personalização por perfil de risco;
- [x] Estruturar e documentar projetos técnicos de forma profissional para o GitHub.

---

## ⚙️ Funcionalidades da Planilha

### 💰 1. Entradas Editáveis (Parâmetros)
O usuário pode inserir e ajustar dinamicamente as seguintes variáveis:
- **Salário mensal** e **percentual destinado a investimentos**;
- **Aporte inicial** e **aporte mensal**;
- **Prazo do investimento** (em anos/meses);
- **Taxa de rendimento mensal estimada** ($DY$);
- **Perfil do investidor** (Conservador, Moderado ou Agressivo).

### 📈 2. Resultados Calculados
A planilha calcula e exibe de forma automatizada:
- **Total Investido do Bolso:** Soma do capital aplicado.
- **Patrimônio Acumulado Final:** Valor total incluindo rendimentos acumulados.
- **Lucro / Ganho de Capital:** Diferença entre o patrimônio acumulado e o valor investido.
- **Renda Passiva Mensal Estimada:** Valor em dividendos projetado para o final do período.

### 📅 3. Simulação de Cenários Multitemporais
Projeções comparativas automáticas para diferentes horizontes de tempo:
- **2 anos** | **5 anos** | **10 anos** | **20 anos** | **30 anos**

### 👤 4. Distribuição por Perfil de Investidor e Categorias
Sugestão de alocação de carteira baseada no perfil selecionado:
- **Conservador**
- **Moderado**
- **Agressivo**

A distribuição engloba as principais categorias do mercado imobiliário:
- 📄 **FIIs de Papel** (CRI, Títulos)
- 🏢 **FIIs de Tijolo** (Galpões, Shopping, Lajes Corporativas)
- 🔄 **FIIs Híbridos**
- 📦 **Fundos de Fundos (FOFs)**
- 🏗️ **Fundos de Desenvolvimento**
- 🏨 **Fundos de Hotelaria**

### 📊 5. Evolução Mensal e Visualização Gráfica
- Tabela detalhada mês a mês acompanhando o acúmulo de cotas e proventos reinvestidos.
- Gráfico dinâmico comparando a curva do **Total Investido vs. Patrimônio Acumulado**.

---

## 🛠️ Ferramentas e Recursos Utilizados

- **Microsoft Excel**: Construção de planilhas, dashboards e gráficos.
- **Fórmulas Financeiras e Lógicas**: `SOMA`, `PROCV` / `PROCX`, `SE`, `INT`, entre outras.
- **Validação de Dados**: Criação de listas suspensas interativas.
- **Markdown & GitHub**: Documentação técnica e versionamento do projeto.

---

## 📁 Estrutura do Repositório

```text
📦 simulador-investimentos-fii
 ┣ 📜 Simulador_Investimentos_FII.xlsx
 ┗ 📜 README.md
