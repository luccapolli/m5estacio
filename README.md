# MISSÃO PRATICA NIVEL 3 - ESTÁCIO
Missão Prática | Tratando a imensidão dos dados  💻

Através dessa atividade o aluno realizará a limpeza de um conjunto de dados,
tornando-o apto a ser usado em tarefas de mineração/análise de dados.

Contextualização

Como Analista de Dados, você recebeu, em um novo projeto, um conjunto de dados.
Sua principal tarefa é tratar os dados desse conjunto a fim de que possam ser
utilizados para a descoberta de conhecimento através de sua posterior análise e
interpretação. Para tal tarefa, você deverá utilizar a linguagem Python e a biblioteca
Pandas. O passo-a-passo de todo o processo de tratamento dos dados é apresentado a
seguir, no roteiro de prática.

Roteiro de prática 📝

- Material necessário para a prática

Interpretador Python ou ambiente de codificação (JupyterLab / Jupyter Notebooks /
Google Colab);
Biblioteca pandas;
Editor ou IDE (caso vá utilizar o interpretados python para execução dos scripts
criados).
 

- Procedimentos

 

Para essa atividade você deverá, obrigatoriamente, utilizar o conjunto de dados
(fornecido anteriormente, na seção “Contextualização”) composto pelas colunas
ID;Duration;Date;Pulse;Maxpulse;Calories
Crie um novo arquivo/script;
Leia o conteúdo do CSV fornecido, atentando-se para a necessidade ou não de
incluir parâmetros adicionais como os relativos ao separador dos dados, a engine e
o enconding;
Atribua os dados lidos a uma variável;
Verifique se os dados foram importados adequadamente:
Imprima as informações gerais sobre o conjunto de dados;
Imprima as primeiras e últimas N linhas do arquivo.
Crie uma nova variável e atribua a ela uma cópia do conjunto de dados original
(variável criada no passo 4);
Nessa nova variável, contendo uma cópia dos dados:
Substitua todos os valores nulos da coluna ‘Calories’ por 0;
Imprima o conjunto de dados para verificar se a mudança acima foi aplicada com
sucesso;
Ainda na nova variável:
Substitua os valores nulos da coluna ‘Date’ por ‘1900/01/01’;
Imprima o conjunto de dados e confira se a mudança foi aplicada com sucesso;
Transforme os dados da coluna ‘Date’ em datetime usando o método
‘to_datetime’;
Tendo seguido todas as instruções anteriores, ao executar o passo anterior você
deverá ter encontrado um erro informando que o valor ‘1900/01/01’ não
corresponde ao formato ‘%Y/%m/%d’. Para resolver esse problema:
Substitua, na coluna ‘Date’, o valor ‘1900/01/01’ por ‘NaN’;
Utilizando o método ‘to_datetime’, repita o passo de transformação dos dados da
coluna ‘Date’ para datetime;
Imprima o conjunto de dados para verificar se as mudanças acima foram
aplicadas com sucesso;
Nesse ponto, você deverá ter esbarrado em outro erro, informando agora que o valor
"20201226" não corresponde ao formato "'%Y/%m/%d'" . Você precisará, agora, na
coluna ‘Date”, transformar especificamente esse valor, atualmente uma string, para
o formato datetime. Para isso você deverá combinar os métodos ‘replace’ e
‘to_datetime’;
Após o passo anterior, execute novamente a transformação de todos os dados da
coluna ‘Date’ para o formato datetime (usando o to_datetime). Imprima o conjunto
de dados atual para verificar se todas as transformações foram executadas com
sucesso;
Por fim, remova os registros contendo valores nulos. Nesse ponto, apenas a coluna
‘Date’ possui um registro que atende a essa premissa (linha 22). Logo, utilize-a
como base para realizar a transformação solicitada;
Imprima o dataframe e verifique se todas as transformações foram executadas
conforme solicitado nos passos anteriores.
- Resultados esperados  ✨

O resultado esperado dessa microatividade é verificar se o aluno possui conhecimentos
básicos sobre python – mais precisamente sobre a biblioteca Pandas, sendo capaz de
utilizá-la na leitura e manipulação de dados, realizando tarefas como a leitura de
arquivos externos, a utilização de dataframes em memória, a exibição de informações e
dados, assim como o tratamento/transformação dos mesmos.
