# Previsão de Preços das Ações do Walmart

## Descrição

Este projeto realiza uma análise de séries temporais dos preços das ações do Walmart para prever os preços futuros com base em dados históricos. Utiliza técnicas avançadas de modelagem, incluindo ARIMA (AutoRegressive Integrated Moving Average) e LSTM (Long Short-Term Memory), para gerar previsões precisas e informar decisões de investimento.

## Dados

Os dados utilizados neste projeto são os preços históricos das ações do Walmart, abrangendo o período de 1º de março de 2000 até 2024. O arquivo CSV está disponível através do seguinte link: [Google Drive](https://drive.google.com/file/d/13SQ1N3PZtieiaVr37aK5rA8mcuQYMEHA/view).

## Dependências

Certifique-se de que as seguintes bibliotecas estão instaladas:

- `pandas`
- `numpy`
- `matplotlib`
- `statsmodels`
- `scikit-learn`
- `keras`
- `requests`

Você pode instalar essas dependências usando o seguinte comando:

```bash
pip install pandas numpy matplotlib statsmodels scikit-learn keras requests
Estrutura do Projeto

previsao_acoes_walmart.py: Código principal que carrega os dados, realiza a análise de séries temporais e gera previsões usando ARIMA e LSTM.

README.md: Este arquivo, que fornece uma visão geral do projeto.
.gitignore: Arquivo que especifica quais arquivos e pastas devem ser ignorados pelo Git.

Como Executar
1. Clone o repositório:
git clone https://github.com/seu-usuario/previsao-acoes-walmart.git
2. Navegue até o diretório do projeto:
cd previsao-acoes-walmart
3. Execute o script principal:
python previsao_acoes_walmart.py

Isso irá gerar gráficos das previsões e visualizações dos preços das ações.

Contribuição
Contribuições são bem-vindas! Se você encontrar algum problema ou tiver sugestões para melhorias, sinta-se à vontade para abrir um problema ou enviar um pull request.

Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para detalhes.
