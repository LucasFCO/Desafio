# Desafio
Desafio Cientista de Dados 

Instruções para execução:

1) Instalar as dependências necessarias. 
Uso do arquivo de requisitos você pode então usar o arquivo requirements.txt para instalar as mesmas versões das dependências usando o seguinte comando:

pip install -r requirements.txt

Isso instalará todas as bibliotecas e versões listadas no arquivo de requisitos.


Caso ocorra algum problema você poderá instalar manualmente pelo terminal, basta copiar e colar os seguintes comandos:

pip install ydata-profiling
pip install scikit-learn
pip install matplotlib
pip install seaborn
pip install ydata_profiling
pip install numpy
pip install folium

2) Realizar o download dos arquivos e salvar todos no mesmo diretorio.

3) Execultar os arquivos do Jupyter Notebook após assegurar que todas as bibliotecas estão instaladas.

 Basta dar um Run All.
 
 4) Para utilizar o arquivo plk basta copiar e colar o script abaixo em uma celula do  Jupyter Notebook.
 
import pickle

with open("dados_entrada.pkl", "rb") as arquivo:
   X = pickle.load(arquivo)
   
4.1) Caso deseje utilizar a base de dados do desafio basta  copiar e colar descomentar as linhas abaixo em  outra celula.

# with open("modelo.pkl", "rb") as arquivo:
#    modelo = pickle.load(arquivo)
#    previsao = modelo.predict(X)

# previsao = modelo.predict(X)

# print(len(previsao), ' - ',previsao)


O modelo.plk pode ser utilizado em outros conjunto de dados, basta voltar na parte 1 e 4.



