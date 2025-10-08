 📈 Análise de Câmbio Histórico (USD-BRL)

Este projeto realiza a coleta, armazenamento e visualização de dados históricos da taxa de câmbio do Dólar Americano (USD) para o Real Brasileiro (BRL), utilizando Python e uma API pública.

 📜 Sobre o Projeto

O objetivo é demonstrar um ciclo completo de um projeto de dados:
1.  Coleta de Dados: Busca de informações de câmbio através da API gratuita [Frankfurter](https://www.frankfurter.app/).
2.  Armazenamento: Persistência dos dados em um banco de dados local **SQLite** para consultas futuras eficientes.
3.  Análise: Utilização da biblioteca **Pandas** para carregar os dados, calcular estatísticas descritivas e uma média móvel de 30 dias.
4.  Visualização: Geração de um gráfico informativo com **Matplotlib** para exibir a série temporal da taxa de câmbio, sua tendência e os pontos de máxima e mínima no período.

 🛠️ Tecnologias Utilizadas
    Python 3
    SQLite para o banco de dados
    Requests para as chamadas de API
    Pandas para manipulação e análise de dados
    Matplotlib para a visualização gráfica

 🚀 Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone [https://github.com/SEU-USUARIO/NOME-DO-SEU-REPO.git](https://github.com/SEU-USUARIO/NOME-DO-SEU-REPO.git)
   ```
2. Navegue até a pasta do projeto:
   ```bash
   cd NOME-DO-SEU-REPO
   ```
3. Instale as dependências necessárias:
   ```bash
   pip install -r requirements.txt
   ```
4. Execute o script principal:
   ```bash
   python analise_cambio.py
   ```
   
 📊 Resultado

A execução do script irá buscar os dados do último ano, salvá-los no banco `cambio_historico.db` e exibir um gráfico como este:

![Gráfico demonstrando o histórico da taxa de câmbio: USD para BRL](./grafico.png)


