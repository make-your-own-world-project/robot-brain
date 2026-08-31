> Português: Tradução assistida por máquina da fonte oficial em inglês. Correções no idioma nativo são bem-vindas. [Inglês](../../README.md) | [Todos os idiomas](../README.md)

# Mantenha o registro. Substitua o modelo.

![Os registros de uma pessoa permanecem em um só lugar, enquanto partes de trabalho separadas cuidam de trabalhos limitados.](../../illustrations/specialist-assembly-line-vs-giant-chatbot.png)

Robot Brain é um software para preservar a história e o significado por trás do trabalho humano de longa duração. Não é um modelo de linguagem, um chatbot ou um serviço que encaminha todas as perguntas para um modelo.

Grandes modelos de linguagem podem pesquisar, escrever, explicar e ajudar a resolver problemas difíceis. Os serviços pagos construídos em torno deles ainda são espaços de trabalho temporários. Eles podem encurtar uma longa conversa, perder instruções anteriores, separar conclusões de suas evidências e continuar escrevendo como se a história perdida ainda estivesse presente. Uma pessoa então gasta mais tempo e uso pago reconstruindo o contexto que já foi fornecido.

Este software muda onde reside o valor duradouro. As conversas, documentos, decisões, tentativas fracassadas, correções e perguntas não respondidas da pessoa permanecem nos registros que a pessoa controla. Os programas locais podem examinar esses registros. Um modelo de linguagem pode ajudar em um trabalho selecionado, mas sua contribuição retorna para registro como um trabalho datado e passível de revisão. O modelo pode então ser substituído sem levar consigo o histórico.

[Leia esta documentação em outro idioma.](../README.md)

## A diferença em uma visão

| Um serviço de modelo de linguagem comercial | Robot Brain |
|---|---|
| Produz uma resposta a partir do material atualmente em sua visualização de trabalho. | Mantém a fonte completa e o histórico em torno dela. |
| Pode encurtar ou perder conversas anteriores à medida que o trabalho cresce. | Salva conversas fora de cada modelo para que possam ser usadas novamente. |
| Combina conhecimento aprendido de muitas fontes sem um caminho completo de volta a cada fonte e suas circunstâncias. | Mantém cada fonte conhecida, descoberta posterior, correção e discordância como um registro separado. |
| Pode escrever, pesquisar, planejar e julgar sua própria resposta em uma única troca. | Permite salvar, pesquisar, analisar, escrever, verificar e aprovar partes separadas com autoridade limitada. |
| Controla o modelo, as regras de serviço, os limites de uso e as alterações do produto. | Deixa o registro duradouro sob o controle da pessoa. |
| É pago por tentativas fracassadas e trocas corretivas, bem como por trabalho útil. | Mantém falhas e correções para que suas aulas não precisem ser adquiridas novamente. |

Robot Brain pode chamar um modelo de idioma local ou online. Isso não o transforma em um proxy modelo. Ele pode preservar, pesquisar, comparar, organizar e reconstruir trabalhos anteriores sem chamar o modelo que participou da conversa original. Quando um modelo é útil, a solicitação é uma etapa de um processo maior que existe independentemente desse modelo.

## Por que isso foi construído

Os modelos de uso geral mais bem pagos disponíveis durante o desenvolvimento eram guardiões capazes, mas não confiáveis, de um trabalho longo.

As falhas registradas incluíam instruções perdidas, evidências ausentes, conexões inventadas, reivindicações prematuras de conclusão, alterações indesejadas e danos aos arquivos de trabalho. Corrigir essas falhas exigiu mais solicitações, mais testes, mais subsídios pagos e mais tempo e energia da pessoa. Os serviços não devolveram automaticamente o uso gasto em trabalhos inutilizáveis ​​ou as trocas necessárias para repará-los.

O problema era maior do que qualquer resposta ruim. Um gerador de texto temporário estava sendo solicitado para servir como memória, historiador, pesquisador, escritor, verificador e juiz final. A mudança de modelos não alterou esse arranjo.

Robot Brain foi construído em torno de um arranjo diferente: manter primeiro o registro humano, permitir que várias peças substituíveis contribuam para ele e exigir evidências fora do modelo gerador antes que um trabalho importante seja aceito.

## O que um modelo treinado não pode manter

Um grande modelo de linguagem aprende padrões de enormes coleções de trabalho humano. Esses padrões tornam o modelo útil, mas o modelo não é uma biblioteca das obras completas que o moldaram.

Dentro do modelo, a influência de livros, artigos, conversas, traduções, comunidades, rótulos e feedback humano é mesclada. O modelo geralmente não consegue mostrar quais fontes moldaram uma frase específica. Não pode restaurar o propósito, o público, as evidências, as divergências, as correções posteriores ou os pontos de vista ausentes de cada autor.

Isso é uma perda de sentido mesmo quando a obra original ainda existe em outro lugar. O modelo retém alguma utilidade do trabalho, ao mesmo tempo que descarta o caminho confiável de volta ao seu ambiente humano.

O mesmo problema aparece durante o uso normal. Uma resposta final pode sobreviver depois que a conversa que lhe deu sentido tiver sido abreviada. A conclusão permanece, mas as tentativas fracassadas, a incerteza e as razões por trás dela desaparecem da visão de funcionamento do modelo.

Este projeto não responde a esse problema treinando outro modelo na vida de uma pessoa. A história pessoal permanece legível e rastreável em vez de ser combinada com outro modelo treinado. Os modelos funcionam com registros selecionados; eles não se tornam os registros.

## O que cada parte faz

O software funcional separa as tarefas que um serviço de chat geralmente faz parecer uma atividade:

1. **O guardião da fonte salva o que aconteceu.** Ele retém a conversa, o documento, a imagem ou outro material sem substituí-lo por um resumo.
2. **Cópias pesquisáveis ​​facilitam a localização da fonte.** Texto, descrições e índices copiados apontam para a fonte inalterada e podem ser reconstruídos.
3. **Leitores locais focados examinam recursos específicos.** Métodos separados analisam a linguagem, as declarações, os relacionamentos, o raciocínio, o tempo, a experiência humana e os valores. Cada um relata apenas suas próprias descobertas e as passagens por trás delas.
4. **O registro do histórico mantém as alterações visíveis.** Novas descobertas, correções, divergências, tentativas fracassadas e perguntas abertas são adicionadas sem reescrever eventos anteriores.
5. **O construtor de solicitações reúne o que um trabalho precisa.** Ele seleciona fontes e descobertas relevantes e registra o que foi incluído ou deixado de fora.
6. **Um modelo linguístico pode acrescentar ajuda limitada.** Um modelo local pode fornecer uma experiência ampla. Um modelo online pode ajudar em pesquisas ou redações difíceis. Qualquer uma das respostas permanece uma contribuição datada que pode ser verificada, rejeitada ou substituída.
7. **Verificações separadas comparam o resultado com a solicitação e a evidência.** O modelo que escreveu uma resposta não pode declarar seu próprio trabalho aceito.
8. **Uma tela permite que uma pessoa use o software.** O software incluídoLibreChatfork é uma dessas telas. Substituí-lo não substitui os registros ou outras peças funcionais.

Nenhuma parte é apresentada como um assistente onisciente. Seus trabalhos limitados são o que torna cada peça substituível.

## Tornando uma conversa concluída útil novamente

Uma conversa concluída contém a solicitação da pessoa, as respostas reais do modelo de linguagem, o trabalho tentado, as falhas, as correções e o ponto onde a troca terminou. Essas mensagens preservam a contribuição do modelo original sem exigir que esse modelo se explique posteriormente.

Leitores locais focados examinam a troca salva de vários ângulos. Eles podem encontrar padrões e relacionamentos detalhados sem depender de um amplo conhecimento mundial. Suas descobertas separadas permanecem ligadas a partes exatas da conversa.

Essas descobertas ainda podem precisar de conhecimento prévio comum antes de formarem um relato claro. Para esse passo limitado, um pequenoQwenmodelo é executado localmente por meiovLLM. Ele adiciona uma visão geral datada que ajuda a conectar as descobertas detalhadas e a explicar o que a troca realizou.

Qwennão recupera os pensamentos ocultos ou o histórico de treinamento do modelo online. Fornece amplo conhecimento prévio que não é exclusivo do modelo original. A contribuição útil do modelo original já está preservada nas palavras que produziu.

OQwena visão geral é armazenada ao lado da fonte e das descobertas anteriores. Pode ser corrigido ou substituído. A conversa original e a análise local detalhada permanecem inalteradas.

## O que está funcionando agora

A implementação atual pode preservar uma conversa concluída, examiná-la através de métodos locais separados, adicionar uma leitura local de conhecimento geral e reunir todas as contribuições retidas em um registro que pode ser reconstruído posteriormente.

Também pode preparar um pedido limitado para um modelo online quando a ajuda externa for útil. Esse serviço recebe apenas o material selecionado. A sua resposta regressa ao registo local, onde as verificações e a aprovação humana: e não o modelo: decidem o que é mantido.

Esta é a conquista central: o trabalho que antes dependia de uma conversa temporária pode permanecer útil depois que sua tela de chat, modelo e provedor desaparecem.

## Leia a explicação completa

- [Por que grandes modelos de linguagem não conseguem preservar a história completa](01-Why-Large-Language-Models-Cannot-Preserve-the-Full-Story.md)
- [O que cada parte faz: e o que nenhum modelo controla](02-A-Lasting-Record-Outside-the-Model.md)
- [Mantenha a correção sem apagar o erro](03-How-Knowledge-Changes-Without-Erasing-History.md)
- [Siga uma reivindicação de volta às evidências](04-How-Every-Claim-Can-Be-Checked.md)
- [Construa o documento antes de escrever a prosa](05-How-Evidence-Becomes-a-Finished-Document.md)
- [Explique a mesma verdade para diferentes leitores](06-One-Meaning-Different-Readers.md)
- [Mantenha o histórico privado sob o controle da pessoa](07-Privacy-and-Control-Stay-With-People.md)
- [O que a implementação atual faz](08-What-Works-Today.md)
- [Por que o design baseia-se em muitos campos](09-How-Research-Strengthens-the-System.md)
- [Ajude sem entregar registros privados](11-Contribute-Without-Giving-Up-Control.md)
- [Palavras usadas nestes documentos](12-A-Short-Guide-to-Key-Terms.md)
- [Siga uma solicitação através das peças de trabalho](13-The-Parts-Running-Today.md)
- [Use um modelo de linguagem para o trabalho, não como memória](15-Why-a-Language-Model-Is-a-Replaceable-Tool.md)
- [Falhas observadas em serviços pagos de modelo linguístico: e as salvaguardas a que levaram](16-What-Commercial-Language-Model-Services-Got-Wrong.md)
- [Lições que mudaram o design](17-How-Language-Models-Lose-Meaning-and-How-to-Preserve-It.md)
- [Notas de uso público, crédito e privacidade](18-Use-Attribution-and-Limits.md)
- [Como uma conversa completa se torna um conhecimento duradouro](19-What-the-System-Accomplishes.md)
- [O que vem a seguir](20-Where-the-System-Goes-Next.md)

## Créditos, fontes e direitos

- [O que ajudou a moldar este trabalho](10-What-Helped-Shape-This-Work.md)
- [Pesquisa por trás do design](14-Sources-Behind-the-Design.md)
- [Fontes, licenças e verificações de liberação pública](../../SOURCES-LICENSES-AND-PRIVACY.md)

## Licença

A redação original, diagramas e ilustrações do projeto estão disponíveis sob o domínio da organização[Licença Creative Commons Atribuição 4.0 Internacional](../../LICENSE.md), a menos que um documento indique termos diferentes. O material criado por terceiros mantém seus próprios direitos e termos.

## Independência e privacidade

Este é um projeto pessoal independente desenvolvido com base em tempo pessoal, equipamentos, contas e serviços pagos. Nenhum empregador participou. Mencionar qualquer pessoa, empregador, instituição, fornecedor modelo, grupo de pesquisa, regra compartilhada ou projeto externo não implica participação, aprovação, parceria ou endosso.

A divulgação pública exclui registros privados, detalhes de identificação, senhas, informações de conexão privada, informações do empregador e instruções para acessar serviços privados. As descrições das falhas do modelo são limitadas ao comportamento registrado e seus efeitos; eles não reivindicam causas ou motivos não revelados. Os documentos não são conselhos profissionais ou promessas de resultados.

![Um caminho da memória controlada pelo provedor até os registros que permanecem com as pessoas a quem dizem respeito.](../../illustrations/open-door-human-future.png)
