# 🛒 Sprint 3: Análise Exploratória de Pedidos Instacart

## 📝 Descrição
Nesta etapa, realizamos a preparação e análise exploratória de um conjunto de dados da plataforma Instacart. O objetivo foi limpar os dados e entender padrões de comportamento dos usuários nos pedidos realizados.

## 🧪 Etapas Realizadas
- Correção de carregamento dos arquivos CSV com `sep=";"`
- Verificação de tipos de dados e conversões adequadas
- Tratamento de valores ausentes:
  - Preenchimento de `product_name` com `"Unknown"`
  - Substituição de valores ausentes em `add_to_cart_order` por `999`
- Remoção de duplicatas completas e parciais
- Verificação de outliers e análises temporais:
  - Distribuição de pedidos por hora do dia
  - Distribuição de pedidos por dia da semana
  - Intervalo de tempo entre pedidos

## 📊 Visualizações Criadas
- Gráfico de pedidos por hora do dia
- Gráfico de pedidos por dia da semana
- Histograma do tempo entre pedidos

## 🧠 Habilidades Desenvolvidas
- Limpeza e padronização de grandes volumes de dados
- Visualização de dados com `matplotlib`
- Interpretação de padrões de comportamento em dados de consumo

## ✅ Conclusão
Através da limpeza e análise dos dados do Instacart, conseguimos traçar perfis de consumo ao longo da semana e identificar padrões relevantes para negócios de varejo.
