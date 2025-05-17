🚀 Desafio Data Science - TelecomX

🎯 Objetivo
Realizar um processo completo de ETL (Extração, Transformação e Carga) dos dados da TelecomX, seguido por uma análise exploratória detalhada para identificar padrões de churn (cancelamento de clientes) e gerar insights valiosos.

1️⃣ Extração
📥 Como fizemos?

Dados obtidos diretamente via API no formato JSON.

Dados carregados em um DataFrame do pandas para manipulação prática.

Colunas com dados aninhados (tipo JSON) foram identificadas para posterior expansão.

2️⃣ Transformação
🔧 O que foi feito?

Explodimos os campos aninhados em colunas planas, para facilitar análise.

Convertidos valores numéricos para os tipos corretos (float, int).

Tratamos valores faltantes, substituindo por medianas ou valores padrão.

Padronizamos textos, convertendo tudo para minúsculas e removendo espaços.

3️⃣ Carga e Análise
📊 Vamos aos dados!

Montamos um DataFrame final com todas as informações normalizadas.

Realizamos análise exploratória para:

Ver distribuição de churn (quem saiu x quem ficou).

Entender perfil do cliente (tempo de contrato, serviços usados).

Avaliar impacto do tipo de contrato, método de pagamento e outras variáveis.

Criamos gráficos para visualizar tendências e padrões.

4️⃣ Relatório Final
📄 Insights importantes:

📉 Clientes com contrato mensal têm maior probabilidade de churn.

⏳ Maior tempo de permanência está associado à retenção do cliente.

💳 Métodos de pagamento influenciam na fidelidade dos clientes.

📺 Serviços como streaming e suporte técnico também impactam o comportamento de cancelamento.
