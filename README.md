# Dashboard Streamlit

Este projeto utiliza o Streamlit para criar um dashboard interativo para visualização de dados.

## Pré-requisitos
- Python 3.x instalado

## Configuração
1. Crie e ative um ambiente virtual:
   ```bash
   python -m venv venv
   ```
   # Ativar no Windows
   ```bash
   venv\Scripts\activate
    ```

   # Ativar no macOS/Linux
   source venv/bin/activate
   ```
2. Caso ocorra um erro ao executar o PowerShell, execute:
    ```bash
    Set-ExecutionPolicy RemoteSigned
    ```
3. Instale as dependências:
   ```bash
   pip install requests
   pip install streamlit
   pip install pandas
   pip install plotly
   ```

## Como executar
1. Ative o ambiente virtual.
2. Execute o comando:
   ```bash
   streamlit run Dashboard.py
   ```
3. Acesse o dashboard em [http://localhost:8501](http://localhost:8501).

# Principais arquivos
1. ```Dashboard.py```: Arquivo principal do Streamlit.
2. ````pages/Dados Brutos.py```: Arquivo adicional do Streamlit localizado na pasta ```pages```.

## Licença
Licenciado sob a [MIT License](LICENSE).