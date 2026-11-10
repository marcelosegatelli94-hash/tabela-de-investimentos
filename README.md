# Tabela de Investimentos e Futuro

Ferramenta desenvolvida em Excel para simulação de aportes financeiros, projeção de patrimônio e distribuição de investimentos por perfil de risco.

## 📌 Perguntas que a ferramenta responde e onde aparecem
1. **Quanto terei em 2, 5, 10, 20 e 30 anos?** As respostas aparecem na tabela de **Cenários**, calculadas com base no valor do aporte mensal e na taxa de rendimento informada.
2. **Quanto vou receber de dividendos mensais?** Apresentado na coluna de **Dividendos** dentro da tabela de cenários.
3. **Como distribuir o valor investido mensalmente entre diferentes ativos?** Exibido na seção de **Perfil**, detalhando quanto vai para cada categoria de investimento com base no percentual escolhido.
4. **Qual será o patrimônio acumulado ao final do período escolhido?** Exibido no bloco de **Investimento Mensal** (Patrimônio Acumulado).
5. **Qual é o impacto de alterar o prazo ou a taxa de juros?** Reflete automaticamente nos cenários de longo prazo.

---

## 🧮 Como as funções VF e PROCV entram nos cálculos
* **VF (Valor Futuro):** Utilizada para calcular o montante acumulado ao longo do tempo com base em pagamentos periódicos (aportes mensais) e uma taxa de juros constante.
* **PROCV:** Utilizada na tabela de perfil para buscar e associar dinamicamente os percentuais e valores direcionados a cada tipo de ativo de acordo com o perfil de investidor selecionado.

---

## 🏷️ Intervalos Nomeados
Foram criados intervalos nomeados na planilha para facilitar as fórmulas e deixar as referências mais limpas e fáceis de entender.

---

## 📊 Percentuais de cada Perfil
A planilha contempla perfis de investimento (como Conservador, Moderado e Agressivo). Os percentuais definem a fatia alocada em cada ativo e a soma de cada perfil totaliza obrigatoriamente **100%**.

---

## 🛠️ O que foi mudado em relação à ferramenta do Expert
* Personalização do design visual e estruturação dos blocos de cenários e dividendos para facilitar a leitura rápida.
