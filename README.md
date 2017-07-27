# Configurando turma no Moodle para ME414

### Abrir turma

1- http://www.ggte.unicamp.br

2- Ambiente: Ensino Aberto

<center><img src="figuras/A.png" width=500></center>


2- Login: usuário DAC

<center><img src="figuras/B.png" width=500></center>


3- Carregar disciplinas

<center><img src="figuras/C.png" width=500></center>


4- Escolher a disciplina, carregar, confirmar.

### Cadastrando PEDs na turma

Se os PEDs estiverem trabalhando conjuntamente nas turmas, o ideal é que se cadastre todos na sua turma.


### Comunicação com os alunos

A página já vem com o quadro de **Avisos** ativa, que pode ser usada para **mandar mensagens para toda a classe**.

<center><img src="figuras/D.png" width=500></center>



<center><img src="figuras/E.png" width=500></center>

Opcionalmente, selecionar: **Enviar email em seguida** (caso contrário o aluno só lerá a mensagem ao entrar no Moodle)


<center><img src="figuras/F.png" width=500></center>


### Lista de presença

1- Ative a edição:

<center><img src="figuras/G.png" width=500></center>


2- Adicione o recurso:

<center><img src="figuras/H.png" width=500></center>


3- Selecione **Presença**:

<center><img src="figuras/I.png" width=500></center>

4- Nota **Nenhum**:

<center><img src="figuras/J.png" width=500></center>

5- Salvar e retornar ao curso

6- Clique em **Presença**

7- Adicionar Sessão

<center><img src="figuras/K.png" width=500></center>

8- Configure com a data inicial, horário inicial e final da aula e depois configure a sessão de repetição de sessões.

<center><img src="figuras/L.png" width=500></center>

9- Em **Configurações** coloque 1 ponto para **Presente**, exclua **Atrasado**, **Dispensado**

<center><img src="figuras/M.png" width=500></center>


10- Resultado:

<center><img src="figuras/N.png" width=500></center>

11- Quando quiser fazer a chamada durante a aula, basta clicar em **Presença**, escolher a sessão e registrar presença.

<center><img src="figuras/O.png" width=500></center>


### Tópico de Informações Gerais


1- Renomeie o **Tópico 1** e depois clique em **Editar** caso queira colocar as informações diretamente.


<center><img src="figuras/P.png" width=500></center>

<center><img src="figuras/Q.png" width=500></center>

2- Outra opção é colocar um pdf com as informações gerais, ou link para uma página, etc... Para isso, basta **adicionar uma atividade ou recurso**

<center><img src="figuras/R.png" width=500></center>


### Livro de Notas


A configuração deste exemplo se refere ao seguinte critério de avaliação:

<center><img src="figuras/T.png" width=800></center>



<center><img src="figuras/S.png" width=500></center>

**Prova 1**: adicione **item de nota**

<center><img src="figuras/U.png" width=500></center>

<center><img src="figuras/V.png" width=500></center>

Repita para **Prova 2**


**Atividade 1**: uma categoria (pasta) em que todas as atividades ficarão dentro desta categoria, com o mesmo peso cada.

<center><img src="figuras/X.png" width=500></center>


<center><img src="figuras/Y.png" width=500></center>

IMPORTANTE: Clicar em **Mostrar mais** e desabilitar **Desconsiderar notas vazias** (caso contrário ele calcula a média ponderada descartando *missing values*).

<center><img src="figuras/Z17.png" width=500></center>



Repita para **Atividade 2**



Crie a **Média Geral MG**, através de **adicione um ITEM de nota** e modifique a nota máxima para 10


<center><img src="figuras/W.png" width=500></center>

Configure a fórmula de **MG**:

<center><img src="figuras/Z.png" width=500></center>

Primeiro:

<center><img src="figuras/Z1.png" width=500></center>

Em seguinda, insira a fórmula:

<center><img src="figuras/Z2.png" width=500></center>

Crie a **Média Final MF**, através de **adicione uma CATEGORIA de nota** e modifique a nota máxima para 10.

Crie o **Exame**, através de **adicione um ITEM de nota** e modifique a nota máxima para 10.


Coloque **MG** e **Exame** dentro da categoria **MF**.

Começando por **MG**:

<center><img src="figuras/Z3.png" width=500></center>


<center><img src="figuras/Z4.png" width=500></center>


Repita a mesma coisa para **Exame**. Resultado:

<center><img src="figuras/Z5.png" width=500></center>


Oculte a coluna **Total do Curso**, pois não será utilizada.

<center><img src="figuras/Z6.png" width=500></center>

**IMPORTANTE** : não preencha a coluna **Exame** para alunos que não ficaram de exame. Para os que ficaram de exame, mas não compareceram, preencha como 0. Desta maneira, a coluna **MF total** irá conter **MF** calculada corretamente automaticamente.


### Inserindo notas de aula

Renomeie o tópico de acordo com a preferência.

<center><img src="figuras/Z8.png" width=500></center>

Duas opções: **adicionar recurso** ou **editar**.

Caso **adcionar recurso** seja selecionada, há diversas opções, por exemplo, **adicionar URL**:


<center><img src="figuras/Z9.png" width=500></center>


<center><img src="figuras/Z10.png" width=500></center>

Resultado:

<center><img src="figuras/Z11.png" width=500></center>


### Importando Banco de Questões - Arquivos XML

Para questões geradas através de programação, utilizando o pacote exams do R

<center><img src="figuras/Z12.png" width=500></center>

<center><img src="figuras/Z13.png" width=500></center>

Para acessar as questões importadas:


<center><img src="figuras/Z14.png" width=500></center>

Depois selecione pelo menu:

<center><img src="figuras/Z15.png" width=500></center>

Questões selecionadas para verificação:

<center><img src="figuras/Z16.png" width=500></center>

Neste exemplo, a questão Q1freq tem 400 versões.

### Criando uma Questão - Arquivos XML

Este exemplo se refere a um exercício que utilizará uma questão gerada através de programação, utilizando o pacote exams do R. É preciso que o  banco de questões já tenha sido importado (instruções acima).

<center><iframe width="560" height="315" src="https://www.youtube.com/embed/i9NwfSYApyg" frameborder="0" allowfullscreen></iframe></center>

A cada tentativa desta questão (é possível configurar o máximo de tentativas) o aluno receberá, ao acaso, uma versão da mesma questão.

