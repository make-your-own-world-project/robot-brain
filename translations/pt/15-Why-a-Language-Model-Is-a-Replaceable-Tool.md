> Português: Tradução assistida por máquina da fonte oficial em inglês. Correções no idioma nativo são bem-vindas. [Inglês](../../15-Why-a-Language-Model-Is-a-Replaceable-Tool.md) | [Todos os idiomas](../README.md)

# Use um modelo de linguagem para o trabalho, não como memória

![Ferramentas, arquivos treinados e coleções de fontes mantêm registros separados de sua origem e termos.](../../illustrations/tool-model-source-index.png)

Robot Brain não é um modelo de linguagem com memória extra. É o software de manutenção de registros, análise, montagem e verificação que decide quando um modelo de linguagem ajudaria e que trabalho limitado ele pode realizar.

O modelo mais potente disponível nem sempre é a melhor escolha para esse trabalho.

Um modelo de linguagem pago pode ser adequado para pesquisas ou redações difíceis. Um pequeno modelo local pode ser suficiente para uma explicação básica. A pesquisa pode ser suficiente para encontrar uma passagem. Um processo fixo pode ser mais seguro quando a resposta deve seguir uma regra exata. Às vezes, a melhor resposta é aquela que já foi verificada e salva.

O construtor de solicitações faz essa escolha com base nas necessidades do trabalho. Ele pode usar um modelo, combinar vários métodos limitados, reutilizar o trabalho verificado ou não fazer nenhuma chamada de modelo. É por isso que este não é um proxy que simplesmente encaminha solicitações para outro serviço.

## Modelos online pagos

Os serviços de modelo de linguagem comercial ajudaram a construir este projeto. Eles apoiaram pesquisa, codificação, redação e revisão.

Eles também perderam instruções anteriores, encurtaram conversas, adivinharam as causas, enterraram respostas curtas em preenchimento e relataram o trabalho como concluído antes de verificá-lo. A correção dessas falhas exigiu mais subsídios pagos e mais tempo humano.

Seu limite mais profundo não é uma sugestão ruim. Um modelo treinado não pode reconstruir a história completa do trabalho humano que o ensinou. Ele mantém padrões enquanto perde links confiáveis ​​para cada autor, propósito, público, disputa, correção e ponto de vista ausente.

Esse amplo conhecimento ainda é útil. Simplesmente não deveria se tornar o único lugar onde existe a história de alguém.

Para uma solicitação on-line,Robot Brain registra qual modelo foi utilizado, o que recebeu, o que retornou, qual o custo do serviço, quais verificações foram realizadas e se o resultado foi mantido. Os antecedentes não comprovados continuam sendo uma sugestão do modelo, e não um fato originado.

## O modelo local não é treinado na pessoa

A instalação atual executa um pequenoQwenmodelo de linguagem atravésvLLMem hardware local.Qwené um contribuidor substituível, não o projeto em si.

Ele não aprende treinando nas conversas, no trabalho ou na vida da pessoa. O treinamento misturaria essa história em um modelo e enfraqueceria o caminho de volta às palavras e eventos originais.

Em vez de,Qwenrecebe material selecionado para um trabalho após o término da conversa. Outros métodos locais já examinaram a linguagem, as declarações, as relações, o raciocínio, o tempo, a experiência humana e os valores na troca.Qwenacrescenta o contexto amplo que esses métodos não compartilham. Isso torna mais fácil explicar o que aconteceu e por quê.

Qwennão revela os pensamentos ocultos, o treinamento ou o raciocínio particular do assistente online. A contribuição útil do assistente online já está presente na conversa salva. O conhecimento geral não é exclusivo desse assistente, portanto, outro modelo adequado pode ajudar a conectar as peças gravadas.

OQwena leitura é salva com o nome do modelo e a data. Permanece separado da conversa e pode ser corrigido ou substituído posteriormente. A solicitação nunca precisa sair do hardware local.

## Pesquisa não é uma explicação

A pesquisa pode encontrar passagens com palavras ou assuntos relacionados. Não pode decidir por que um evento foi importante, se uma ação causou outra ou o que alguém quis dizer.

Essas conclusões precisam de evidências, história e espaço para correção.

## O custo inclui o tempo da pessoa

Preço e velocidade não são os únicos custos. Uma resposta barata torna-se cara quando alguém passa horas encontrando o erro, explicando novamente o histórico e reparando o resultado.

O construtor de solicitações, portanto, considera taxas de serviço, espera, novas tentativas, uso de energia e verificação humana. Um modelo menor, um método local fixo ou um resultado salvo podem criar mais valor quando seu trabalho for mais fácil de inspecionar.

## As fontes permanecem identificáveis

Registros originais, textos copiados, respostas modelo, pesquisas públicas, citações e revisões posteriores permanecem como coisas diferentes.

Quando conhecido e permitido, o registro guarda o criador, finalidade, público, data, idioma, evidências, divergências, direitos e correções posteriores. A disponibilidade pública e o crédito não garantem, por si só, permissão para redistribuir material protegido.

Este repositório inclui documentação pública e ilustrações criadas por projetos. Ele deixa de fora registros privados, senhas, detalhes de acesso, segredos do provedor e material externo que não foi liberado para divulgação.
