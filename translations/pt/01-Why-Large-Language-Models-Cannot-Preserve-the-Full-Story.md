> Português: Tradução assistida por máquina da fonte oficial em inglês. Correções no idioma nativo são bem-vindas. [Inglês](../../01-Why-Large-Language-Models-Cannot-Preserve-the-Full-Story.md) | [Todos os idiomas](../README.md)

# Por que grandes modelos de linguagem não conseguem preservar a história completa

![As peças salvas perdem valor quando suas fontes, relacionamentos e história são separados.](../../illustrations/ordinary-storage-loses-context.png)

Os modelos de linguagem pagos mais fortes usados ​​durante a construção deste projeto poderiam fazer um trabalho impressionante. Eles poderiam escrever, pesquisar, explicar e ajudar a resolver problemas difíceis. Eles ainda não conseguiram preservar toda a história por trás de um longo projeto.

Uma resposta posterior pode lembrar a conclusão, mas perder as tentativas fracassadas, as correções e as evidências que levaram a ela. As instruções anteriores poderiam desaparecer quando uma conversa se tornasse muito longa. O modelo continuaria escrevendo como se nada de importante tivesse sido perdido.

Isso é um problema sério quando a história que falta representa o tempo, o conhecimento ou a experiência de alguém.

## Arquivos não são suficientes

Uma pasta pode conter todas as notas, conversas, imagens e tarefas, ao mesmo tempo que perde a história que os conecta.

Meses depois, uma pessoa pode precisar saber:

- o que iniciou o trabalho
- quais ideias foram consideradas
- por que uma tentativa falhou
- que evidências mudaram o plano
- qual conclusão é atual
- o que ainda é desconhecido
- por que uma nota antiga é importante agora

A pesquisa pode encontrar um arquivo com palavras semelhantes. Não pode responder de forma confiável a essas perguntas. Enviar uma pilha maior de arquivos para um modelo de linguagem também não cria memória permanente. O serviço vê o que foi selecionado para aquela solicitação. Quando a solicitação terminar, as conexões úteis poderão desaparecer novamente.

## O treino também perde a configuração original

Os modelos de linguagem aprendem padrões de enormes coleções de trabalho humano. É isso que os torna úteis. É também por isso que não podem funcionar como um arquivo fiel de tudo o que os moldou.

As ideias de um livro, artigo, conversa, tradução ou comunidade misturam-se com ideias de muitos outros. O modelo não mantém intacta cada obra com seu autor, propósito, público, evidências, discordância e correções posteriores anexadas.

A obra original ainda pode existir em outro lugar. Um fornecedor também pode manter cópias separadas. A perda descrita aqui acontece dentro do modelo treinado: ele mantém a influência útil do trabalho, mas não consegue reconstruir o significado humano completo em torno dele.

Repetir uma frase não é o mesmo que preservar esse significado. Um modelo pode reproduzir palavras familiares sem saber por que foram escritas, que situação descreveram, de quem estava faltando visão ou o que aconteceu depois.

## A história perdida também esconde preconceitos

Nenhum modelo de linguagem aprendido no mundo inteiro.

Seu conhecimento reflete o que foi escrito, preservado, coletado, traduzido, licenciado, rotulado e selecionado. Também reflete o que estava faltando. Algumas línguas e comunidades têm muito mais material publicado do que outras. Os arquivos preservam as opiniões de instituições poderosas com mais frequência do que o conhecimento privado, local ou oral.

As pessoas que constroem o modelo fazem mais escolhas sobre o que remover, recompensar, desencorajar ou tratar como uma boa resposta. As regras do produto adicionam outra camada. Uma resposta finalizada pode carregar todas essas influências sem mostrar qual delas afetou uma frase específica.

Uma citação encontrada durante uma nova solicitação não revela esse histórico completo. Mostra uma fonte usada ou nomeada para aquela solicitação, não tudo que ensinou ao modelo como interpretar o assunto.

## O que este projeto mantém

Robot Brain mantém a fonte antes de pedir ajuda a qualquer modelo para interpretá-la. A fonte não muda quando um resumo, correção ou nova interpretação é adicionado.

O trabalho posterior é salvo ao lado dele com uma data e um link para a passagem relevante. Uma tentativa fracassada pode permanecer visível. Uma conclusão corrigida pode apontar para as evidências que a alteraram. Se o motivo de uma mudança for desconhecido, o registro diz isso.

Quando alguém precisa de uma resposta ou documento, o construtor de solicitações reúne a parte desse histórico necessária para o trabalho. O resultado pode ser menor que o registro completo sem a pretensão de substituí-lo.

Um modelo de linguagem pode ajudar nesse resultado. Não pode apagar as fontes, reescrever o passado ou fazer com que uma suposição não fundamentada se torne parte do registo aceite.

## O teste prático

Um resultado útil deve permitir ao leitor responder a quatro perguntas:

1. O que aconteceu?
2. Que evidências apoiam esse relato?
3. O que mudou, falhou ou permanece controverso?
4. O que ainda é desconhecido?

Se o registo não puder responder a uma destas questões, uma linguagem refinada não deverá esconder a lacuna.
