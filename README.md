Trabalho da Universidade catolica de brasilia 3º (terceiro) semestre. Disciplina: Estrutura de dados

Instruções:
Este trabalho prático tem por finalidade a implementação, em C, de algoritmo para leitura e manipulação de dados formatados de um arquivo texto (csv).

Formato dos dados:
No arquivo processo_043_202409032338, cada linha (com exceção da primeira) contém dados relacionados a processos que tramitam na justiça eleitoral de uma unidade da federação e que incluem os campos id (identificador), numero (número do processo), data_ajuizamento (data em que o processo foi iniciado), id_classe (classe vinculada ao processo), id_assunto (assunto vinculado ao processo) e ano_eleicao (ano da eleição que ensejou a abertura do processo). A seguir, observe que os atributos são separados por vírgula:

"id","numero","data_ajuizamento","id_classe","id_assunto","ano_eleicao"

638633058,"00000103020166070018",2016-04-20 15:03:40.000,{12554},{11778},0

405287812,"06000824620216070000",2021-07-01 16:33:15.000,{12377},{11778},2020

405277919,"00000238420156070011",2015-05-18 16:49:33.000,{11541},{11778},0

O que deve ser feito:
O programa a ser construído deve ler dados de cada processo, identificando cada um dos atributos acima para, a seguir, realizar as seguintes operações:

Ordenar, em ordem crescente, o conjunto de dados a partir do atributo “id”;
Ordenar, em ordem decrescente, o conjunto de dados a partir do atributo “data_ajuizamento”;
Contar quantos processos estão vinculados a um determinado “id_classe”;
Identificar quantos “id_assuntos” constam nos processos presentes na base de dados;
Listar todos os processos que estão vinculados a mais de um assunto; e
Indicar a quantos dias um processo está em tramitação na justiça.
Observações:
Deve ser implementado o Tipo Abstrato de Dados (TAD) “Processo”, seguindo diretrizes dadas em aula.
O código-fonte deve ser estruturado em três arquivos, conforme explicitado na aula TAD.
Não podem ser usadas funções de bibliotecas C para pesquisar e ordenar o conjunto.
Os dados devem ser organizados em vetores de structs.
Os atributos são separados por vírgula.
Os atributos multivalorados multivalorados estão delimitados por “{}”.
As respostas dos itens 1 e 2 devem ser armazenados em arquivo “cvs”, mantendo cabeçalho.
Deve ser implementada 1 (uma) função para resolver cada item indicado acima.
