# What each part does—and what no model controls

![Original sources support a lasting history while replaceable tools perform limited work.](illustrations/core-architecture-layers.png)

Robot Brain is a collection of cooperating parts built around one lasting record. It is not one large language model, a group of models pretending to be one, or a chat service with extra search.

The distinction matters because the problems being addressed come from asking a temporary language-model service to serve as memory, researcher, writer, checker, and judge at the same time. This software separates those jobs and keeps the person's history outside every model.

## Save the event before interpreting it

The source keeper saves the conversation, note, image, document, task, or other item as it arrived. It also saves facts that are actually known, such as the arrival time, source, creator when established, and permission when recorded.

A filename, model guess, or later interpretation cannot silently become a fact about the source. Missing information remains missing.

## Make search useful without replacing the source

The software creates searchable copies such as extracted text, descriptions, and indexes. These copies point back to the unchanged source. They can be rebuilt when a better method becomes available.

This is different from asking a language model to summarize a pile of files and then treating the summary as the memory. A summary is one later view. It never replaces the material it describes.

## Let focused local readers make limited findings

Separate local methods examine defined features of the source. Some look at the structure of language. Others identify statements, possible relationships, reasoning, changes over time, or observations about human experience and values.

These methods are not little chatbots. They perform narrow jobs against saved material. Each finding identifies the passage examined, the method used, the date, and known limits. A method may find something, find nothing, decline to answer, or fail. It cannot rewrite another method's work.

## Keep history as history

New findings are added beside earlier events. Corrections do not erase mistakes. A later conclusion can become current while the earlier conclusion remains visible with the evidence and circumstances that once supported it.

This lets later work answer not only “what is believed now?” but also “what changed, why did it change, and what did the change cost?”

## Gather evidence for one request

The request builder starts with the purpose of the answer or document. It identifies what the reader needs, gathers the sources and findings that bear on those questions, and records what was included and left out.

A commercial chat service usually asks the model to work from whatever text fits into the current request. Here, evidence selection is a recorded step outside the model. The model cannot quietly decide that missing history does not matter.

## Use models as contributors

A language model may be useful for research, broad background, or writing. It receives selected material for a declared job.

The current installation also uses a small local Qwen model for one specific purpose: after focused local analysis has examined a completed conversation, Qwen adds ordinary background knowledge that helps connect the separate findings. It does not become the memory, recover hidden thoughts, or decide what the exchange means.

Whether local or online, a model response is saved as a dated contribution. It can be checked, corrected, rejected, or replaced without changing the source.

## Check work outside the writer

Separate checks compare a finished answer or document with its sources, required coverage, and stated limits. The exact version that passed is recorded.

A language model cannot make its own claim true by writing confidently. It also cannot make its own work accepted by saying that it followed the instructions.

## Use any suitable screen

The included LibreChat fork provides a conversational screen for requesting work and reading results. It does not store the lasting record, direct every other part, or approve answers.

LibreChat can be replaced by another screen. Qwen can be replaced by another suitable model. An online provider can be changed or omitted. The source history and accepted work remain usable because none of those parts owns them.

## The boundary that defines the project

Language models generate temporary contributions from the material they are shown. Robot Brain preserves the source, organizes the work around it, records change, prepares limited requests, and checks what comes back.

That is why this is not another language model, a model proxy, or a better chatbot. Models can participate in the work. The work does not depend on any one model.
