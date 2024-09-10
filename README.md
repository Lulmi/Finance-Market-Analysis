# Finance-Market-Analysis

---

## Project Overview: Market Analysis and Report Generation

This project is structured to provide a detailed and organized view of the performance of selected stocks over the past six months. The main steps and approaches employed in this project are outlined below:

1. **Library Installation and Import**
   Initially, the necessary libraries for data analysis and visualization were installed and imported. `yfinance` was used to download historical stock data, `pandas` for data manipulation, and `matplotlib` with `mplcyberpunk` for creating performance graphs.

2. **Data Collection**
   Market data was collected for a specific set of stocks, including companies like AES Brasil, Alupar, Banco do Brasil, Itaúsa, Klabin, SANEPAR, TAEE, and Kilima Suno 30. Data was downloaded for a six-month period. This step is crucial for obtaining up-to-date information on stock price behavior.

3. **Data Treatment**
   The collected data was processed to extract only the adjusted closing prices of the stocks. It was then cleaned to remove any missing values. Columns were renamed to facilitate the identification of stocks in subsequent reports and graphs.

4. **Performance Graphs Creation**
   For each stock, graphs illustrating the price variation over the past six months were generated. The `cyberpunk` style was used to create modern and visually appealing graphs. The graphs were saved as images, making them easy to include in reports and presentations.

5. **Daily Return Calculation**
   Daily returns for the stocks were calculated based on the percentage change in adjusted closing prices. Calculations were made for five-day periods, providing insight into recent stock performance. The most recent returns were extracted and formatted for easy interpretation.

6. **Report Preparation and Sending**
   An email was drafted with a summary of the most recent returns for each stock. The email included the generated graphs as attachments, providing a clear and detailed view of stock performance to the recipient. The email sending was automated using the `win32com` library, ensuring efficient delivery of the report.

This project showcases advanced skills in finance and data analysis, highlighting the ability to manipulate financial data, create informative visualizations, and automate the generation and sending of reports. The use of libraries like `yfinance` and `matplotlib`, along with integration with email tools, demonstrates effective use of modern techniques in financial data analysis and communication.

---

## Visão Geral do Projeto: Análise de Mercado e Geração de Relatórios

Este projeto está estruturado para fornecer uma visão detalhada e organizada do desempenho de ações selecionadas ao longo dos últimos seis meses. As principais etapas e abordagens empregadas neste projeto estão descritas abaixo:

1. **Instalação e Importação de Bibliotecas**
   Inicialmente, foram instaladas e importadas as bibliotecas necessárias para a análise de dados e visualização. Utilizou-se o `yfinance` para baixar dados históricos de ações, `pandas` para manipulação dos dados e `matplotlib` com `mplcyberpunk` para a criação dos gráficos de desempenho.

2. **Coleta de Dados**
   Os dados de mercado foram coletados para um conjunto específico de ações, incluindo empresas como AES Brasil, Alupar, Banco do Brasil, Itaúsa, Klabin, SANEPAR, TAEE e Kilima Suno 30. Os dados foram baixados para um período de seis meses. Este passo é crucial para obter informações atualizadas sobre o comportamento dos preços das ações.

3. **Tratamento de Dados**
   Os dados coletados foram processados para extrair apenas os preços de fechamento ajustados das ações. Em seguida, foram limpos para remover quaisquer valores ausentes. As colunas foram renomeadas para facilitar a identificação das ações nos relatórios e gráficos subsequentes.

4. **Criação de Gráficos de Performance**
   Para cada ação, foram gerados gráficos que ilustram a variação do preço ao longo dos últimos seis meses. Utilizou-se o estilo de visualização `cyberpunk` para criar gráficos modernos e visualmente atraentes. Os gráficos foram salvos como imagens, facilitando a inclusão em relatórios e apresentações.

5. **Cálculo dos Retornos Diários**
   Os retornos diários das ações foram calculados com base na variação percentual dos preços de fechamento ajustados. O cálculo foi feito para períodos de cinco dias, oferecendo uma visão sobre o desempenho recente das ações. Os retornos mais recentes foram extraídos e formatados para fácil interpretação.

6. **Preparação e Envio do Relatório**
   Foi criada uma mensagem de e-mail com um resumo dos retornos mais recentes de cada ação. O e-mail incluiu os gráficos gerados como anexos, proporcionando uma visualização clara e detalhada do desempenho das ações para o destinatário. O envio do e-mail foi automatizado usando a biblioteca `win32com`, garantindo que o relatório chegasse ao destinatário de forma eficiente.

Este projeto demonstra habilidades avançadas em finanças e análise de dados, destacando a capacidade de manipular dados financeiros, criar visualizações informativas e automatizar a geração e envio de relatórios. O uso de bibliotecas como `yfinance` e `matplotlib`, juntamente com a integração com ferramentas de e-mail, mostra um domínio eficaz de técnicas modernas de análise e comunicação de dados financeiros.
