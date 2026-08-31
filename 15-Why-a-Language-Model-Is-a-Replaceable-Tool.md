# Use a language model for the job, not as the memory

![Tools, trained files, and source collections keep separate records of their origin and terms.](illustrations/tool-model-source-index.png)

Robot Brain is not a language model with extra memory. It is the recordkeeping, analysis, assembly, and checking software that decides when a language model would help and what limited job it may perform.

The most powerful available model is not always the best choice for that job.

A paid language model may be right for difficult research or writing. A small local model may be enough for background explanation. Search may be enough to find a passage. A fixed process may be safer when the answer must follow an exact rule. Sometimes the best answer is one that was already checked and saved.

The request builder makes that choice from the job's needs. It may use a model, combine several limited methods, reuse checked work, or make no model call at all. That is why this is not a proxy that simply forwards requests to another service.

## Paid online models

Commercial language-model services helped build this project. They supported research, coding, writing, and review.

They also lost earlier instructions, shortened conversations, guessed at causes, buried short answers in filler, and reported work as complete before checking it. Correcting those failures used more paid allowance and more human time.

Their deeper limit is not a bad prompt. A trained model cannot rebuild the complete history of the human work that taught it. It keeps patterns while losing dependable links to every author, purpose, audience, dispute, correction, and missing viewpoint.

That broad knowledge is still useful. It simply should not become the only place where someone's history exists.

For an online request, Robot Brain records which model was used, what it received, what it returned, what the service cost, which checks ran, and whether the result was kept. Unsupported background remains the model's suggestion rather than a sourced fact.

## The local model is not trained on the person

The current installation runs a small Qwen language model through vLLM on local hardware. Qwen is one replaceable contributor, not the project itself.

It does not learn by training on the person's conversations, work, or life. Training would mix that history into a model and weaken the path back to the original words and events.

Instead, Qwen receives selected material for one job after a conversation has ended. Other local methods have already examined the language, statements, relationships, reasoning, time, human experience, and values in the exchange. Qwen adds the broad background those methods do not share. This makes it easier to explain what happened and why.

Qwen does not reveal the online assistant's hidden thoughts, training, or private reasoning. The online assistant's useful contribution is already present in the saved conversation. General background knowledge is not unique to that assistant, so another suitable model can help connect the recorded pieces.

The Qwen reading is saved with the model name and date. It remains separate from the conversation and can be corrected or replaced later. The request never has to leave the local hardware.

## Search is not an explanation

Search can find passages with related words or subjects. It cannot decide why an event mattered, whether one action caused another, or what someone meant.

Those conclusions need evidence, history, and room for correction.

## Cost includes the person's time

Price and speed are not the only costs. A cheap answer becomes expensive when someone spends hours finding the error, explaining the history again, and repairing the result.

The request builder therefore considers service fees, waiting, retries, energy use, and human checking. A smaller model, a fixed local method, or a saved result may create more value when its work is easier to inspect.

## Sources remain identifiable

Original records, copied text, model responses, public research, quotations, and later reviews stay as different things.

When known and permitted, the record keeps the creator, purpose, audience, date, language, evidence, disagreement, rights, and later corrections. Public availability and credit do not by themselves grant permission to redistribute protected material.

This repository includes public documentation and project-created illustrations. It leaves out private records, passwords, access details, provider secrets, and outside material that has not been cleared for release.
