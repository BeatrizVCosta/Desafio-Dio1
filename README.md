# Simulador de FIIs em Excel 📈

Ferramenta desenvolvida no desafio prático da DIO (com o Expert Felipe Aguiar) para simular investimentos em Fundos Imobiliários com cara de aplicativo.

## 🎯 O que a ferramenta faz

Responde a 5 perguntas de negócio:

1. Quanto investir por mês?

2. Por quantos anos?

3. Qual a taxa de rendimento mensal?

4. Quanto de patrimônio vai acumular?

5. Quanto vai receber de dividendos por mês?

## ⚙️ Lógica e Fórmulas

* **VF (Valor Futuro):** Calcula o patrimônio acumulado com base nos aportes mensais e prazos.

* **PROCV + Chave Composta:** Busca o percentual de cada tipo de fundo com base no perfil escolhido.

* **Intervalos Nomeados:** Substituem referências fixas (ex: `aporte`, `taxa_mensal`), facilitando as fórmulas.

## 📊 Perfis de Investidor

A planilha traz uma lista suspensa para alternar entre perfis (Conservador, Moderado e Arrojado), dividindo automaticamente o aporte entre 6 tipos de FIIs (totalizando 100% em cada perfil).



Feito por BeatrizVCosta | Desafio DIO 🚀
