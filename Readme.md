🚚 Supply Chain & Logistics Intelligence Dashboard
📌 Visão Geral do Projeto
Este dashboard foi desenvolvido para fornecer uma visão 360º de uma operação de Supply Chain, transformando dados brutos de logística em decisões estratégicas. O projeto aborda desde a saúde financeira (receita e lucro) até a eficiência operacional e o comportamento do cliente.

Nível do Projeto: Profissional / Pleno

Foco: Supply Chain, Prevenção de Fraudes e Experiência do Cliente.

🏗️ Arquitetura de Dados & ETL
Um diferencial técnico deste projeto é a sua escalabilidade.

Simulação de Ambiente Corporativo: O processo de ETL (Linguagem M) foi estruturado via pastas locais, simulando uma arquitetura de SharePoint/Data Lake. Isso permite que o relatório seja atualizado automaticamente apenas adicionando novos arquivos às pastas.

Tratamento de Dados: Limpeza de duplicidades, tipagem de dados e criação de chaves únicas para garantir que clientes homônimos (como o caso real de IDs distintos para o mesmo nome) fossem contabilizados corretamente.

📊 Estrutura do Dashboard
1. Visão Executiva (Financeira)
Focada em KPIs de alto nível para a diretoria.

Métricas Principais: Receita Total, Margem de Lucro e Ticket Médio.

Análise Geográfica: Substituição de mapas tradicionais por gráficos de alta densidade de informação para rápida tomada de decisão.

Painel de Filtros: Menu lateral dinâmico (UI Moderna) para segmentação por categoria e período.

2. Visão Operacional (Logística)
Focada na eficiência da cadeia de suprimentos.

Lead Time: Análise do tempo de entrega real vs. previsto.

Gap de Entrega: Identificação de gargalos logísticos.

Prevenção de Perdas: Monitoramento de pedidos com status de "Suspeita de Fraude", permitindo uma ação proativa do time de risco.

3. Visão de Clientes (Customer Insights)
Focada em entender quem é o consumidor.

Ranking de Fidelidade: Identificação dos Top Clientes por volume de compra e lucro.

Segmentação: Quebra por tipo de pagamento (Débito, Transferência, etc.) e segmento de mercado.

🎨 Diferenciais de UI/UX (Design)
Design Minimalista: Uso de tons de Azul Marinho e Teal (Verde Água), baseados na identidade visual da marca.

Navegação Intuitiva: Menu lateral para alternância de telas e botão para "Limpar Filtros".

Alta Performance: Visual limpo com poucos elementos pesados, garantindo carregamento rápido.

🛠️ Tecnologias Utilizadas
Power BI Desktop

Power Query (Linguagem M) para ETL avançado.

DAX para métricas de inteligência de negócio.

Figma (ou técnicas de design interno) para o layout da capa e background.

📈 Conclusão e Insights
O projeto revelou que a eficiência logística impacta diretamente a retenção de clientes. A implementação da análise de fraude permitiu identificar que certas regiões demandam políticas de segurança mais rígidas, protegendo a margem de lucro da operação.