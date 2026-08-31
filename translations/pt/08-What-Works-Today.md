> Português: Tradução assistida por máquina da fonte oficial em inglês. Correções no idioma nativo são bem-vindas. [Inglês](../../08-What-Works-Today.md) | [Todos os idiomas](../README.md)

# O que a implementação atual faz

![Ideias, testes, falhas e habilidades comprovadas permanecem claramente separados.](../../illustrations/evidence-implementation-gates.png)

Robot Brain está executando um software para preservar e reconstruir o significado do trabalho gravado. Não é uma proposta de chatbot e sua implementação atual não é um modelo de linguagem.

## Capacidades na implementação atual

As execuções registradas mostram que o software pode:

- preservar uma conversa concluída sem substituí-la por um resumo
- mantenha as palavras da pessoa separadas das respostas do modelo e da interpretação posterior
- criar descobertas detalhadas sobre linguagem, significado, raciocínio, tempo, experiência humana e valores
- conectar cada descoberta retida à parte da conversa por trás dela
- manter correções, divergências, falhas no trabalho e perguntas não respondidas
- adicione uma visão geral de conhecimento geral local datada sem chamar o modelo online original
- reunir as contribuições retidas para uma reconstrução solicitada
- registrar o que foi verificado, rejeitado, corrigido e aceito
- substitua uma tela ou modelo de idioma participante sem substituir o histórico salvo

Estas são funções do software em torno dos modelos. Não são habilidades reivindicadasQwen,LibreChatou um assistente online.

## O que aconteceu no marco da conversa concluída

A conversa testada foi salva com as mensagens da pessoa e as respostas da modelo online em ordem.

Métodos locais focados produziram então registros separados sobre a troca. Seu trabalho cobriu linguagem e significado, raciocínio, observações psicológicas, observações filosóficas, relacionamentos e mudanças ao longo do tempo. Cada contribuição retida permaneceu vinculada ao material de origem e ao método que o produziu.

Esses métodos detalhados intencionalmente não carregam o amplo conhecimento prévio de um modelo de uso geral. Um pequeno localQwenmodelo, atendido porvLLM, leia o material selecionado e adicione uma visão geral datada. Sua função era fornecer informações básicas que conectassem as descobertas separadas e tornassem a troca compreensível como um todo.

Qwennão recuperou os pensamentos ocultos, o histórico de treinamento ou o estado interno privado do modelo original. A contribuição útil do modelo original já estava presente nas mensagens salvas. Um amplo conhecimento prévio foi fornecido por um modelo local substituível porque esse conhecimento não era exclusivo do fornecedor original.

## O que “completo” significa para este marco

A palavra refere-se à lista mantida de contribuições para esta execução. Cada mensagem fonte e cada contribuição que o processo reteve para a reconstrução podem ser encontradas e reunidas novamente.

Isso não significa que um modelo forneceu uma interpretação completa. A conquista é que as peças aceitas sejam preservadas, separadas por fonte e método, e disponíveis para reconstrução sem reexecutar a troca online original.

## Como a reivindicação é apoiada

A execução registra quais partes foram executadas, o que cada uma recebeu, o que cada uma retornou, quais contribuições foram rejeitadas e quais verificações foram aprovadas. A reconstrução é medida em relação à sua própria lista salva de registros esperados.

Um teste de componente é descrito como um teste de componente. Um trecho conectado é descrito como um trecho conectado. O trabalho planejado permanece separado da implementação atual.

O próximo trabalho inclui testes independentes mais amplos, suporte para mais tipos de registros, mais idiomas e culturas, telas de revisão mais claras e melhor medição do tempo que as pessoas passam lendo e corrigindo resultados.
