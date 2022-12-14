# Máquina de estados
### O projeto tem como objetivo analisar linguagens através de automatos Deterministicos, Não deterministicos e Não deterministicos com transição vazia
A construção dos automatos foi baseada na estrutura do simulador [FSM Simulator](https://ivanzuzak.info/noam/webapps/fsm_simulator/) 


## Como Testar:

- Ao baixar o projeto acesse o caminho /scr/testes/automatos, nesse diretório armazenamos automatos dos 3 tipos para teste, caso queira adicionar outro automato recomendamos deixar nesse mesmo diretório.

- Para de fato realizar os testes acesse o arquivo main.py, na chamada da função main localizada no entrypoint escreva o nome do arquivo no lugar de "{nome_do_arquivo}" e a palavra que deseja analisar no lugar de "{palavra}", em caso de mudança na localização do arquivo passe o path de acesso no primeiro parâmetro. Por fim execute o entrypoint.

- A saída esperada para DFA's é: tipo, estrutura dos conjuntos e o resultado da análise da palavra enviada.

- Para NFA's e eNFA's a saida esperada será: tipo, tabela de transformação, estrutura do DFA gerado e o resultado da análise da palavra enviada.

# OBSERVAÇÃO:

- Representação dos estados deve ser feita com pelo menos 2 caracteres, seguindo o exemplo do simulador, Ex: S0, S1, S2. 

## Notebook

Acesse o projeto de forma detalhada através do seguinte notebook:

- [notebook_do_projeto](https://colab.research.google.com/drive/1MPs5NwAbL7cZ0uWj6A5xQa51Bixhn7ic?usp=sharing)
