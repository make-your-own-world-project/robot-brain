# Lessons that changed the design

![Lessons from working and failed approaches remain available for the next design.](illustrations/discoveries-engineering-lessons.png)

The design grew through testing, including failed approaches. The lessons below explain why it looks different from a commercial chat service.

## The writing study used cleared public material

To study how different kinds of writing are organized, the project examined selected public-domain books, speeches, United States government writing, and historical newspapers. A small number of public standards that expressly allow public use were examined separately.

The work measured and compared writing. It did not train a new general language model. The public documents do not include copies of the source texts.

Each study record identifies the public source, why it could be examined, what part was used, and a short digital fingerprint confirming the exact material. A large Project Gutenberg index released under CC BY 4.0 was inspected only to understand its contents; the indexed books were not downloaded or measured through that index.

## Separate methods preserve what they find

Local methods examine language, meaning, relationships, reasoning, time, human experience, and values. Each method saves its own findings with the part of the conversation behind them.

This keeps one method from swallowing the others. A finding can be corrected without rewriting the source or every other analysis.

## General knowledge connects the pieces

Focused methods can produce accurate findings that remain hard to understand together. They do not share the broad background knowledge a language model uses when reading an ordinary conversation.

A small Qwen model running locally adds that background after the focused work is complete. It helps explain the situation, the participants' goals, the reason for a request, and how one event led to another.

The local model does not recover the original assistant's hidden knowledge. The assistant's contribution is already present in its messages. Qwen supplies general background that is broad enough for another suitable model to provide.

Its reading is dated and kept separately. A later model can add a different view without rewriting the earlier one.

## Model training keeps influence but loses the full human record

A language model learns useful patterns from human-created material. It does not keep every work intact with its creator, purpose, evidence, disagreement, and later history attached.

The model may reproduce words or use an idea well. It still cannot reliably rebuild why those words existed, what their author meant, whose account was missing, or what later corrected the work.

No software can recover history that a model never kept. This design can prevent the same loss from happening to the person's own records.

## Bias is not one simple setting

What a model can recognize depends on what people created, what archives preserved, which languages were collected, how material was translated and labeled, what builders rewarded, and which product rules were added later.

No single score can explain all of that. The practical response is to keep sources visible, identify the model and date behind a finding, preserve disagreement, and leave missing information marked as missing.

## A larger prompt is still temporary

Giving a model more text can help one request. It does not create dependable memory. The selected material may be shortened during the conversation, and another model may interpret it differently later.

The saved record must exist before and after the request.

## Similar words do not prove a relationship

Search can find possible matches. It cannot establish that one passage caused, corrected, contradicted, or continued another.

Those relationships need their own evidence.

## “No answer” can be the correct answer

“Not found,” “does not apply,” “unknown,” and “false” mean different things. Every focused reader and language-model contribution must preserve those differences instead of generating a likely answer merely to keep the conversation moving.

## Rejected work still teaches something

An unsupported answer does not enter accepted knowledge. The answer and the reason for rejecting it can still prevent the same mistake from being purchased and checked again.

## Keep track of who said what

Human words, quotations, model responses, local findings, and later reviews cannot be blended together without changing their meaning.

Every contribution stays labeled with its source.

## Planning, writing, and checking are different jobs

The request builder can choose the right evidence while a language model still writes badly. A model can write clearly from the wrong evidence. It can also follow the evidence and still fail the reader by producing far too much text.

Keeping selection, writing, and checking separate makes the failure visible. The failed part can be replaced without rebuilding everything.

## A full document needs one plan

Writing sections independently produced repetition, changing terms, and unsupported connections. A document must be planned and checked as one piece even when several tools help create it.

## Reading and correction are real costs

Reading filler, searching for buried answers, and correcting repeated mistakes take a person's time and energy. That cost belongs in any honest account of the result.

## Outside help does not need the whole history

An online language model can receive enough evidence for one task without receiving unrelated records, private history, or the tools that prepare future requests.

The useful response comes back. The full record stays where the person controls it.
