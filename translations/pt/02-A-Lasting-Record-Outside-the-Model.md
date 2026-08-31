> Português: Tradução assistida por máquina da fonte oficial em inglês. Correções no idioma nativo são bem-vindas. [Inglês](../../02-A-Lasting-Record-Outside-the-Model.md) | [Todos os idiomas](../README.md)

# O que cada parte faz: e o que nenhum modelo controla

![As fontes originais sustentam uma história duradoura, enquanto as ferramentas substituíveis realizam um trabalho limitado.](../../illustrations/core-architecture-layers.png)

Robot Brain é uma coleção de partes cooperantes construídas em torno de um registro duradouro. Não é um grande modelo de linguagem, um grupo de modelos que fingem ser um, ou um serviço de chat com pesquisa extra.

A distinção é importante porque os problemas abordados provêm da solicitação de um serviço de modelo de linguagem temporário para servir como memória, pesquisador, escritor, verificador e juiz ao mesmo tempo. Este software separa esses trabalhos e mantém o histórico da pessoa fora de cada modelo.

## Salve o evento antes de interpretá-lo

O guardião da fonte salva a conversa, nota, imagem, documento, tarefa ou outro item conforme ele chega. Também salva fatos que são realmente conhecidos, como horário de chegada, origem, criador quando estabelecido e permissão quando registrado.

Um nome de arquivo, uma suposição de modelo ou uma interpretação posterior não pode se tornar silenciosamente um fato sobre a fonte. A informação faltante continua faltando.

## Torne a pesquisa útil sem substituir a fonte

O software cria cópias pesquisáveis, como texto extraído, descrições e índices. Essas cópias apontam para a fonte inalterada. Eles podem ser reconstruídos quando um método melhor estiver disponível.

Isso é diferente de pedir a um modelo de linguagem que resuma uma pilha de arquivos e depois tratar o resumo como memória. Um resumo é uma visualização posterior. Nunca substitui o material que descreve.

## Deixe que leitores locais focados façam descobertas limitadas

Métodos locais separados examinam recursos definidos da fonte. Alguns olham para a estrutura da linguagem. Outros identificam declarações, possíveis relações, raciocínios, mudanças ao longo do tempo ou observações sobre a experiência e os valores humanos.

Esses métodos não são pequenos chatbots. Eles realizam trabalhos estreitos contra material economizado. Cada descoberta identifica a passagem examinada, o método utilizado, a data e os limites conhecidos. Um método pode encontrar algo, não encontrar nada, recusar-se a responder ou falhar. Não pode reescrever o trabalho de outro método.

## Mantenha a história como história

Novas descobertas são adicionadas ao lado de eventos anteriores. As correções não apagam os erros. Uma conclusão posterior pode tornar-se atual, enquanto a conclusão anterior permanece visível com as evidências e circunstâncias que uma vez a apoiaram.

Isto permite que o trabalho posterior responda não apenas “no que se acredita agora?” mas também “o que mudou, por que mudou e quanto custou a mudança?”

## Reúna evidências para uma solicitação

O construtor de solicitações começa com o propósito da resposta ou documento. Ele identifica o que o leitor precisa, reúne as fontes e descobertas relacionadas a essas questões e registra o que foi incluído e o que foi deixado de fora.

Um serviço de chat comercial geralmente pede ao modelo para trabalhar a partir de qualquer texto que se encaixe na solicitação atual. Aqui, a seleção de evidências é uma etapa registrada fora do modelo. O modelo não pode decidir silenciosamente que a história perdida não importa.

## Use modelos como contribuidores

Um modelo de linguagem pode ser útil para pesquisa, formação ampla ou redação. Recebe material selecionado para um trabalho declarado.

A instalação atual também utiliza um pequeno localQwenmodelo para um propósito específico: depois de uma análise local focada ter examinado uma conversa completa,Qwenadiciona conhecimento básico comum que ajuda a conectar as descobertas separadas. Não se torna a memória, não recupera pensamentos ocultos ou decide o que significa a troca.

Seja local ou online, uma resposta modelo é salva como uma contribuição datada. Pode ser verificado, corrigido, rejeitado ou substituído sem alterar a fonte.

## Verifique o trabalho fora do escritor

Verificações separadas comparam uma resposta ou documento finalizado com suas fontes, cobertura necessária e limites declarados. A versão exata que passou é registrada.

Um modelo de linguagem não pode tornar verdadeira sua própria afirmação escrevendo com confiança. Também não pode fazer com que o seu próprio trabalho seja aceite dizendo que seguiu as instruções.

## Use qualquer tela adequada

O incluídoLibreChatfork fornece uma tela de conversação para solicitar trabalho e ler resultados. Ele não armazena o registro duradouro, não direciona todas as outras partes nem aprova respostas.

LibreChatpode ser substituído por outra tela.Qwenpode ser substituído por outro modelo adequado. Um provedor online pode ser alterado ou omitido. O histórico de origem e o trabalho aceito permanecem utilizáveis ​​porque nenhuma dessas partes os possui.

## O limite que define o projeto

Os modelos de linguagem geram contribuições temporárias a partir do material que lhes é mostrado.Robot Brain preserva a fonte, organiza o trabalho em torno dela, registra alterações, prepara solicitações limitadas e verifica o que retorna.

É por isso que este não é outro modelo de linguagem, um modelo proxy ou um chatbot melhor. Modelos podem participar do trabalho. O trabalho não depende de nenhum modelo.
