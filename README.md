# Meu primeiro PORTFÓLIO 

Sistema de Classificação de Risco para concessão de Empréstimos 

# PROBLEMA DO NEGÓCIO 

  Nesse projeto, eu construí um sistema de classificação de risco empréstimo que a partir de dados do cliente a máquina preditiva vai avaliar e dizer se o risco para este empréstimo é Risco Alto, Risco Médio ou Risco Baixo. 

  Então a partir da resposta do modelo de machine learning, cabe a pessoa que está avaliando a solicitação do empréstimo do cliente aceitar ou negar o empréstimo. 

# FONTE DOS DADOS 

LINK: https://archive.ics.uci.edu/index.php 

O nome da base de dados "**risco.csv**" originada por meio dos dados da **UCI Machine Learning**. Eu modifiquei o nome da base de dados de 'risco.csv' para 'BaseDados' apenas para ficar mais fácil para quem for ver todo este projeto. 

# ARQUITETURA DOS DADOS (AD) 

* **id_cliente**  : Número de identificação única do cliente 

* **inad**    : Índice de inadimplência do cliente 

* **Saldo_contas**: Índice referente aos saldos das contas corrente, poupança e aplicações do cliente 

* **Class_Renda** : Índice referente à classificação do cliente de acordo com sua renda. 

* **Anotações**   : Índice referente às anotações externas à empresa, tais como anotações SERASA / SPC / BACEN  

* **Risco**  : Risco do Cliente atribuído dadas as variáveis de análise do cliente 

# DEPLOY DO PROJETO 

1º - Realizar o download da ferramenta "Visual Studio Code" no link abaixo e instalei: 

https://code.visualstudio.com/ 

2º - Criar um diretório chamado "app" no seu Drive "C" e uma pasta "Projeto", e salvei nele todos os arquivos do projeto 

3° - Depois abrir o VS Code e clicar no menu "File", depois "Open Folder" e vai navegar até o diretório "C:\app\Projeto" 

4° - Vai no menu "terminal", depois "New Terminal". e instalar as seguintes bibliotecas; 

a) pip install plotly  +  tecla enter 

b) pip install streamlit  +  tecla enter 

5º - Executar o seguinte comando; streamlit run app_risco.py 

OBS: O sistema era abrir no seu navegador web 

  
FIM 
