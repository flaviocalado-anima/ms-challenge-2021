# Desafio Final - Trilha Engenheiro IA Microsoft

Olá! Bom dia, boa tarde ou boa noite!

Este é um desafio criado para testar os seus conhecimentos em Machine Learning e nos serviços cogntivos da Azure.

Leia atentamente todo o conteúdo desse documento antes de começar qualquer execução!

## Instruções gerais

O desafio consiste em uma série de problemas que envolvem Machine Learning e Inteligência Artificial aplicados ao contexto da educação.

Você e seu time devem escolher quais problemas desejam solucionar, pode ser um único problema, podem ser vários. Vocês escolhem!

Caso não possuam créditos na Azure, você e sua equipe podem optar por outras ferramentas de aprendizagem de máquina.

Cada desafio possui uma pontuação associada. Se a equipe soluciona corretamente o desafio, leva a pontuação dele.

A entrega desse teste deve ser feita através do seu repositório Git pessoal (GitHub, Bitbucket, etc) de um membro da equipe. Vocês deverão encaminhar o link do repositório através do formulário que será enviado durante a próxima semana.

Os resultados finais das previsões dos desafios deverá estar no arquiv README.md do repositório

Qualquer dúvida que tenha, basta entrar em contato conosco.

## Critérios para avaliação
- Pontuação obtida pela equipe
- Quantidade dos desafios concluidos
- Complexidade dos desafios concluidos

# Realizando a Análise dos Dados do Enem

Vá ao site de microdados do ENEM e baixe o dataset referente ao ano de 2019

 https://download.inep.gov.br/microdados/microdados_enem_2019.zip





## Desafio 1 - (3 pontos) Existe alguma correlação entre as notas das provas objetivas? Comente.



### Tarefa
Quem é bom em matemática, também vai bem em ciências da natureza? 
Nesse problema, você selecionará os campos da prova objetiva:

NU_NOTA_CN	Nota da prova de Ciências da Natureza
NU_NOTA_CH	Nota da prova de Ciências Humanas
NU_NOTA_LC	Nota da prova de Linguagens e Códigos
NU_NOTA_MT	Nota da prova de Matemática

Você deverá realizar uma análise de regressão para descobrir se é possível prever a nota da prova de Ciências da Natureza caso se saiba a nota de outra.

### Resultado
Você deverá mostrar a previsão de uma nota de Ciências da Natureza com base em uma nota da prova de Matemática


## Desafio 2 - (5 pontos) Escolha um estado da federação e clusterize os estudantes do enade com base em suas respostas ao questionário socioeconômico.


Material de referência: https://docs.microsoft.com/pt-br/learn/modules/create-clustering-model-azure-machine-learning-designer/

### Tarefa
Neste problema, você deverá selecionar alguns campos do questionário sócioeconomico Renda Mensal (Q006), acesso a internet (Q025) e a nota final da redação (NU_NOTA_REDACAO) e agrupar os estudantes

### Resultado
Você deverá mostrar a previsão do cluster de um estudante com base nos dados de Renda Mensal, acesso a internet e nota final da redação informados



# Realizando a Análise dos Dados do ENADE

Para este desafio, você deverá ir até o site do INEP e baixar os Microdados do ENADE 2019. Disponível em: https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/enade

## Desafio 3 - (3 pontos) Clusterizando os dados do ENADE

Material de referência: https://docs.microsoft.com/pt-br/learn/modules/create-clustering-model-azure-machine-learning-designer/

Entender quais fatores influenciam na nota dos estudantes do ENADE pode oferecer insights sobre os grupos sociais e suas notas.

### Tarefa
Neste desafio, você deverá utilizar os algoritmos de clusterização para agrupar os estudantes em torno da sua renda (QE_I08), suas horas de estudo (QE_I23) e sua nota geral (NT_GER).

### Resultado
Você deverá mostrar a previsão do cluster de um estudante com base nos dados de Renda Mensal, suas horas de estudo e sua nota geral

## Desafio 4 - (6 pontos) Criando um preditor de notas no ENADE

Será que as notas no ENADE vão aumentar ou diminuir? Acesse os microdados das provas anteriores 2019, 2018, 2017, 2016 e 2015 e faça uma análise de regressão para verificar se a nota geral (NT_GER) tendem a aumentar ou a diminuir nos anos de 2020 e 2021.

### Resultado
Você deverá mostrar a previsão das notas do ENADE para os anos de 2020 e 2021


# Considerações finais

Aqui, finalizamos o teste! Espero que tenha conseguido fazer tudo com bastante carinho e atenção! Aguardamos pelo seu envio e, assim que fizermos a avaliação, iremos te dar um retorno com feedbacks a respeito.

Esperamos também que tenha gostado e que tenha aprendido um pouco conosco!

Até breve!